
# GravatarHelper.AspNetMVC
Gravatars are world-renowned avatar images that follow you to where you post, blog or from your apps. GravatarHelper.AspNetMVC.lib is a library class that allows you to generate your image using HTML Help.

# Installation
## step 1 :
Let's start by installing the library  via nuget :
```
Install-Package GravatarHelper.AspNetMVC.lib
```
 Or search for "GravatarHelper.AspNetMVC.lib" in the Nuget package window
## step 2 :
do not forget to add in your web.config for the view folder this line:
```
<add namespace="GravatarHelper.AspNetMVC.lib" />
```
## step 3 :
congratulation now, you can used esay for any razor page for exemple : 
```
@Html.GravatarImage("ahmedoumezzine@outlook.fr","img")
```
