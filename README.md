# Healthy Mind Tech

## Instructions on how to contribute to the website

* We have selected the `minima` theme for the GitHub pages. (repo for the theme: https://github.com/jekyll/minima, and other support themes are: https://pages.github.com/themes/). 
  * Config on what theme we are using is in the `_config.yml` file. 
  * See the docs here: https://docs.github.com/en/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll

* We can customize the theme's layout and design (CSS) by overwriting the theme's file. 
  * That is, look in the original theme repo and create corresponding folders and files with the customizations you want in order to overwrite the original theme files.
  * See the docs here: https://docs.github.com/en/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll#customizing-your-themes-css

* To add new content, create a new `.md` file in the root folder
  * See the docs here: https://docs.github.com/en/github/working-with-github-pages/adding-content-to-your-github-pages-site-using-jekyll#adding-a-new-page-to-your-site
  * Start the file with the following:
  ```
    layout: page
    title: "PAGE TITLE"
    permalink: /URL-PATH/
  ```
  * Add your page content after that 

* To run Jekyll locally and look how the site looks like before pushing to github, see the docs: https://docs.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll

