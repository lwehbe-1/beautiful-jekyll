---
layout: page
title: Getting Started
subtitle: Set up your website in minutes!
---

## Overview of Steps Required

There are only three simple steps to follow.

Here is a 40-second video demonstrating the process:

<img src="../img/install-steps.gif" style="width:100%;" alt="Installation steps" />

---

<div class="gs-section-01" markdown="1">

### 1. Fork the Beautiful Jekyll Repository

Fork the [repository](https://github.com/daattali/beautiful-jekyll)  
by clicking the Fork button on the top right corner in GitHub.

</div>

---

<div class="gs-section-02" markdown="1">

### 2. Rename the Project

Click on **Settings** in your repository and rename your repository  
to `<yourusername>.github.io` to activate GitHub Pages.

</div>

---

<div class="gs-section-03" markdown="1">

### 3. Customize Your Website

Edit the `_config.yml` file to update the website settings,  
such as title, description, and social media links.

</div>

---

## Apply Custom Styling

To demonstrate that you can apply CSS styles,  
we will make each step title a different color.

Add this **CSS code** at the bottom of this file:

```html
<style>
/* Step 1 - Red Title */
.gs-section-01 h2 { color: red; }

/* Step 2 - Blue Title */
.gs-section-02 h2 { color: blue; }

/* Step 3 - Green Title */
.gs-section-03 h2 { color: green; }
</style>
