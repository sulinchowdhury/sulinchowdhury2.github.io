A Github Pages template for academic websites. This was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.

# Initial Setup Instructions (See Below for Customization Tips)

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://academicpages.github.io/

# How to customize your page?
Once the basic page is up and running, you can get started with your customization in the following places:
1. Go to "config.yml" to change information that appears in the left hand banner, including your name and title. 
2. Go to "data > navigation" to define the names and order of the tabs for your site (e.g., Research, CV, Contact)
3. Go to "pages" to create pages corresponding with these tabs using Markdown (e.g., Research)
4. Go to "files" to upload the pdfs or other documents you want to host and link to on your website, e.g., your CV
5. Go to "images" to upload your profile picture and other images for the website

Here are some helpful links to building and customizing your site:
https://zenglix.github.io/personal_website/
https://www.cross-validated.com/Personal-website-with-Minimal-Mistakes-Jekyll-Theme-HOWTO-Part-II/
