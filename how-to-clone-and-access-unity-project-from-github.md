---
layout: post
title: How to clone and access Unity Project from GitHub using SourceTree
---

# How to clone and access Unity Project from GitHub using SourceTree <!-- omit in toc -->

#### Table of Contents
- [Download SourceTree](#download-sourcetree)
- [Install SourceTree](#install-sourcetree)
- [After you Install](#after-you-install)
- [Connect your GitHub account](#connect-your-github-account)
- [Clone a remote repository](#clone-a-remote-repository)
- [After you clone a Unity Project](#after-you-clone-a-unity-project)

*Note: Links in italics are important.*

---

## Download SourceTree

Go to *[SourceTree Website][1]* to *download* and install **SourceTree**.

![Download SourceTree](/images/download_sourcetree_0.png)

---

## Install SourceTree

Launch the downloaded file and follow the installation.

---

## After you Install

- You'll have to **agree** to the **Atlassian Customer Agreement** and hit `Continue`.

- You need an **Atlassian account** to use `Sourcetree`. 

![Log in to your Atlassian account](images/sourcetree_aa.png)

- When you get to this screen, click either `Use an existing account` or `Go to My Atlassian` and follow the prompts to *[create a new account][2]*. 
- Once you've got an account, you'll be able to `log in` with `Use an existing account`.

---

## Connect your GitHub account

To add repositories to **Sourcetree**, log in with your `GitHub` account.

1.	Click the gear icon and select Accounts.
	![Settings](images/Screen+Shot+2018-02-28+at+10.17.41+am.png)

2.	Click Add from the Accounts tab.

3.	After you select a Host, enter your hosting details. If you selected GitHub, keep the default AUTH Type and click Connect Account to enter your credentials.
	![Add account](images/sourcetree_add_account.png)

4.	When you enter your account details, you can choose whether you prefer to connect with HTTPS or SSH. For information about setting up SSH for your account, see *[Set up an SSH key][3]*.

---

## Clone a remote repository

If you have an existing remote repository on GitHub, you need to copy or clone it to your computer.

1.	From SourceTree, click Remote. All of your remote projects display.
	![Remotes](images/Screen+Shot+2018-02-28+at+11.01.12+am.png)

2.	Click Clone next to the repository you wish to clone locally.
3.	From the Clone a repository window, click Clone. Click Local to see a list of your cloned repositories. 

---

## After you clone a Unity Project

There is nothing more to do, just open Unity and select the currently cloned location to open the project.

---

[1]: http://www.sourcetreeapp.com
[2]: https://id.atlassian.com/signup?application=mac&continue=https%3A%2F%2Fmy.atlassian.com%2Fproducts%2Findex&_ga=2.226597081.535148348.1557168519-733480428.1557168519
[3]: https://confluence.atlassian.com/bitbucket/set-up-an-ssh-key-728138079.html
