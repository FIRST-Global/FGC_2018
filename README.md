## Welcome!
This GitHub repository contains the source code that is used to build an Android app to control a *FIRST* Global competition robot.  To use this SDK, download/clone the entire project to your local computer.

If you are new to the *FIRST* Global software and control system, you should read the setup guide to learn how to install, configure, and use the software and control system:

https://first.global/fgc/robot-kit/

## Downloading the Project
It is important to note that this repository is large and can take a long time and use a lot of space to download. If you would like to save time and space, there are some options that you can choose to download only the most current version of the Android project folder:

* If you are a git user, *FIRST* Global recommends that you use the `--depth` command line argument to only clone the most current version of the repository:

```console
git clone --depth=1 https://github.com/FIRST-Global/FGC_2018.git
```

* Or, if you prefer, you can use the "Download Zip" button available through the main repository page.  Downloading the project as a .ZIP file will keep the size of the download manageable.

* You can also download the project folder (as a .zip or .tar.gz archive file) from the Downloads subsection of the Releases page for this repository.

Once you have downloaded and uncompressed (if needed) your folder, you can use Android Studio to import the folder  ("Import project (Eclipse ADT, Gradle, etc.)").  See the setup guide for more information.

## Getting Help
### User Documentation and Tutorials
*FIRST* Global maintains a selection of PDF guides with information and tutorials on how to use the *FIRST* Global software and robot control system.  You can access these documents at the following address:

https://first.global/fgc/robot-kit/

### Javadoc Reference Material
Documentation for the FGC SDK is included with this repository.  There is a subfolder called "doc" which contains several subfolders:

 * The folder "apk" contains the .apk files for the FGC Driver Station and FGC Robot Controller apps.
 * The folder "javadoc" contains the JavaDoc user documentation for the FGC SDK.  Double clicking the `index.html` file will open the JavaDoc in your web browser.
