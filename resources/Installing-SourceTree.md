---
layout: single
title: Installing Sourcetree
---

[SourceTree]: https://www.sourcetreeapp.com/

Sourcetree is a graphical application for git, which makes it easy to keep track
of changes to your work and to move your work between GitHub and your own
computer. It is available for Mac and for Windows.

This article describes how to download, install, and configure Sourcetree. 

<a name="download-sourcetree"></a>
## Download and install SourceTree

Download [SourceTree] from their website. 

### Mac version
If you download the Mac version:
   1. You should get a file called something like `Sourcetree_2.7.1d.zip`. 
   1. Double-click the file, which should unpack it, leaving a file called
      Sourcetree.
   1. Drag the file to your computer's `Applications` folder.

### Windows version
If you download the Windows version:
   1. You should get a file called `SourceTreeSetup-2.4.8.0.exe`.
   1. Double-click the file, which should open an installer. Follow the
      instructions to install.

_Note: I don't have Windows, so I wasn't able to verify that these instructions
work. Please let me know if they don't._
{: .notice--warning}

<a name="connect"></a>
## Connect Atlassian account to Sourcetree
   1. Open Sourcetree. You should see a dialog that will walk you through some
      configuration. 
   1. On the first screen:
      1. Click the box to agree to the Atlassian Customer Agreement (after
         reading it, of course!). 
      1. Decide whether you want to improve Sourcetree by sending data about
         your usage. 
      1. Click the `Continue` button.
   1. Create an Atlassian account (or use an existing one).
      + Unfortunately, Atlassian makes you create an account to use Sourcetree.
      + If you don't have an account (most likely scenario), click `Go to My
        Atlassian` and create an account. Atlassian will send you a confirmation
        email. Click on the link in the email to verify your account. Don't
        worry about filling out the information on the website.
      + Once you have an account, you should be able to continue with the setup.
   1. In the next pane (`Connect an Account`), click the `Skip Setup` button.

<a name="configure"></a>
## Configure Sourcetree
   1. Once Sourcetree is running, open the Preferences.
   1. In the `General` tab: 
       1. make sure that the `Allow Sourcetree to modify...` box is checked. 
       1. Underneath that checkbox, put your full name and the email address you
          use for Github. 
          
          **Warning:** This name and email address may become
          public, on GitHub, so make sure that you choose a name & email address
          that you're okay making public.
          {: .notice--warning}

   1. In the `Accounts` tab:
       1. Click the `Add...` button.
       1. For `Host`, choose `GitHub`.
       1. For `Auth Type`, choose `OAuth`.
       1. For `Protocol`, choose `HTTPS`.
       1. Click the `Connect Account` button.
       1. In the pop-up, log in to your GitHub account.
       1. Click `Save`.
   1. Close the Preferences pane.

You're ready to start using Sourcetree for our class! Check out the 
[Assignment HOWTO](./Assignment-HOWTO.html) to get started.