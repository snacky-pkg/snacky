# Snacky ![Snacky](https://github.com/snacky-pkg/snacky/blob/main/icon.png?raw=true)

# Introduction 

Snacky is a free and open source package manager.

# Installation

There are 2 versions of Snacky, the CLI and the GUI verion, think the GUI version more as a App Store replacment.
To install the GUI version, go to Releases and find download the latest .pkg file. Install it, and your done!

To install the CLI version, go to this [repo.](https://github.com/snacky-pkg/snackycli/)
Go to Releases, and then download the snackycli.zip file. There will be a install.sh script.
Run the script in a terminal of your choice, Note that for the CLI version you will need sudo rights.

# How can i upload packages?

Create an account at https://snacky.rf.gd, this is the official website.
Upload your install.sh and your install.py scripts, NOT THE WHOLE PACKAGE!
In the install.sh script, this is what is needed.
1. GitHub repo info, this should be commented.
2. The download URL, upload the package to GitHub, and copy the releases download url FOR THE ZIP FILE! example: https://github.com/username/repo/releases/download/version/package.zip
3. A command to run install.py, example: python3 install.py

In the install.py script, this is what you need.
1. A command to run Snacky. Use snacky.
2. A command to run the continue install. Use snackycontinue-pkg. Replace pkg with your packges name.

## For it to come up in the GUI, request a verfication at: verifpkg.snacky.rf.gd.Make sure you are logged in.
