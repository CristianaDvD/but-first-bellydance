# But first, Bellydance!

The But first, Bellydance! website was created to be responsive, permitting all its visitors to have a good User Experience on different screen-size devices. 

![But first, Bellydance! seen on different devices](assets/images/site-responsive.png)

[View But first, Bellydance! website on Github pages](https://cristianadvd.github.io/but-first-bellydance/)
---

## Contents

---
## User Experience

The But first, Bellydance! website welcomes all visitors that want to find out about belly dance classes for everyone over 2 years old, with different options for children and adults. Also, all visitors can access the Hire page to transform any event into a unique one. The goal of the site is to offer a different entertainment environment.

### External user's goals.

  * The site's users are interested in finding the most appropriate class option by age, when it takes place and price for all.
  * The users are looking for a hire enquiry form to have a bellydancer at their event.
  * The site is expected to have a gallery with high quality pictures.
  * The users are looking to find contact information easily.


## Design

### Colour Scheme

![But first, Bellydance! colour palette](assets/images/But%20first,%20Bellydance!%20colour%20palette.png)

The website uses a colour palette to match with the majority of images used. The colour palette was created using the [Coolors](https://coolors.co/) website.


### Typography 

Google Fonts was used for the following fonts:
* Tapestry font was used for headings. It is a serif font.
* Delius Swash Caps font was used for the body text on the site. It is a sans-serif font.

### Imagery

All images used for the website are credited in the [credits](#Credits) section.


## Features

The website is comprised of six pages, four of them being accessible from the navigation bar (home page, classes, hire, gallery) and the fifth which is a thank you page that opens when all three forms of the website (subscription, join now for classes and hire form) are submitted.

### Navigation bar
All pages of the website display a responsive navigation bar at the top which allows the user to navigate through the site.  To the left of the navigation bar is an image of bellydancer ilustration logo together with the text But first, Bellydance!. To the right of the navigation bar are the links to the websites pages (home, classes, hire, gallery, contact). To allow a good user experience of the site, the But first, Bellydance! text is hidden with a media query on mobile devices to prevent the navigation bar looking cluttered. When viewing with mobile devices the navigation links change to a burger toggler. This was implemented to give the site a clean look and to promote a good user experience, as users are used to seeing the burger icon when on mobile devices to navigate a site.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**June 18, 2024,** Add Mongo back into template

**June 14, 2024,** Temporarily remove Mongo until the key issue is resolved

**May 28 2024:** Fix Mongo and Links installs

**April 26 2024:** Update node version to 16

**September 20 2023:** Update Python version to 3.9.17.

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
