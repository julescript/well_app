<img src="./readme/title1.svg" alt="Title" title="Title" />
test 1 2 3
![Title](./readme/title1.svg)
test 1 2 3
<img src="./readme/title2.svg" alt="Title" title="Title" />
test 1 2 3
![Title](./readme/title2.svg)
test 1 2 3

<div align='center'>
<a href="https://aimeos.org/">
    <img src="https://aimeos.org/fileadmin/template/icons/logo.png" alt="Aimeos logo" title="Aimeos" align="center" height="60" />
</a>
</div>
<br />

<div align='center'>

[Ameos](https://aimeos.org/TYPO3) is THE professional, full-featured and
high performance e-commerce extension for TYPO3!  You can install it in your
existing TYPO3 web site within 5 minutes and can adapt, extend, overwrite
and customize anything to your needs.
  
<a href='https://github.com/chroline/well_app/releases'>
  
<img src='https://img.shields.io/github/v/release/chroline/well_app?color=%23FDD835&label=version&style=for-the-badge'>
  
</a>
  
<a href='https://github.com/chroline/well_app/blob/main/LICENSE'>
  
<img src='https://img.shields.io/github/license/chroline/well_app?style=for-the-badge'>
  
</a>
  
</div>

<br />

---

<div align='center'>
  
### Quick Links
  
<a href='https://projects.colegaw.in/well-app?utm_source=GitHub&utm_medium=readme&utm_campaign=well_app_readme'>
  
<img src='https://img.shields.io/badge/HOMEPAGE-gray?style=for-the-badge'>
  
</a>
  
<a href='https://projects.colegaw.in/well-app/research?utm_source=GitHub&utm_medium=readme&utm_campaign=well_app_readme'>
  
<img src='https://img.shields.io/badge/RESEARCH-blue?style=for-the-badge'>
  
</a>
  
<a href='https://projects.colegaw.in/well-app/case-study?utm_source=GitHub&utm_medium=readme&utm_campaign=well_app_readme'>
  
<img src='https://img.shields.io/badge/CASE STUDY-green?style=for-the-badge'>
  
</a>
  
<br />
  
</div>

---

### The Well app is available for download! 🥳 🚀

- iOS/macOS: Search for "well: reboot your mindset" on the [iOS app store](https://apps.apple.com/us/app/well-reboot-your-mindset/id1573357406).
- Web: Visit [https://well-app.netlify.app](https://well-app.netlify.app). Install as a PWA for native-like functionality!
- Android: coming soon 👀

---

<br />

<div align="center">

**[PROJECT PHILOSOPHY](https://github.com/chroline/well_app#-project-philosophy) • 
[TECH STACK](https://github.com/chroline/well_app#-tech-stack) • 
[SITE SETUP](https://github.com/chroline/well_app#-site-setup) • 
[WHAT'S NEXT?](https://github.com/chroline/well_app#-spread-the-word) • 
[LICENSE](https://github.com/chroline/well_app#%EF%B8%8F-license)**

</div>

<br />

# 🧐 Project philosophy

> The Well app is a mental health and mindfulness app built on top of the science of positive psychology. The Well app is more than just another meditation or journaling app; it encourages you to enhance and reflect on your day with structured, guided activities.
> 
> There are 5 daily tasks that the Well app asks you to complete each day: record 3 gratitudes, write a journal entry, perform 3 acts of kindness, exercise for 20 minutes, and meditate for 15 minutes.

**Read more about the Well app on [the project homepage](https://projects.colegaw.in/well-app?utm_source=GitHub&utm_medium=readme&utm_campaign=well_app_readme).**

# 👨‍💻 Tech stack

Here's a brief high-level overview of the tech stack the Well app uses:

- This project uses the [Flutter app development framework](https://flutter.dev/). Flutter is a cross-platform hybrid app development platform which allows us to use a single codebase for apps on mobile, desktop, and the web.
- For persistent storage (database), the app uses the [Hive](https://hivedb.dev/) package which allows the app to create a custom storage schema and save it to a local database.
- To send local push notifications, the app uses the [flutter_local_notifications](https://pub.dev/packages/flutter_local_notifications) package which supports Android, iOS, and macOS.
  - 🚨 Currently, notifications aren't working on macOS. This is a known issue that we are working to resolve!
- The app uses the font ["Work Sans"](https://fonts.google.com/specimen/Work+Sans) as its main font, and the design of the app adheres to the material design guidelines.

For more information on the technologies that power the Well app, check out the [Tech Stack](https://github.com/chroline/well_app/wiki/Tech-Stack) page on our wiki.


# 💻 Site setup

TYPO3 10+ requires a site configuration which you have to add in "Site Management" > "Sites" available in the left navigation.

## Page setup

The page setup for an Aimeos web shop is easy if you import the example page tree for TYPO3 10/11:

* [21.10+ page tree](https://aimeos.org/fileadmin/download/Aimeos-pages_21.10.t3d) only

**Note:** The Aimeos layout expects [Bootstrap](https://getbootstrap.com) providing the grid layout!

### Go to the import view

* In Web::Page, root page (the one with the globe)
* Right click on the globe
* Move the cursor to "Branch actions"
* In the sub-menu, click on "Import from .t3d"

![Go to the import view](https://aimeos.org/docs/images/Aimeos-typo3-pages-menu.png)

### Upload the page tree file

* In the page import dialog
* Select the "Upload" tab (2nd one)
* Click on the "Select" dialog
* Choose the file you've downloaded
* Press the "Upload files" button

![Upload the page tree file](https://aimeos.org/docs/images/Aimeos-typo3-pages-upload.png)

### Import the page tree

* In Import / Export view
* Select the uploaded file from the drop-down menu
* Click on the "Preview" button
* The pages that will be imported are shown below
* Click on the "Import" button that has appeared
* Confirm to import the pages

![Import the uploaded page tree file](https://aimeos.org/docs/images/Aimeos-typo3-pages-import.png)

Now you have a new page "Shop" in your page tree including all required sub-pages.

# 🌟 What's next?

If you want to say thank you and/or support active development of the Well app:

- Add a GitHub Star to the project!
- Tweet about the project on your Twitter!
  - Tag [@colegawin_](https://twitter.com/colegawin_) and/or `#thewellapp`
- Leave us a review [on the iOS App Store](https://apps.apple.com/us/app/well-reboot-your-mindset/id1573357406)!

Thanks so much for your interest in growing the reach of the Well app!

_**PS:** consider sponsoring me ([Cole Gawin](https://colegaw.in)) to continue the development of this project on [BuyMeACoffee](https://buymeacoffee.com/colegawin) :)_

---

# 💛

Reminder that *you are great, you are enough, and your presence is valued.* If you are struggling with your mental health, please reach out to someone you love and consult a professional. [There are many resources for you to get help in a time of need.](https://www.nimh.nih.gov/health/find-help)
