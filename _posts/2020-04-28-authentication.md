---
title: Firebase Authentication
subtitle: A Beginners Guide To Setting up Firebase Authentication
date: 2020-04-28T21:47:23.557Z
thumb_img_path: /images/firebase-auth-absolute-beginners-set-up-guide.png
excerpt: Part 1 - Setting Up Firebase Authentication
layout: post
---
So you've picked one of our beautiful templates. Now you're ready to make it work!

If you know how to set up Firebase with Thunkable, skip to **[Part 2](/posts/authentication-part-2)**.

# Part 1 - Setup

## Step 1:

Assuming you've chosen [one of our templates](/portfolio), open up the template. This will only take a minute. This is good practice when using our templates so you know what you're dealing with.

Here you're going to see 5 screens at the top of the designer tab:

* Loading
* Sign Up
* Sign In
* Forgot Password
* Home

*Don't worry if there are extra screens, just make sure the five screens above are there and in the order shown below.*

![Step 1](/images/step-1.png)

[Open image in tab.](/images/step-1.png)

Make sure the loading screen is at the top of the component list, which is located on the left of your design view. This is shown in the image above with the blue arrow. **Once we can confirm all our screens are there we will begin the next step.**

## Setting Up Firebase

###### If you already know how to set up and link your Firebase project, skip to [Part 2](/posts/authentication-part-2).

Okay now we're going to start getting into it. Don't worry, it's not going to be difficult. There will be no fancy words or skipping steps. We will cover every bit of this. That way if you know a step you can skip it, and if you don't understand it, you soon will!

## Step 2:

First things first we're going to head over to [Firebase](https://firebase.google.com). Click **Go to console**.

![Step 2](/images/step-2.png)

[Open image in tab.](/images/step-2.png)

## Step 3:

You will be greeted by a sign in screen. If you aren't, then you're already signed in! Go ahead and sign in with your Google Account.

![Step 3](/images/step-3.png)

[Open image in tab.](/images/step-3.png)

## Step 4:

Once we're signed in we will be greeted with our Firebase Dashboard. Go ahead and click **Create a project**.

![Step 4](/images/step-4.png)

[Open image in tab.](/images/step-4.png)

## Step 5:

Name your project something. It's best to name your project the same as your Thunkable app. This will come in handy when you have lots of projects. Click **Continue** to proceed.

![Step 5](/images/step-5.png)

[Open image in tab.](/images/step-5.png)

## Step 6:

Firebase has many useful data analytic features. This is completely optional. This will not affect your Firebase project performance or cost (in case you're wondering, the project is free!). If the box is already ticked here you can leave it be and click **Continue**.

![Step 6](/images/step-6.png)

[Open image in tab.](/images/step-6.png)

## Step 7:

Set your region according to your location. Tick the boxes and click **Continue**.

![Step 7](/images/step-7.png)

[Open image in tab.](/images/step-7.png)

## Step 8:

All set! Well kind of. You've successfully created your own Firebase project. Pretty cool huh? Go ahead and click **Continue** and proceed to the next step.

![Step 8](/images/step-8.png)

[Open image in tab.](/images/step-8.png)

## Step 9:

Now things start to get interesting. It may seem over the top to have 8 steps just to get to this screen, but once you've done it, next time you can skip past this section! We promised we'd cover everything here.

On the left of your screen now you will see a navigation menu. If you don't see it click the ☰ at the top left of the screen. We want to select **Authentication**.

![Step 9](/images/step-9.png)

[View image in tab.](/images/step-9.png)

## Step 10:

Now we want to select **Set up sign-in method**.

![Step 10](/images/step-10.png)

[View image in tab.](/images/step-10.png)

## Step 11:

Here we are going to click on the **Email/Password** option.

![Step 11](/images/step-11.png)

[View image in tab.](/images/step-11.png)

## Step 12:

This will expand the **Email/Password** option. From here we want to toggle the top **Enable** switch. The enable switch to the right of "*Email link (passwordless sign-in)*"is not a feature currently supported in any of our templates so we want to leave this disabled.

![Step 12](/images/step-12.png)

[View image in tab.](/images/step-12.png)

## Step 13:

We're almost done with setting up Firebase. Click **Save** to complete this setting. Now your project supports email and password sign in. Next step is to connect it with your Thunkable app.

![Step 13](/images/step-13.png)

[View image in tab.](/images/step-13.png)

## Step 14:

In the navigation menu on the left of your Firebase Console,at the top you will see a settings icon. We're going to click on it.

![Step 14](/images/step-14.png)

[View image in tab.](/images/step-14.png)

After we click on it we will get a small menu with 3 options. Choose **Project settings**.

![Step 14.2](/images/step-14.2.png)

[View image in tab.](/images/step-14.2.png)

## Step 15:

We now have access to our **API Key**. We need this piece of information along with our **Database URL**. 

**Do not share your API Key with anybody.**

Take note of the string of text circled in red. Your Web API Key will be different to this, so don't use the one in the image. If you do your project simply won't work.

![Step 15](/images/step-15.png)

[View image in tab.](/images/step-15.png)

## Step 16:

Next we are going to copy down our **Database URL**. This is the second of the two pieces of information that we require to make our sign in app work. From the navigation menu on the left of your screen, select **Database**.

![Step 16](/images/step-16.png)

[View image in tab.](/images/step-16.png)

## Step 17:

Once the Database page loads, scroll down until you see the option **Realtime Database**. Under this option click **Create Database**. 

The reason we create a database is so we can use it for other features such as storing users information. It is also how we can retrieve the **Database URL**.

![Step 17](/images/step-17.png)

[View image in tab.](/images/step-17.png)

## Step 18:

These are your security rules. We will select **Start in locked mode** because we will not be using the Realtime Database as of this tutorial. This can be easily changed when you decide to use it.

Click **Enable**.

![Step 18](/images/step-18.png)

[View image in tab.](/images/step-18.png)

## Step 19:

Now we can view our **Database URL**. Make a copy of this. This is the last step on the Firebase Console for now.

![Step 19](/images/step-19.png)

[View image in tab.](/images/step-19.png)

## Step 20:

**Back to Thunkable!** Go back to your project on [x.thunkable.com](https://x.thunkable.com). **Click on your project name**, which should appear on the top left of the design view. 

![Step 20](/images/step-20.png)

[View image in tab.](/images/step-20.png)

## Step 21:

On the right hand side of your screen the properties tab will have changed to app properties. Scroll down until you find **Firebase Settings**. Enter your **Web API** key that we got from step 15, and your **Database URL** from step 19 in their appropriate places, as shown below.

![Step 21](/images/step-21.png)

[View image in tab.](/images/step-21.png)

# And that's it!

Well done on completing this tutorial. It can get tough following a guide, so fair play for sticking out 21 steps of Firebase! 

When you're ready to start adding the blocks to your template, you can check out **[Part 2](/posts/authentication-part-2)**.