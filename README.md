<!--
  <<< Author notes: Header of the course >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses Creative Commons Attribution 4.0 International.
-->

# Creating Your First GitHub Pages Site

_This course will guide you through the process of creating your first website using GitHub Pages._

<!--
  <<< Author notes: Start of the course >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
  Each step should be wrapped in <details>/<summary>, with an `id` set.
  The start <details> should have `open` as well.
  Do not use quotes on the <details> tag attributes.
-->

<details id=0 open>
<summary><h2>Welcome</h2></summary>

Welcome to the course! In this tutorial, you will learn how to create a personal website using GitHub Pages. This is a great way to showcase your projects or share your thoughts through blogging.

- **Who is this for**: Anyone interested in web development or sharing content online.
- **What you'll learn**: How to set up and customize your own GitHub Pages site.
- **What you'll build**: A simple website with a homepage and blog posts using Jekyll.
- **Prerequisites**: Basic understanding of Git and GitHub.
- **Duration**: Approximately 30 minutes.

**Course tips:**
- Glossary terms will be _emphasized_ and linked to their definitions.

## How to start this course

1. Right-click **Start course** and open the link in a new tab.
   <br />[![start-course](https://user-images.githubusercontent.com/1221423/218596841-0645fe1a-4aaf-4f51-9ab3-8aa2d3fdd487.svg)](https://github.com/skills/github-pages/generate)
2. Follow the prompts to create a new repository.

</details>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
-->

<details id=1>
<summary><h2>Step 1: Create Your Repository</h2></summary>

_To begin, let's create a new repository for your website._

### :keyboard: Activity: Create a repository

1. Go to [GitHub](https://github.com) and log in to your account.
2. Click on the **New** button to create a new repository.
3. Name your repository `my-github-pages-site`.
4. Set it to **Public** and check the box for **Initialize this repository with a README**.
5. Click **Create repository**.

</details>

<details id=2>
<summary><h2>Step 2: Enable GitHub Pages</h2></summary>

_Now that you have created your repository, let's enable GitHub Pages._

### :keyboard: Activity: Enable GitHub Pages

1. In your new repository, click on **Settings**.
2. Scroll down to the **Pages** section on the left sidebar.
3. Under **Source**, select `main` branch and click **Save**.
4. Wait a moment for GitHub to publish your site.

</details>

<details id=3>
<summary><h2>Step 3: Customize Your Site</h2></summary>

_It's time to customize your site using Jekyll._

### :keyboard: Activity: Configure Jekyll

1. In your repository, create a new file named `_config.yml`.
2. Add the following content:
title: My GitHub Pages Site
description: A simple site created with GitHub Pages
theme: minima
3. Commit your changes.

</details>

<details id=4>
<summary><h2>Step 4: Create Your Homepage</h2></summary>

_Let's create an `index.md` file for your homepage._

### :keyboard: Activity: Create homepage

1. Create a new file named `index.md`.
2. Add the following content:
Welcome to My Site
This is my first GitHub Pages site! I’m excited to share my projects and thoughts here.
3. Commit your changes.

</details>

<details id=5>
<summary><h2>Step 5: Publish Your Changes</h2></summary>

_Nice work! Now let's publish everything._

### :keyboard: Activity: Merge changes

1. Go back to the main page of your repository.
2. You should see a notification that your site is published at `https://<your-username>.github.io/my-github-pages-site/`.
3. Click on the link to view your live site!

</details>

<!--
<<< Author notes: Finish >>>
-->

<details id=X>
<summary><h2>Finish</h2></summary>

_Congratulations! You've successfully created and published your first GitHub Pages site!_

<img src=https://octodex.github.com/images/constructocat2.jpg alt=celebrate width=300 align=right>

### What's next?

- Explore more features of Jekyll and customize your site further!
- Share your site with friends and family!
- Consider contributing to open source projects on GitHub.

</details>

---

Get help: [Post in our discussion board](https://github.com/skills/.github/discussions) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2025 Mmabiaa &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
