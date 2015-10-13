# Note: This project has been moved to [https://github.com/honeynet/apkinspector/ on GitHub](https://github.com/honeynet/apkinspector/). #

## Introduction ##
The goal of this project is to aide analysts and reverse engineers to visualize compiled Android packages and their corresponding DEX code.
APKInspector provides both analysis functions and graphic features for the users to gain deep insight into the malicious apps:

  * CFG

  * Call Graph

  * Static Instrumentation

  * Permission Analysis

  * Dalvik codes

  * Smali codes

  * Java codes

  * APK Information


## Deploy APkInspector on your computer ##
This is a guide to get APKInspector running on your own computer. The latest version is tested on Ubuntu 10.10 and Ubuntu 11.04.
  1. Download the latest version of APKInspector via GIT
  1. Run “./Install.sh”
  1. Test if APKInspector can boot correctly, go to the directory of “APKInspector”, run “python StartQT.py”.


## What’s new? ##
UI Improvement:
  * Automatically installation
  * Fine-grained Graph View to Source View
  * Call Graph
  * Navigation
  * Better display of Control Flow Graph
New Analysis Features:
  * Reverse the Code with Ded for Java Analysis
  * Static Instrumentation
  * Combine Permission Analysis

## Related Projects ##
Some modules of APKinspector on based on Androguard http://code.google.com/p/androguard/.

DED
http://siis.cse.psu.edu/ded/