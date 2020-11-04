# On Hosting your Resume on GitHub (and learning Technical Communication principles!)

Are you looking for a **free, simple way** to host your resume online, and *be able to edit and update it on the fly*? This README tutorial will guide you through the process using the accessible, modern tools of GitHub Pages (*part of a DVCS*), Markdown (*a lightweight markup language*), and Jekyll (*a static site generator*)!  
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
    * Not sure what Markdown is or how to use it? It's a simple-to learn, lightweight markup language, built for online content!
    * Refer to [More Resources](#more-resources) for a quick tutorial to get you started!
* your resume, properly formatted in Markdown (saved in **.md** format!)
    * Refer to [More Resources](#more-resources) for a relatively simple, online Markdown editor to use.

## Setup Process
*This tutorial assumes that you have not made previous repositories (Git's encompassing your project and its history), and **prefaces each major section** of the hosting process with some relevant insight from Etter's software documentation principles, properly delineated from the main content.*

---

### Preface: DVCSs, and GitHub
> To start, why are you using GitHub Pages to host your resume, anyway? GitHub is known as a distributed control version system (DVCS), which, as Etter mentions, has become widely-used among computer scientists for its 
> * high performance system of **sharing, hosting, and updating files**
> * capability for offline work on hosted projects 
> * ability to **work concurrently with other contributors with ease**
>
> By using DVCSs, technical writers are able to keep their documentation constantly up-to-date and encourages more accessible contributions among many different project authors! 
>
>This versatility and accessibility is what drives the main **principle of choosing GitHub, a DVCS, in modern technical communication, even though we may not make use of all of the available features that GitHub has to offer**. 

Now, onto creating your first repository to host your resume!


### Creating your first GitHub repository
1. Login to your GitHub Account.
2. Access the plus-sign (+) dropdown menu on the top right, and select **New Repository**. 

![newrepo](https://github.com/Neppington/neppington.github.io/blob/main/newrepo.gif =250x250) 

3. Enter your repository name, ***which must start with your username and followed by `.github.io`***, as in this template:  
    `[your username].github.io`  
    * If you don't follow this **exact** format, your site won't display at all!
4. Set your repository to **Public** by selecting the dialog option.
5. Scroll down and select **Create repository**.

![reponame](https://github.com/Neppington/neppington.github.io/blob/main/reponame.gif =250x250) 

### Integrating your resume into your site
1. Access your brand-new repository through your GitHub homepage.
2. Start by selecting the **Upload an existing file** option.
3. Select **Choose your files**, and select your Markdown-formatted resume to upload.
    * **Ensure that your resume file is named `index.md`! If it isn't, it will not properly display on your hosted site!**
    * Select **Upload new file** if you already have your .md formatted resume, and upload your file.
    
![upload](https://github.com/Neppington/neppington.github.io/blob/main/upload.gif =250x250) 

**Note**: Your GitHub Page may take **up to 5 minutes** to properly load any changes you make. 

*Aside*: If you want to write your own documentation for this site, feel free to upload a Markdown-formatted **README.md** to your repository!

---

### Preface: Static websites, and Jekyll
> Why static websites? Etter's take on the matter is pretty simple: static websites are **fast, simple, portable, and secure**: 
> * Static websites are **portable**, in which can be hosted almost everywhere (GitHub Pages included), and contain no dependencies on servers, databases, or applications. 
> * Since static sites *just serve page data,* there's no need to dynamically process any elements, making them **fast and digestible** for most computer hardware
> * Due to their structure, they're **secure and very easy to edit on the fly**
>
> These beneficial attributes of static websites are the what create this **principle of using static websites over other styles of content delivery**. In order to make anything more than basic static sites, Etter highly recommends utilizing a **static site generator**, such as Jekyll. Jekyll's basic functions that we'll make use of are **filling it with content (using your Markdown-formatted resume) and applying a theme (using the sample templated HTML and CSS provided by GitHub)**. For more advanced functionalities of Jekyll, refer to [More Resources](#more-resources) for a video series tutorial for it!

Now, let's get to sprucing up your website!


### Integrating site themes with your GitHub Page
1. Go to your repository homepage.
2. Select the **Settings** tab.
3. Scroll below to find the **GitHub Pages** section in the Options submenu.
4. Select the **Change theme** button.
5. Select a theme that you like!
6. Select **Select theme** once you're satisfied with the layout.

![theme](https://github.com/Neppington/neppington.github.io/blob/main/theme.gif =250x250) 

### Modifying your site theme and making it your own
To truly make this page your own, let's make a simple change: editing the title of your page.
1. Return to your repository homepage.
   * Notice that a new file has been created in your repository root: `_config.yml`. This will be used to edit your site theme!
2. Select the `_config.yml` file.
3. Select the **pencil icon** found at the header of the code.
4. Type in `title:` below the currently-used lines, and choose a title name (eg. *title: My resume site!*).
5. Select **Commit changes.**

![title](https://github.com/Neppington/neppington.github.io/blob/main/title.gif =250x250)

***Congratulations! Your site should now be completely set up and look stylish, to boot!***

![resume](https://github.com/Neppington/neppington.github.io/blob/main/resume.gif =250x250)

---

### More Resources
* [A quick Markdown tutorial](https://markdowntutorial.com)
* [Markdown Live Preview](https://markdownlivepreview.com/)
* [Andrew Etter's book on Amazon](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
* [Video series tutorial on Jekyll](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)

## Authors and Acknowledgements
* [John Rohan, Template theme author](https://twitter.com/jonrohan/)

* My groupmates in my COMP 3040 class, **Group 16**:
   * Jaskeerat Singh
   * Ali Jasim
   * Zhi Zheng

## Frequently Asked Questions

### Why is Markdown better than a word processor?
Within the context of software documentation, Markdown is a far better in formatting and updating published content. Word processors, as Etter puts it, are made "to create short, attractive PDFs that can be consumed and discarded. Markdown provides the basis for content delivery for static site generators and DVCSs, encourages more frequent contribution opportunities by being easy-to-learn, and is relatively simple to update!
### Why is my resume not showing up?
There can be many reasons, but here are a few suggestions:
   * Check if you've properly labeled your repository as `[your username].github.io?`.
   * Check if your resume file is properly named `index.md`, and formatted correctly.
   * If you've *just* uploaded your files, wait for 5-10 minutes; GitHub takes some time to properly load everything, so try to be patient!
