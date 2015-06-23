# **What we will do**
  This is a two part tutorial where we would create a "Hello Doge" App.   A basic android app that would display a shiba inu image. You can go to http://dogr.io/  to generate an image.
 
 ![](http://i.imgur.com/ALS9Kqj.jpg)

# **Requirements**
  This tutorial assumes that you already have the following installed
  
   1. [JDK 1.7](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
   2. [Android Studio](http://developer.android.com/sdk/index.html)
   3. [Android SDK](http://developer.android.com/sdk/installing/index.html)

# **Create a new project**
1. Open up **Android Studio** and **start a new project** by     selecting  **Start a new Android Studio project**

  ![](http://i.imgur.com/CgO792g.png)

  If you're in **Android Studio** , choose **File** &gt; **Create      Project**

2. This would take you to the new project Wizard. 
  The first page allows you to enter the following :
 
  **Application Name** : The name we wish to give our hello world      application. We will set this to "week1" in this example

  **Company Domain** : Used as a qualifier in the package name. I'll   use the domain name of this blog.

  **Package Name** : By default the value of the package name is the   reverse company domain + the **Application Name**. You may change    this by clicking the tiny edit button ![edit button.](http://i.imgur.com/m0VR1Ke.png)
  We will use the default value in this tutorial


  ![](http://i.imgur.com/7WS46iB.png?1)

  Click next to proceed.

3. The second page would allow you to select the platform where you wish to deploy your application.Just leave the default values and hit next

  ![Imgur](http://i.imgur.com/6AXqaIP.png)
  
4. The next page allows you to add an **Activity**. Select **Blank Activity**. 

  ![](http://i.imgur.com/OkLae2l.png)
  
  
  ![](http://i.imgur.com/iuiZ1yU.png?2)
  
  Okay okay, so what is an **Activity**? Think of it like a web page, or a canvass or a piece of paper  . It's a component where you could add bits and pieces of other components that  someone can interact with. So when you select **Blank Activity** imagine that you are given a blank piece of paper where you get to draw all your anime stuff! fun!.
  ![](http://i.imgur.com/UfhVHoV.png)
  
  More detailed explanation about activities here : [Android developer site](http://developer.android.com/guide/components/activities.html)

5. Clicking next would take you  to another wizard page where you can provide additional details to the Activity
  
  **Activity Name** : This would be the name of the java class for   
  the activity
  
  **Layout Name** : The base name of the xml file that contains the 
  layout of the Activity. Think of it as something similar to css

  **Title** : insert captain obvious meme here
 
  ![](http://i.imgur.com/7vvjzya.png)
 
 Click finish
 

# **Set-up Emulator**

 1. After creating the project, you would see something similar to 
    the screenshot below.
    ![](http://i.imgur.com/mZb7HZb.png)
 2. Clicking the AVD Manager button ![] (http://i.imgur.com/C4Jiktl.png)
    ![](http://i.imgur.com/QUDSw7h.png?1)
    
     would take us to the AVD Manager! wow! such fun! LOL
    ![](http://i.imgur.com/fYPG0si.png)
     
    Click **Create a virtual device**     
    ![](http://i.imgur.com/XFsvH0X.png) 
    to Start creating the new device 
  
 3. In the device definition we would select **Nexus 5**.
    ![](http://i.imgur.com/MoMyFyE.png)
    
 4. Select **Lollipop** whose **API Level** is 21. Click **Next**
    ![](http://i.imgur.com/hJjBznm.png)
 
 5. Hit Finish after this screen
    ![](http://i.imgur.com/XMFp2Fm.png)
    You would now have a device in AVD Manager. Click ![](http://i.imgur.com/pNfRUoR.png) to start the device
    ![](http://i.imgur.com/9WTkKtA.png)
 
 6. Once you have the device running you would see something similar 
    to the image below
    ![](http://i.imgur.com/Wd4v8HL.png)
    

# **Running the initial app**
  
1. The project you created contains a **TextView** in the layout by     default. See **activity_main.xml**
    ![](http://i.imgur.com/ZiVCVjP.png)

2. Now that you have the device running you could actually test this     app by clicking ![](http://i.imgur.com/pNfRUoR.png) or hitting ^R      
3. You will be prompted to select the device where you would run       the app. Select the device you created and hit **OK**
  
  ![](http://i.imgur.com/yDK5knr.png)
  
4. Tadaaa 
    
  ![](http://i.imgur.com/YGwciud.png)

  

## Coming up Next 
 1. [Navigating Android Studio](http://bertanasco.com/post/121426387185/week-1-mandatory-hello-world-part-2-a)
 2. Discuss the contents of a project
 3. Add the Doge image in the App 


![](http://i.imgur.com/fhjMuNc.png)