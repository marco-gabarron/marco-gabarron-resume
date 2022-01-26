# Marco Gabarron's Portfolio

Website developed to show Marco Gabarron's portfolio. Website includes Main landing page, projects page and contact me page.
User will find my most recent projects using HTML, CSS, JavaScript and Swift.

![Screens Screenshot](assets/images/screens-screenshot.png)


## Features
------

- Navigation:  
    - Name on Top left corner.
    - Navigation Menu on top right Corner containing Home, Projects and Contact Me links.
    - Font chosen to be a handwritting font on headers and neutral and easy to read font on links and menus.
    - Navigation made to be clear and easy section divisions.

![Navbar Screenshot](assets/images/navbar-screenshot.png)

- Profile Section: 
    - Image to ilustrate what is the theme of the portfolio(coding).
    - Hero image followed by profile picture and a Hello message.
    - This section provides a clear understanding of what the website is about(Portfolio) and main focus(Developer)

![CodeImage Screenshot](assets/images/codeimage-screenshot.png)
![Profile Screenshot](assets/images/profile-screenshot.png)

- My Skills Section: 
    - Add image to ilustrate and easily identify skill.
    - Brief Description of my skills.
    - Color of images and text to match the pallet color of the rest of the website.
    - Idea is to be playful and give more details in Projects page.

![MySkills Screenshot](assets/images/myskills-screenshot.png)

- Get in Touch Section:
    - Brief and nice message to invite user to get in touch with me.
    - Highlight that there is a Contact Me page.
    - Button with link to Contact Me page.

![GetInTouch Screenshot](assets/images/getintouch-screenshot.png)

- Projects Page:
    - Description of Projects Done.
    - Listed technologies used.
    - Added logo image that represents project.

![Projects Screenshot](assets/images/projects-screenshot.png)

- Contact Me Page:
    - Added form for user to get in touch.
    - Name, Surname, Email and Message field input added.

![ContactMe Screenshot](assets/images/contactme-screenshot.png)


## Testing
------

- I tested the page with different browsers(Chrome, Firefox)

- I tested responsiveness of website and can confirm it is retaining design and readability on all screen sizes.

- I confirmed Home, Projects and Contact ME page is readable and easy to unsderstand.

- I have confirmed all input field is working properly and expecting apropriate format(Email format for instance).


### Bugs

##### Solved Bugs

- My skills section in the home page was breaking when on mobile screen. Had to change style.css to proportional size.

### Validator Testing
- HTML: 
    - No errors were returned when passing through the official W3C validator.

- CSS: 
    - No errors were returned when passing through the official (jigsaw)) validator.

- Acessibility
    - I confirmed that the colors and fonts chosen are easy to read and accessible by running through lighthouse in devtools.

![LightHouse Screenshot](assets/images/lighthouse-screenshot.png)

### Unfixed Bugs
No unfixed bugs


## Deployment
------

- The site was deployed to GitHub pages. The steps deploy are as follows:
    - In the GitHub repository, navigate to the Settings tab.
    - From the source section drop-down menu, select the Master Branch.
    - Once the master branch has been selected, the page provided the link to the completed website.

The live link can be found here: <a href="https://marco-gabarron.github.io/marco-gabarron-resume/" target="_blank">Marco's Protfolio</a>


## Credits
------

### Content
- The code to make social media links were taken from CI Love Running projects.

### Media
- Code Image taken from <a href="https://pexels.com" target="_blank">Pexels.</a>.


![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome marco-gabarron,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **September 1, 2021**

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

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


Picture 1
Photo by Sabrina Gelbart from Pexels
https://www.pexels.com/photo/full-frame-shot-of-abstract-pattern-249798/