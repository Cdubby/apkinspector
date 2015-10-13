# Note: This project has been moved to [https://github.com/honeynet/apkinspector on GitHub](https://github.com/honeynet/apkinspector). #

#summary How to use APKInspector to analysis apps

# Introduction #

APKInspector can provide you deep insight with the behavior of malicious apps.You can
get information about the structure of the app and find the security threats of those apps.


# Basic Usage #

  1. Run "python StartQT.py"
  1. Click "Setting" button to choose the analysis component you want.
  1. Click "New" button, choose the application you want to analysis.
  1. Select different pages to see CFG\Call Graph\Dalvik codes\Permissions etc.


# Features #

  * Press "Space" bar to jump between CFG view and Dalvik code view.
  * Use the "Navigation" button to jump between viewed classes
  * Edit the Smali code and compile it use "compile" button to set static instrument