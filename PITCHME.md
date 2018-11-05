---?image=https://github.com/clementblanco/mobile-application-design-intro/blob/master/cover.png&size=100% auto

---

## Introduction

---

**Good news, don’t forget what you know already.**

See this as a new set of skills and build on this...

---?image=https://i.imgflip.com/p8blw.jpg&size=auto auto

--- 

Similar to web design, it’s wide and dense, like huge but interesting.

But it's still designing so you’ll still need inspiration as well as all of your best skills especially for UX and UI.

---

**(Try to) Be interested and curious**

It’s okay to be new on something as long as you try to understand it and do your best even though
if it could be quite overwhelming at first when digging into it, as it's kind of its own world.

You could feel like...

---

![](https://img.memecdn.com/i-have-no-idea_o_1043684.jpg)

But it's okay.

---

**My personal first experiences...**

Using Appcelerator Titanium...

- [COBAN Atlantique dans l’App Store](https://itunes.apple.com/fr/app/coban-atlantique/id653538938?mt=8)
- [COBAN Atlantique - Android Apps on Google Play](https://play.google.com/store/apps/details?id=com.seppa.coban&hl=en)
- [Guide de Mérignac dans l’App Store](https://itunes.apple.com/fr/app/guide-de-m%C3%A9rignac/id620600674?mt=8)

---

And a print designer... 🤦‍

- [my Selecta on the App Store](https://itunes.apple.com/gb/app/my-selecta/id727157602?mt=8)
- [my Selecta - Android Apps on Google Play](https://play.google.com/store/apps/details?id=com.selecta.myselecta&hl=en)

---?image=http://s2.quickmeme.com/img/f5/f5be8ad0e3d180f614afb5255793fab60b2b9d7cdaf450ab1356dd9956e29b99.jpg&size=auto auto

---

## Different ways (and technologies) to build mobile applications

---

**iOS Native Development**

Objective-C or Swift language + iOS SDK + XCode as IDE + CocoaPods as Dependancy Manager
    
---

**Android Native Development**

Java language + Android SDK + Android Studio as IDE + Gradle as Dependancy Manager
    
---

Those two can't be any closer from the OS + native SDK

---

**Hybrid Development**

- React Native (Javascript)
- Appcelerator Titanium (Javascript)
- Xamarin (C# + Microsoft .Net platform)

---

- performances: very close from native 👍
- can access most of the device capabilities
- target both iOS and Android (and sometimes Windows Phones too)
- re-usable codebase
- more accessible languages
- but with some limitations

--- 

**Web App Development** AKA "App Shelling"

- PhoneGap (Cordova)
- SenchaTouch
- Ion

Encapsulate a website (including RWD or not) into a mobile applciation.

---

- performances are 💩
- depending on HTML/CSS/Javascript
- can't access all device capabilities

--- 

**But no matter what, it's all going to the same place**

- Apple App Store
- Android Play Store

^ Good news for designers. ❤️

---

- Same distribution
- Same platform constraints
- Same challanges

---

## Considerations

---

**Good news, don’t forget what you know**

- UI Design Skills
- UX Design Skills
- Wireframing Skills
- Same tools...

---

**But wait, what are you building this for?**

Another good news: the same things! 🎉 

---

**A Machine and a User**

True ❤️ story.

---

### A machine

Some technical considerations from a Designer POV

---

**Websites**

Any **Browser** which is going to run the website using one or multiple **Resolutions** (RWD or not),

---

**Mobile Applications**

- Device (hardware)
- Operating System
- Connectivity

---

**Device - Resolution(s)**

- Standards for iOS based on original 320x480
- Different resolutions **4** based on screen sizes (5.5” | 4.7” | 4” | 3.5”)
- Android uses standards like HVGA, WVGA800 or WVGA854

---

**What resolution(s) should we use for our designs?**

Discussion...

---

### A user

---

**User Input is different from a website**

- Multiple touch gestures:
    - **tap** (not click) + position
    - **double tap** + position
    - **swipe** + direction + position
    - **pinch** + direction
    - **drag** + direction

---

![](https://cdn-images-1.medium.com/max/1600/1*aA7h4IzDUyrmuDHu-wFOQw.gif)

---

- Typing on a small keyboard (slower text typing)
    - ↝ ask for the very minimum
    - ↝ ask for relevant things
- Learn the terminology:
    - Page = Screen
    - Click = Tap/Touch
    - App Icon
    - Splash Screens…

---

## Wireframes

- Good to start on paper but needs to be digital at some point
- Like a website, prep work is mandatory...

---

**Apply the same concepts from a website**
    
- Brand guidelines
- Business Requirements
- Client Requirements
- ~~Site map~~ → Flow map (or Flow chart, App flow, Storyboard) **important**
- User Interface and Interactions (should be illustrated if needed)

---

**Example of a Flow map**

![](http://www.davidgauch.com/img/portfolio/20_hellofutureself/hfs_mobile_app_flow.jpg)

---

**Application Definition Statement**
        
- What the application experience is
- What is the application meant to do
- Who is the intended audience

---

**Feedback, touch gestures and transitions**

Always feedback to the user

↝ confirm correct behaviour + satisfaction + avoid confusion

---

**Visual Feedback at least**

- touch states
- animation upon completion of action
- communicate with literals upon completion of action

(audio or vibration feedback can be used too)

---

User interaction is different from a website (multiple touch gestures...)

Always keep in mind the context (connectivity) and limitations from a user POV

Don't forget transitions between screen and animations.

---

## UI Design

---

**Most of Design Principles still apply**

- User centric
- Less is more
- Actions are keys
- Be consistent
- and many more I’m sure…

---

Sketch is a must (vector is ❤️) proper UI design tool

---

Resolutions and densities

Responsiveness of a mobile application

---

**Design Guidelines**

- Apple Human Interface Guidelines
- Google Material Design Guidelines

or other (Windows Phones)

---

**Know the UI Elements/Components**

Buttons, TableView/ListView, ScrollableView, ScrollView, ImageView, View, Slider, Dialog, Picker, Window, Inputs...

---?image=https://i.pinimg.com/736x/83/b4/a9/83b4a9840373239ad291a58a0c50f013--view-controller-ios-.jpg&size=auto 90%

---

**Know how iOS / Android handle differences**

---

**Units, Layout, Positioning and View Hierarchy**

Units for Absolute values:

- Default iOS: dip
- Default Android: pixels 
- Possibilities: px, mm, cm, in, dp/dip, or system
- dp/dip is recommended

---

**DP/DIP/DPI DAFUQ?**

DPI (Dots Per Inch) = **Physical measure**
DIP (Density Independent Pixels) = **Abstract measure**

---

DIP is also known as:

- Points
- DP (Digital Points)
- PPI (points per inch)

Don't ask. ¯\\(ツ)/¯

---

- Android: actual pixels = dip * (screen density) / 160
- iOS: actual pixels = dip * (screen density) / 163

Effectively **1dip = 1px** on standard and **1dip = 2px** on retina display for iOS.

---

Practically, people tend to design in 1x on Sketch.

For pictures (not vector), use high res assets.

See resources linked.

---

Don't get confused between DIP and DPI (dots per inch).

DPI is used for screen sizes (LDPI, MDPI, HDPI, XHDPI, XXHDPI) which is like @1x, @2x, @3x

---

![](http://movify.be/wp-content/uploads/2016/10/iosandroid_proportion.jpg)

---

![](http://blog.fluidui.com/content/images/2015/09/resolution.png)

---

**iOS Export**

![](http://movify.be/wp-content/uploads/2016/10/ios_export.jpg)

---

**Android Export**

![](http://movify.be/wp-content/uploads/2016/10/android_export.jpg)

---

**Content**
        
- FILL behaviour
- SIZE behaviour
- Absolute values (based on selected unit)
- Percentages (based on parent)

---

**Positionning**

- top, right, bottom, left anchors
- value (percentage or absolute)

---

**Image formats**

- GIF, PNG, JPG supported but JPG for pics and PNG preferred for anything else.
- No SVG supported.
- Image sizes are really important and Developers should be able to tell you for some very specific assets what is the **exact** resolution expected. Hard requirement in some cases.
- Overview of Android 9 patch technique.
- 2 ways of doing splash screens

---

**Navigation** and **Forms** are one of the most challenging things to do

---

- Navigation
    - Windows
    - Explanations around patterns
        - 1 High level (with multiple options)
        - Many sub levels
        - Avoid to jump from the middle of a navigation branch to somewhere on another branch
        - Keep consistency into accessing functionalities on the same branch of the navigation

---

- Forms
    - Elements
    - Feedback
    - Textarea example
    - Checkbox example
    - Date picker example

---

Use symbols to avoid having to repeat yourself, especially for UI elements

---

Try to build your own library (or modify an existing one to match the project) but having standards and avoid repetition is key. Similar to what we do for websites with [Styleguide | Cyber-Duck](http://patterns.cyberduck.net/)

---

- Typography
- Buttons
- Form elements
- Screen layouts (templates)
- Screen elements
- and many more…

---

Don’t forget empty states.

Don’t forget transitions, make it live and FUN (but not too much). Evil is in the detials.

---?image=https://raw.githubusercontent.com/Sunnyyoung/SYFavoriteButton/master/ScreenShot/ScreenShot.gif&size=auto 90%

---

![](https://www.sketchappsources.com/resources/source-image/books-app-travishowell.gif)

---

Push notification wizard example

Even small things can benefit this.

---

**Always test your UI**

- Using Sketch? (@cristina)
- Things should be touchable
- Put yourself in your user's shoes
- Best way to make sure interaction and UX is good enough

---

**Deliverables**

- Wireframes
- Designs
- UI Kit (standardised and re-usable components)
- Testable UI (optional but UI testing while designing is still **mandatory**)

---

## Don’t reinvent the wheel

---

Past: Photoshop + Smart Object

---

- Now Sketch Files/Libraries + Symbols
- Tools (App Icons, Splash screens…)
- Libraries (UI Libraries for example)

---

- [App Icon Templates](https://savvyapps.com/blog/sketch-ios-app-icon-template)
- [App Icon Sketch Files](https://www.sketchappsources.com/free-source/2183-ios-android-app-icon-generator-sketch-freebie-resource.html)
- Splash Screens Sketch Files...
- sketchappsources.com + Google 

---

Discussions about Git [https://github.com/jtholloran/icons](https://github.com/jtholloran/icons)

---

## Designers and Developers should talk a lot.

As always.

---

Gather technical requirements from Developers.

Make sure you book recurrent times to review things.

Thing are coming as requirements from the technology used.

---

- For a functionality
- For the UI
- For connectivity

---

- For feeding back the user on errors
    - While filling a form or performing an action
    - While simply navigating and using the application
- What units to talk with?
- What densities do you need?

---

Make sure to have a lot of checkpoints with your Developers to approve what has been produced (wireframes, designs, functionalities…)

---

In sum, apply the same things you would apply for a website in terms of workflow, checkpoints and processes.

But maybe not only...

---

## Stay curious

- How to organise Sketch file(s) for Mobile Application Design?
- What are the best practices with Sketch for Mobile Application Design?
- What should be our processes in terms of Mobile Application Design?
- How to do wireframing efficiently for Mobile Application Design?
- What processes to create/adjust internally?
- and many more...

---

## Resources

---

- [Principles of Mobile App Design: Introduction](https://www.thinkwithgoogle.com/marketing-resources/experience-design/principles-of-mobile-app-design-introduction/)
- [Dribbble - 4_2x.png by Jerry](https://dribbble.com/shots/3835770-Dogdom/attachments/868382)
- [UI Design Do’s and Don’ts - Apple Developer](https://developer.apple.com/design/tips/)
- [Themes - Overview - iOS Human Interface Guidelines](https://developer.apple.com/ios/human-interface-guidelines/overview/themes/)

---

- [Show Me the Way to Go Anywhere – Navigation for Mobile Applications](https://www.interaction-design.org/literature/article/show-me-the-way-to-go-anywhere-navigation-for-mobile-applications)
- [Density Explanation](http://blog.fluidui.com/designing-for-mobile-101-pixels-points-and-resolutions/)
- [Pixel Density Demyistified](https://medium.com/@pnowelldesign/pixel-density-demystified-a4db63ba2922)
- [UI Sample](http://browse.sketchapp.tv/post/144553267835/collection-53-sketchapp-tv-uis)

---

- [Design at 1x it's a fact](https://medium.com/shyp-design/design-at-1x-its-a-fact-249c5b896536)
- [Designing at 1x](https://medium.com/sketch-app-sources/designing-at-1x-33240842180c)
- [Designing at 1x](http://movify.be/designing-at-1x/)
- [Eight don’ts for your Material Design app – Prototypr](https://blog.prototypr.io/common-material-design-bad-practices-to-avoid-b7995f251329)

---

- [Basic Patterns of Mobile Navigation](https://blogs.adobe.com/creativecloud/basic-patterns-of-mobile-navigation/)
- [Material Design](https://material.io/)
- [What Dimensions And Resolution Should Be For iOS And Android App Design?](https://think360studio.com/what-dimensions-resolution-should-be-for-ios-and-android-app-design/)
- [Appcelerator Platform - Appcelerator Docs](http://docs.appcelerator.com/platform/latest/#!/guide/Layouts,_Positioning,_and_the_View_Hierarchy)

---

![](http://i.memecaptain.com/gend_images/sMzG0g.jpg)
