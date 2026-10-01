# Editing Guide

## Change About Me or research interests

Open `index.html` in Visual Studio Code and search for `About Me` or `Research Interests`.

## Change the profile photo

Replace `assets/profile.jpg` with a new JPG image using the same file name.

## Update the CV

Replace `assets/Safran_Khan_CV.pdf` with the newest CV using the same file name.

## Add a publication

Open `publications.html` and copy one complete `<article class="publication">` block. Change the title, authors, journal, year, and link.

## Add a conference

Open `conferences.html` and copy one complete `<div class="conference-item">` block. Change the year, title, authors, conference, location, and date.

## Add a post

Open `news.html`. The current page is prepared for future research notes. Individual post pages can be added later.

## Change colors or layout

Open `assets/styles.css`. The color settings are near the top under `:root` and `html[data-theme="dark"]`.

## Publish with GitHub Pages

Create a public repository named `YOURUSERNAME.github.io` and upload all files and folders from this website folder into the repository root. Then open repository Settings, Pages, choose deployment from the `main` branch, and select the root folder.
