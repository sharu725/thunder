# Features

## Customizable theme
The theme can be customized just by changing few variables in **_config.yml** file.

## Light-weight
Since the theme is based on default Jekyll theme, it is very light-weight. No JavaScript except analytics is used!
![jekyll theme thunder speed test](/images/webpagetest-jekyll-theme-thunder.jpg)


# Installation
Fork the ``master`` branch and delete ``gh-pages`` branch in it. This is important because ``gh-pages`` branch is used here only to host the blog. You should be using the master branch as the source and create a fresh ``gh-pages`` branch.

## How to delete old **gh-pages** branch?
After forking the repository, click on **branches**.


![delete gh-pages branch](/images/delete-github-branch.png)

Delete ``gh-pages`` branch.
![delete gh-pages branch](/images/delete-github-branch-2.png)

You have to create a new ``gh-pages`` branch using the master branch. Go back to the forked repository and create ``gh-pages`` branch.

![create gh-pages branch](/images/create-gh-pages-branch.JPG)

Now, go to settings and check the **Github Pages** section. You should see a URL where the blog is hosted.

This process will host the theme as a **Project Page**. You can also download the files for local development. 

Default theme will look like this

![webjeda thunder jekyll theme](/images/thunder-jekyll-theme.jpg)

This theme is responsive.

![webjeda thunder jekyll responsive theme](/images/thunder-responsive-jekyll-theme.jpg)


# Customization

## Theme
The theme provides a nice header that can be customized by changing colors in the **_config.yml** file.

<pre>

#color scheme
color-1: '#E64C3C'
color-2: '#F0C419' 

</pre>

![webjeda sidebar theme](/images/thunder-jekyll-theme-2.jpg)

Remember, while developing locally, every change you make in **_config.yml** is applied only if you restart ``jekyll serve`` process.

## Font 
The default font is Helvetica. Text shadow is used to give it a little deapth.

## Logo
The **webjeda thunder** logo is an SVG file. This can be removed and text can be used as the logo. Make these changes in the **header** file. But I suggest to use an SVG or an image.

# Development
Make changes to the **master** branch and create a pull request. Do not use **gh-pages** branch as it is used to host the theme.

# License
MIT License