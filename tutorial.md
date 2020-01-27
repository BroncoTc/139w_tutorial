# This is bullshit, don't follow it, it's just a homework.

## How to setup KeePass for your first time
![keypass logo](https://keepass.info/images/icons/keepass_512x512.png)
KeePass is an open source password manager. This tutorial will introduce you to setup KeePass for the first time. It will involve initialize the KeePass storage database and link it to a browser to allow automatic password generation and fill-in. 

**Note:**
KeePass is not a simple consumer-friendly product, and this tutorial is **not for everyone**. It expects you to have knowledge and use experience with **at least one other password manager** (such as LastPass or 1Password) before. It also expects you to have decent knowledge about the operating system you are using.

---
####  Contents
**Part 1:** Install KeePass password manager
**Part 2:** Initialize your KeePass password storage
**Part 3:** Install KeePass browser extension
**Part 4:** Config the link between your browser and KeePass application

---
#### Part 1:  Install KeePass password manager

The KeePass password manager is a desktop application, thus requires you to install it on your operating system first before you can setup and use it.

This tutorial installed its KeePass on a Debian Linux distribution. Similar steps can be done on other Linux distributions.

**Steps:**
1. Open a Terminal with a sudoer account
2. Type in “sudo apt install keepass2” and enter “y” when prompted about whether to install the software.
![figure 2]()
3. Wait for the installation to complete. 
When it’s complete, you should be given back your access to your shell.
4. Open KeePass by click your super button on your keyboard and enter “keepass” into the displayed search box. KeePass button will appear and you will click on it to open KeePass.
![figure 3]()

**After this step, you should have your KeePass installed and prepared for you to initialize it.**

---

#### Part 2:  Initialize your KeePass password storage
The password storage of KeePass is a password-encrypted local file on your computer. You need to create the file inside KeePass software to start using KeePass.

**Steps:**
1. Click the "New" button on top-left corner of main user interface
![figure 4]()
2. Click "OK" on the prompted message box.
![figure 5]()
3. Choose a location you want to store your database file and click the "save" button on the "create new password database" dialog. (I recommend leave it at the default location"
4. Create your master password to protect your database and click “OK”
![figure 6]()
5. Give your new database a name. It can be any name you want and feel meaningful about. Enter your desired name into the "Database name" input box and click "OK".
![figure 7]()
6. Print your data-saver rescue sheet to protect all your passwords from being lost.
![figure 8]()

**Now you have been automatically return to the main KeePass interface with your password database created and opened**

---

#### Part 3:  Install KeePass browser extension
This part will instruct you to install a browser extension to use with your KeePass installation. My daily-drive browser is Mozilla Firefox. It is a completely open-source browser powered by a non-profit organization, which is a perfect companion with an open-source password manager. 

**Steps:**
1. Open [KeePassHttp-Connector](https://addons.mozilla.org/en-US/firefox/addon/keepasshttp-connector/) in your Mozilla Firefox browser.
2. Install the Add-on by click the "Add to Firefox" button
![figure 9]()
3. Click "Add" to allow the extension being installed on the prompted dialog box.

**Now you have your KeePass companion browser extension installed**

---
#### Part 4:  Config the link between your browser and KeePass application**
In this part, you will install a plugin for KeePass to allow it to communicate with other applications (including your browser) and setup the link between your browser extension and your KeePass application.

**Steps:**
1. Download [KeePassHttp Plugin](https://raw.github.com/pfn/keepasshttp/master/KeePassHttp.plgx) and save it to your KeePass plugin folder (It's `/usr/lib/keepass2/` on my system or `C:\Program Files (x86)\KeePass Password Safe 2\Plugins` for Windows)
2.  Quit KeePass by press `Ctrl+Q` in the KeePass main user interface
3.  Start KeePass again (as instructed in Part 2)
4.  Go to your browser, click the KeePass icon on the top-right corner, and click "Connect" as instructed by the window itself
![figure 10]()
5. Open up your KeePass interface and enter a desired key name (e.g. "firefox") in the pop-up window, and click "Save" to save the browser connection
6. Go back to your browser and click the KeePass icon again 

**Now you have your browser connected with your KeePass desktop application. You have finished the entire KeyPass setup process.**
