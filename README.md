XCodeSystemFrameworkLinker for Unity3d
=======================================================

Automatically link system libraries with '''Optional" or "Required" 
option every time developer export XCode project from Unity using 
PostprocessBuildPlayer.

This enable you to link necessary libraries like 'StoreKit.Framework',
'MessageUI.Framework'. Here is the list of framework by default.


## Link with 'Required' option
  - StoreKit  
  - Security  
  - CoreText  
  - MessageUI 


## Link with 'Optional' option
  - Twitter 
  - Social 
  - Accounts  
  - AdSupport

## Installation

### 1. Install 'xcodeproj' using gems

Install 'xcodeproj' from [the page of rubygems](http://rubygems.org/gems/xcodeproj).

    The version of 'xcodeproj' must be under '4.0'.

### 2. Put 'PostprocessBuildPlayer' inside your Unity3d project.

Put 'PostprocessBuildPlayer' pulled from this repository under 'Assets/Edit'.

    NOTE :
    Since this script is using Unity3d's Build Player Pipeline feature and the feature works 
    for only the file named 'PostprocessBuildPlayer', you must not rename this.
