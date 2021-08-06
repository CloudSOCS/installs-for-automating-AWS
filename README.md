![CloudSOC logo](/pic/cloudsocs.png)

Setting up Homebrew, Atom, Python3, pipenv, Node, Serverless, awscli, Git, and ssh for Automating AWS With Python




To install Homebrew go to [Homebrew](http://brew.sh) Home page or  run the install script on the command line below
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
If you don’t have Apples Xcode Command Line Tools installed it will alert you to that it will install it and carry on with the Homebrew installation and download the Command Line Tools you will need to enter your admin password at some point.
To check for any issues with Homebrew run:
```
brew doctor
```
Homebrew Cask extends Homebrew. Bringing its simplicity and speed to the installation and management of GUI macOS applications such as Atom and Google Chrome.

To install Atom using Homebrew Cask you can run the following simple command:
```
 brew install atom
 ```
 Atom is a highly customizable text editor. With the right plugins, it can approach the functionality of an IDE.  Text editors, also called code editors, are applications used by developers to write code. They highlight and format your code so that it’s easier to read and understand.

 ![](/pic/48.png)

 Install Python3
----------------
You can automate nearly everything with Python. From sending emails and filling out PDFs and CSVs  to interacting with external APIs and sending HTTP requests. Whatever your idea, it’s more than likely that you can pull it off using Python along with its modules and tools.

Tons of libraries created for Python make the language really powerful, allowing developers to tackle everything from machine learning and web scraping to managing your computer’s operating system.

```
brew install python3
```
Also with the install of python3, pip should have been installed, to make sure run this in terminal
```
pip3 --version
```
Now we will install a package called pipenv
-------------------------------------------
Run this in terminal: 
```
pip3 install pipenv
```
Install Node JS  
------------------------------------------
[Node.js](https://bootcamp.berkeley.edu/resources/coding/learn-node-js/introduction-to-node-js/) is an open-source, cross-platform, dynamic JavaScript runtime environment. As a runtime environment, Node.js has the software and hardware infrastructure necessary to execute a program in real-time. This functionality makes it an invaluable tool for those who want to write back end (server-side) programs in JavaScript.
```
brew install node
```
Now that we have installed node, we can use npm an online repository for the publishing of open-source Node.js projects; second, it is a command-line utility for interacting with said repository that aids in package installation, version management, and dependency management.

Install Serverless
-----------------------------
Serverless computing (or serverless for short), is an execution model where the cloud provider (AWS, Azure, or Google Cloud) is responsible for executing a piece of code by dynamically allocating the resources. And only charging for the amount of resources used to run the code. The code is typically run inside stateless containers that can be triggered by a variety of events including http requests, database events, queuing services, monitoring alerts, file uploads, scheduled events (cron jobs), etc. The code that is sent to the cloud provider for execution is usually in the form of a function. Serverless is sometimes referred to as “Functions as a Service” or _“_FaaS_”_.
```
npm install -g serverless
```
Install awscli
--------------
The AWS Command Line Interface (CLI) is a unified tool to manage your AWS services. With just one tool to download and configure, you can control multiple AWS services from the command line and automate them through scripts.

We can achieve more speed and customization through AWS CLI than the AWS management console. It improves the convenience and productivity of DevOps engineers and developers.
```
brew install awscli
```
Install GIT
-----------
**Git** is a version control system that you download onto your computer. It is essential that you use Git if you want to collaborate with other developers on a coding project or work on your own project.

In order to check if you already have Git installed on your computer you can type the command `git --version` in the terminal.

If you already have Git installed then you will see what version you have. If you don’t have Git installed you can visit the [Git website](https://git-scm.com/) and easily follow the download instructions to install the correct version for your operating system. Are run this in terminal.
```
brew install git
```
Install SSH
-----------
The SSH, Secure Shell, is a remote management protocol through which users can both modify and control their remote servers on the Internet. SSH makes use of the most innovative cryptography techniques with the clear objective that all communications made between users and remote servers are secure. It has a tool that allows the remote user to authenticate to exit later back to the users.  
 Ssh-keygen is a tool for creating new authentication key pairs for SSH. Such key pairs are used for automating logins, single sign-on, and for authenticating hosts.  
 The simplest way to generate a key pair is to run

 ssh-keygen

without arguments. In this case, it will prompt for the file in which to store keys.

You will see the following text:
```
Generating public/private rsa key pair.
    Enter file in which to save the key (/home/username/.ssh/id_rsa):

Press enter to save your keys to the default `/home/username/.ssh` directory.

Then you'll be prompted to enter a password:

    Enter passphrase (empty for no passphrase):
     Your identification has been saved in /home/username/.ssh/id_rsa.
    Your public key has been saved in /home/username/.ssh/id_rsa.pub.
    The key fingerprint is:
    SHA256:/qRoWhRcIBTw0D4KpTUyK6YepyL6RQ2CQrtWsaicCb4 username@871e129f767b
    The key's randomart image is:
    +---[RSA 2048]----+
    | .o=+....        |
    |+.*o+o .         |
    |+X.=o o          |
    |@.=.oo .         |
    |=O ...o S        |
    |o.oo . .         |
    |.E+ . . . .      |
    |oo . ... +       |
    |=.. .o. . .      |
    +----[SHA256]-----+

```
You now have a public and private SSH key pair you can use to access remote servers and to handle authentication for command line programs like Git.

 
