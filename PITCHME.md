---?image=https://cdn-pro.dprcdn.net/files/acc_244709/IedzTc

---

# Introduction

---

**Good news, don’t forget what you know already.**
See this as a new set of skills and build on this...

--- 

**It's gonna be huge.**
Similar to web design, it’s wide and dense and you’ll still need inspiration and all of your best UX skills.

---

**Be interested and curious**
It’s okay to be new on something as long as you try to understand and do your best to be better.

---

***My personal first experiences...***

- [COBAN Atlantique dans l’App Store](https://itunes.apple.com/fr/app/coban-atlantique/id653538938?mt=8)
- [COBAN Atlantique - Android Apps on Google Play](https://play.google.com/store/apps/details?id=com.seppa.coban&hl=en)
- [Guide de Mérignac dans l’App Store](https://itunes.apple.com/fr/app/guide-de-m%C3%A9rignac/id620600674?mt=8)
- [my Selecta on the App Store](https://itunes.apple.com/gb/app/my-selecta/id727157602?mt=8)
- [my Selecta - Android Apps on Google Play](https://play.google.com/store/apps/details?id=com.selecta.myselecta&hl=en)

---

UGLY AF.

---

### Different ways and tech stacks to build mobile apps

- Native app
    - Tech stack
- Hybrid app
    - Tech stack
- Web app (app shelling) + RWD
    - Tech stack
- Some limitations based on which approach
- No matter what, it’s always distributed on the same platforms
    - -> same platform constraints
    - -> same way to distribute

---

### Considerations

---

#### Don’t forget what you know

- UI Design Skills
- UX Design Skills

---

#### What are you building this for?

Good news, we’re building this for the same things! 🎉 

---

#### A machine

---

**Technical considerations from a Designer POV**

- Websites:
    - Any **Browser** which is going to run the website using one or multiple **Resolutions** (RWD or not)
- Mobile Applications:
    - **Device** (hardware)
        - Resolution
            - iOS has standards based on original 320 x 480
                - Different resolutions **4** based on screen sizes (5.5” | 4.7” | 4” | 3.5”)
                - Recommended to use 
            - Android
                - Standards like HVGA, WVGA800 or WVGA854
                - Recommended to start with a Google Phone as a standard
            - **BUT** need to understand that an application still need to be responsive, no matter the resolution.
            - **ALSO** need to consider landscape
        - Density of the screen
            - -> Learn about @1x, @2x, @3x, ldpi, mdpi, hdpi, xhdpi, xxhdpi
            - -> Learn the units (check with developers too)
        - Device capabilities
    - **Operating System**
        - UI Guidelines
        - UX Expectations
    - **Connectivity**
        - Think about asynchronous and synchronous tasks
        - Think about bad connectivity (in a user journey or not)

---

#### A user

---

**User Input is different from a website**

- Multiple touch gestures:
    - **tap** (not click) + position
    - **double tap** + position
    - **swipe** + direction + position
    - **pinch** + direction
    - **drag** + direction
- Typing on a small keyboard (slower text typing)
    - -> ask for the very minimum
    - -> ask for relevant things
- Learn the terminology: Page = Screen, Click = Tap/Touch, App Icon, Splash Screens…

---

### Wireframes

- Good to start on paper but needs to be digital at some point
- Like a website, prep work is mandatory:
    - Apply the same concepts from a website
        - Brand guidelines
        - Business Requirements
        - Client Requirements
    - **Application Definition Statement**
        - What the application experience is
        - What is the application meant to do
        - Who is the intended audience
- UI and Interactions should be illustrated
- Feedback, touch gestures and transitions
    - Always feedback to the user: confirm correct behaviour + satisfaction + avoid confusion
        - Visual Feedback at least
            - touch states
            - animation upon completion of action
            - communicate with literals upon completion of action
        - Audio Feedback
        - Vibrating Feedback
    - User interaction is different from a website:
        - Multiple touch gestures: tap, swipe + direction, 
    - Transitions between screen + animations are important

---

### UI Design

---

- Most of Design Principles still apply
    - User centric
    - Less is more
    - Actions are keys
    - Be consistent
    - and many more I’m sure…
- Sketch is a go to (vector is ❤️) proper UI design tool
- Resolutions and densities
- Responsiveness of a mobile application
- Design Guidelines
    - Know the UI Elements/Components
        - Buttons
        - TableView/ListView
        - ScrollableView
        - ScrollView
        - ImageView
        - View
        - Slider
        - Dialog
        - Picker
        - Window
        - Inputs
    - Know how iOS / Android handle differences
- Units, Layout, Positioning and View Hierarchy (for Appcelerator)
    - **Units for Absolute values**
        - Default iOS: dip
        - Default Android: pixels 
        - Possibilities: px, mm, cm, in, dp/dip, or system
        - dp/dip is recommended:
            - Density-independent pixels (we sometimes call these "points")
            - Android : actual pixels = dip * (screen density) / 160
            - iOS : actual pixels = dip * (screen density) / 163 (effectively 1dip=1px on standard, 1dip=2px on retina)
    - FILL behaviour
    - SIZE behaviour
    - Absolute values (based on selected unit)
    - Percentages (based on parent)
    - top, right, bottom, left anchors
- Image formats
    - GIF, PNG, JPG supported but JPG for pics and PNG preferred for anything else.
    - No SVG supported.
    - Image sizes are really important and Developers should be able to tell you for some very specific assets what is the **exact** resolution expected. Hard requirement in some cases.
    - Overview of Android 9 patch technique.
    - 2 ways of doing splash screens
- **Navigation** and **Forms** are one of the most challenging things to do
    - Navigation
        - Windows
        - Explanations around patterns
            - High level
                - Sub levels
    - Forms
        - Elements
        - Feedback
        - Textarea example
        - Checkbox example
        - Date picker example
- Use symbols to avoid having to repeat yourself, especially for UI elements
- Try to build your own library (or modify an existing one to match the project) but having standards and avoid repetition is key. Similar to what we do for websites with [Styleguide | Cyber-Duck](http://patterns.cyberduck.net/)
    - Typography
    - Buttons
    - Form elements
    - Screen layouts (templates)
    - Screen elements
    - and many more…
- Don’t forget empty states.
- Don’t forget transitions, make it live (but not too much)
    - Push Notification example
- Always test your UI
    - Things should be touchable
    - UX needs to be good
- Deliverables
- Richard could potentially show us what he’s been working on so far

---

### Don’t reinvent the wheel

---

- Past: Photoshop + Smart Object
- Now Sketch Files/Libraries + Symbols
- Tools (App Icons, Splash screens…)
- Libraries (UI Libraries for example)
- Question about Git https://github.com/jtholloran/icons
- [The Best Free Sketch iOS App Icon Template - Savvy Apps](https://savvyapps.com/blog/sketch-ios-app-icon-template)
- [iOS and Android App Icon Generator Sketch freebie - Download free resource for Sketch - Sketch App Sources](https://www.sketchappsources.com/free-source/2183-ios-android-app-icon-generator-sketch-freebie-resource.html)
- sketchappsources.com

---

### Designers and Developers should talk a lot. As always.

---

- Gather technical requirements from Developers
    - For a functionality
    - For the UI
    - For connectivity
    - For feeding back the user on errors
        - While filling a form or performing an action
        - While simply navigating and using the application
    - For another specific thing
    - What units to talk to?
    - What densities?
- Make sure to have a lot of checkpoints with your Developers to approve what has been produced (wireframes, designs, functionalities…)
- Apply the same processes you would apply for a website in terms of workflow and checkpoints.

---

## Resources

---

- [Principles of Mobile App Design: Introduction](https://www.thinkwithgoogle.com/marketing-resources/experience-design/principles-of-mobile-app-design-introduction/)
- [Dribbble - 4_2x.png by Jerry](https://dribbble.com/shots/3835770-Dogdom/attachments/868382)
- [UI Design Do’s and Don’ts - Apple Developer](https://developer.apple.com/design/tips/)
- [Themes - Overview - iOS Human Interface Guidelines](https://developer.apple.com/ios/human-interface-guidelines/overview/themes/)
- [Eight don’ts for your Material Design app – Prototypr](https://blog.prototypr.io/common-material-design-bad-practices-to-avoid-b7995f251329)
- [Material Design](https://material.io/)
- [What Dimensions And Resolution Should Be For iOS And Android App Design?](https://think360studio.com/what-dimensions-resolution-should-be-for-ios-and-android-app-design/)
- [Appcelerator Platform - Appcelerator Docs](http://docs.appcelerator.com/platform/latest/#!/guide/Layouts,_Positioning,_and_the_View_Hierarchy)
