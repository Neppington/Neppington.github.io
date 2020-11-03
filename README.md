# On Hosting your Resume on GitHub (and learning Technical Communication principles!)

Are you looking for a **free, simple way** to host your resume online, and *be able to edit and update it on the fly*? This README tutorial will guide you through the process using the accessible, modern tools of GitHub Pages, Markdown, and Jekyll!  
Along the way, you'll also gain some insight into the modern technical communication principles that helped bring this project to life: Andrew Etter, in his book *Modern Technical Writing: An Introduction to Software Documentation*, outlines the methodologies that influenced the usage of these specific tools that you will use to host your resume (and bolster your technical communication toolkit)! 

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
To start, why are you using GitHub Pages to host your resume, anyway? The answer lies in the current state of the field of computer science, and the common tools that lead the industry. GitHub is known as a distributed control version system (DVCS), which, as Etter mentions, has become widely-used among computer scientists for its 
* high performance, no-frills system of sharing and hosting of files
* capability for offline work on hosted projects (just download the project to your local PC!)
* ability to work concurrently with other contributors with ease 

...That being said, **technical writers should use these same DVCSs since so many developers prefer utilizing them.** By using DVCSs, we can more closely work with software developers, allowing more opportunities for smoother contribution than if we used more centralized control systems. 

This versatility what drives the main principle of choosing GitHub, a DVCS, in modern technical communication, even though we may not make use of all of the available features that GitHub has to offer. Leave that to the software developers! Now, onto creating your first repository to host your resume!


#### Creating your first GitHub repository
1. Login to your GitHub Account.
2. Select the **New** button, found on your GitHub homepage.  
**RESULT**: You will be redirected to the repository creation page.

3. Enter your repository name, ***which must start with your username and followed by `.github.io`***, as in this template:  
    `[your username].github.io`  
    * If you don't follow this **exact** format, your site won't display at all!
4. Set your repository to **Public** by selecting the dialog option.
5. Select **Create repository**.

**RESULT:** With this, you should have your first GitHub repository active and available!

#### Integrating your resume and initializing your README
1. Access your brand-new repository through your GitHub homepage.
2. Select the **Add File** dropdown.
    * **Ensure that your resume file is named `index.md`! If it isn't, it will not properly display on your hosted site!**
    * Select **Upload new file** if you already have your .md formatted resume, and upload your file.
3. Select the same **Add File** dropdown **upload** or **create** your **README.md**. (for now, this doesn't have to be filled with anything)

**RESULT**: You should now be able to see your resume on your GitHub Pages domain! Simply **enter your repository name as a website** and you'll be redirected to your hosted site.  

**Note**: Your GitHub Page may take **up to 5 minutes** to properly load any changes you make. 


---

### Preface: Jekyll

#### Integrating Jekyll themes with your GitHub Page
1. Go to your repository homepage, found by selecting it on your GitHub homepage.
2. Select the **Settings** tab.
3. Scroll below to find the **GitHub Pages** section in the Options submenu.
4. Select the **Change theme** button.

**RESULT**: You will be redirected to the theme changer page, displaying previews of what your site will look like.

5. Select a theme that you like!
6. Select **Select theme** once you're satisfied with the layout.

**RESULT**: after a few minutes to let the site update, your website will have integrated with a Jekyll theme!

### More Resources
* [A quick Markdown tutorial](https://markdowntutorial.com)
* [Markdown Live Preview, a simple, online Markdown Editor](https://markdownlivepreview.com/)
* [Andrew Etter's book on Amazon; go and support him!](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

## Authors and Acknowledgements

## Frequently Asked Questions
