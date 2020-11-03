# On Hosting your Resume on GitHub (and learning Technical Communication principles!)

Are you looking for a **free, simple way** to host your resume online, and *be able to edit and update it on the fly*? This README tutorial will guide you through the process using the accessible, modern tools of GitHub Pages (part of a DVCS), Markdown (an online text syntax), and Jekyll (a static site generator)!  
You'll also gain some **insight into the modern technical communication principles** that helped bring this project to life: Andrew Etter, in his book *Modern Technical Writing: An Introduction to Software Documentation*, outlines the methodologies that influenced the usage of these specific tools that you will use to host your resume (*and bolster your technical communication toolkit*)! 

**Important note:** this README tutorial will be taught using the ***GitHub's browser client.*** This tutorial will **not** cover the console client or the desktop client variants of GitHub.

## Table of Contents
* [Prerequisites](#prerequisites)
* [Setup Process](#setup-process)
* [Authors and Acknowledgements](#authors-and-acknowledgements)
* [Frequently Asked Questions](#frequently-asked-questions)

## Prerequisites

* a GitHub Account
    * If you don't have one, visit [GitHub's website](https://github.com/) and make your own free account!
* (enough) Markdown know-how
    * Not sure what Markdown is or how to use it? Refer to [More Resources](#more-resources) for a quick tutorial to get you started!
* your resume, properly formatted in Markdown (saved in **.md** format!)
    * Refer to [More Resources](#more-resources) for a relatively simple, online Markdown editor to use.

## Setup Process
*This tutorial assumes that you have not made previous repositories (Git's encompassing your project and its history), and **prefaces each major section** of the hosting process with some relevant insight from Etter's software documentation principles.*

---

### Preface: GitHub
To start, why are you using GitHub Pages to host your resume, anyway? GitHub is known as a distributed control version system (DVCS), which, as Etter mentions, has become widely-used among computer scientists for its 
* high performance system of **sharing, hosting, and updating files**
* capability for offline work on hosted projects 
* ability to **work concurrently with other contributors with ease**

By using DVCSs, technical writers are able to keep their documentation constantly up-to-date (relatively easily, mind you), and additionally allowing more accessible contributions among contributing members. 

This versatility and accessibility is what drives the main principle of choosing GitHub, a DVCS, in modern technical communication, even though we may not make use of all of the available features that GitHub has to offer. Now, onto creating your first repository to host your resume!


### Creating your first GitHub repository
1. Login to your GitHub Account.
2. Select the **New** button, found on your GitHub homepage.  
**RESULT**: You will be redirected to the repository creation page.

3. Enter your repository name, ***which must start with your username and followed by `.github.io`***, as in this template:  
    `[your username].github.io`  
    * If you don't follow this **exact** format, your site won't display at all!
4. Set your repository to **Private** by selecting the dialog option.
5. Select **Create repository**.

**RESULT:** With this, you should have your first GitHub repository active and available!

### Integrating your resume and initializing your README
1. Access your brand-new repository through your GitHub homepage.
2. Select the **Add File** dropdown.
    * **Ensure that your resume file is named `index.md`! If it isn't, it will not properly display on your hosted site!**
    * Select **Upload new file** if you already have your .md formatted resume, and upload your file.
3. Select the same **Add File** dropdown **upload** or **create** your **README.md**. (for now, this doesn't have to be filled with anything)

**RESULT**: You should now be able to see your resume on your GitHub Pages domain! Simply **enter your repository name as a website** and you'll be redirected to your hosted site.  

**Note**: Your GitHub Page may take **up to 5 minutes** to properly load any changes you make. 


---

### Preface: Jekyll
You may have noticed that, if you visit your current GitHub page, your layout looks... bland. Don't fret, as GitHub has Jekyll (a static site generator) integrations built-in! You'll be able to easily customize the look of your website in no time.
Other than that, why static websites? Etter's take on the matter is pretty simple: static websites are **fast, simple, portable, and secure**: 
* Static websites are **portable**, in which can be hosted almost everywhere (GitHub Pages included), and contain no dependencies on servers, databases, or applications. 
* Since static sites *just serve page data,* there's no need to dynamically process any elements, making them **fast and digestible** for most computer hardware
* Due to their **simple** strucuture, there are little to no exploitable components, making them **secure**

Jekyll allows you to easily integrate static site components into your GitHub Page. That being said, we're not even using a *fraction* of it's potential! If you want to learn more about Jekyll's capabilities, refer to [More Resources](#more-resources) for a video series on the static site generator!

Now, let's get to sprucing up your website!


### Integrating Jekyll themes with your GitHub Page
1. Go to your repository homepage, found by selecting it on your GitHub homepage.
2. Select the **Settings** tab.
3. Scroll below to find the **GitHub Pages** section in the Options submenu.
4. Select the **Change theme** button.

**RESULT**: You will be redirected to the theme changer page, displaying previews of what your site will look like.

5. Select a theme that you like!
6. Select **Select theme** once you're satisfied with the layout.

**RESULT**: after a few minutes to let the site update, your website will have integrated with a Jekyll theme!

### Modifying your Jekyll theme and making it your own
To truly make this page your own, let's make a simple change: editing the title of your page.
1. Return to your repository homepage.
   * Notice that a new file has been created in your repository root: `_config.yml`. This will be used to edit your Jekyll theme!
2. Select the `_config.yml` file.

**RESULT**: You will be redirected to the view/update page for the .yml file.

3. Select the **pencil icon** found at the header of the code.
4. Type in `title:` below the currently-used lines, and choose a title name (eg. *title: My resume site!*).
5. Select **Commit changes.**

***Congratulations! Your site should now be completely set up and look stylish, to boot!***

---

### More Resources
* [A quick Markdown tutorial](https://markdowntutorial.com)
* [Markdown Live Preview, a simple, online Markdown Editor](https://markdownlivepreview.com/)
* [Andrew Etter's book on Amazon; go and support him!](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* [Video series tutorial on Jekyll](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)

## Authors and Acknowledgements
* [John Rohan, Template theme author](https://twitter.com/jonrohan/)

* My groupmates in my COMP 3040 class, **Group 16**:
   * Jaskeerat Singh
   * Ali Jasim
   * Zhi Zheng

## Frequently Asked Questions

### Why is Markdown better than a word processor?
Word processors, as Etter puts it, are made "to create short, attractive PDFs that can be consumed and discarded. Markdown is far simpler to integrate and format into HTML, and blend very well with the constantly-updating environment that is DVCSs, where projects are constantly updated (consequently, the documentation must be constantly updated, too!).
### Why is my resume not showing up?
There can be many reasons, but here are a few suggestions:
   * Check if you've properly labeled your repository as `[your username].github.io?`.
   * Check if your resume file is properly named `index.md`, and formatted correctly.
   * If you've *just* uploaded your files, wait for 5-10 minutes; GitHub takes some time to properly load everything, so try to be patient!
