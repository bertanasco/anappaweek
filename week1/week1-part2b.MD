
#What we'll do#

Discuss the project structure of an **android studio** project and provide an overview of of the files and folders in the project

#Android Project Structure#

If you think about it, physics somehow define the conventions and structure of the world we live in. If we aren't constrained by its laws we can make a horse slide like the one below

![](https://i.imgur.com/rKpxPh.jpg)

<sup>courtesy of imgur and OP<sup>

Or use a gun a la Quake 3 rocket launcher!

![](http://i.imgur.com/PhrgLL0.gif)

<sup>courtesy of imgur and OP<sup>

or do this sick  move

![](http://i.imgur.com/dchnNNP.gif)

such fun!

and uhmm  I wish I can think of something creative to tell you how these bollywood gifs are related to the android project structure. The god's of writting decided that I leave it up to you and that I should proceed to the our main topic.


So to start, Let's use  **Project view** to check the files and folder.

![](http://i.imgur.com/Zk4l7H3.png)

#app folder#

The most important folder that we should inspect is the **app** folder. This folder contains all your project resources, java files , build files etc. 

##/app/build##

All the stuff that gets created during the build is located here. 

![](http://i.imgur.com/fOlb0jp.png)
<sup>Android's build process taken from the developer site<sup>


Head over to android developer's [site](https://developer.android.com/sdk/installing/studio-build.html) to further read about the build process.

###.gradle folder###
![](http://i.imgur.com/XBQsd5o.png)

this is just [gradle's](https://gradle.org/) cache information. It get's created every time you create/build a project.


###.idea folder###

![](http://i.imgur.com/xglRcwP.png)

Contain's your project settings.
Copy paste from jetbrain's wiki:

	The .idea directory contains a set of configuration files (.xml). 
	Each file contains only a portion of configuration data pertaining to a certain functional area which is reflected in the name of a file, for example, compiler.xml, encodings.xml, modules.xml.

Source: [https://www.jetbrains.com/idea/help/project.html](https://www.jetbrains.com/idea/help/project.html)









