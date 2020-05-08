---
title: Retro - Login Template
subtitle: Clean 100% Customisable Login Template
date: 2020-05-08T20:35:10.204Z
thumb_img_path: /images/retro-login-template-frontal-image.png
content_img_path: ""
layout: project
---
![Retro- Login Template Header Image](/images/4-screen-app-preview-retro-1.png)

Meet **Retro**, the fully customisable login template. 

# Template Features

This template is ready to go out of the box, just input your Firebase credentials, which if you aren't familiar with doing, you can check out our [Absolute Beginners Guide to Firebase Authentication with Thunkable X](/posts/authentication/).

What is unique about this template is that everything you see (excluding the "your logo here" image) was created entirely inside of Thunkable. This means you can change just about anything in this template. 

The app contains [alerts](https://docs.thunkable.com/alert) that appear for:

* Incorrect username or password
* User already exists
* Any other error (may contain a long error code)
* Confirming that a password reset link has been sent

The users credentials are stored in the app, so they do not have to enter a password every time they sign in. An app variable called **authUserID** will get the users Firebase Authentication ID and store it as an app variable. This makes it easy for storing and retrieving user-specific data from an external data source, such as the users name, bio or profile picture.

![4 Screen Preview - Retro Login Template](/images/4-screen-app-preview-retro-1.png)

<div style="display: flex; justify-content: center;">

<p class="block-cta">
<a href="https://x.thunkable.com/projects/5ea215cc6d1fee15b0d68df1/1f44e23c-52d6-4205-993f-c4b84d9b99fc/designer" target="_blank" class="button">Remix Template</a>
</p>

</div>

Make sure to click **remix** when the project opens up.

![Click to Remix Example](/images/click-to-remix-example.png)

# Template Documentation

### Changing Stripe Properties:

These stripes are visible on the **Login** and **Sign Up** screens.

![](/images/stripes-design-view-preview.png)

The stripes are rotated at:

* \-6 radians in **Sign Up** screen
* 6 radians in **Login** screen

``

```
| Formula | 6Rad × 180/π = 343.775Deg
```

You can change this up using *Transform rotate* in the advanced properties tab.

![](/images/stripes-design-view-adding-the-6-rad.png)

![](/images/stripe-rotate-properties.png)

Changing the colour is a piece of cake. Click on the stripe you want to alter and chose a colour from the colour picker.

![](/images/change-stripe-colour-preview.png)

All the stripes are named accordingly for ease of customisation:

* Stripe 1
* Stripe 2
* Stripe 3
* Stripe 4

**And**

* Stripe-1
* Stripe-2
* Stripe-3
* Stripe-4

### Changing The Loading Animation:

The loading animation can be found [here](https://lottiefiles.com/21462-loader-jumps). 

You can use [LottieFiles](https://lottiefiles.com)' easy to use colour editor to change the colours to work with your own theme.

![](/images/lottiefiles-edit-layers-preview.png)

### Change The Home Screen:

![](/images/testing-home-screen-preview.png)

This screen is useful for testing purposes, as it has a temporary sign out button so you can perform tests with your brand new template. You can rename the home screen and delete all data inside of it, but **do not delete the home screen**. This will cause errors that can be frustrating if you are not experienced with Thunkable.

### If you encounter any problems or issues drop a comment below.