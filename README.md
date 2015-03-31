# Patterns-Colors
The Patterns Color repo is where we host Esri's official color documentation that can be see on the forth coming Patterns.esri.com site.  Currently the repo contains a mixture of CSS, SASS and Stylus files tha you can use in your projects.

Feel free to download the files for use in your project or add a refrence in your files that points to the CDN files `CDN Link Coming Soon`.  Also feel free to use a `Submodule` to import these files into your project.

## SASS Variables file
A [SASS](http://sass-lang.com/) variables file can be found in the SCSS folder `scss/variables.scss`.  To learn how to use `Variable` files within SASS please read [USING SASS Variables](http://sass-lang.com/guide#topic-2).  


## Stylus Variables file
A [Stylus](http://learnboost.github.io/stylus/) variables file can be found in the Styus folder `stylus/variables.scss`. To learn how to use `Variable` files within Styus please read [USING Styus Variables](http://learnboost.github.io/stylus/docs/variables.html).  

## To use CSS
A set of CSS reference files have been added to the CSS folder:
- `css/brand_colors.css`
- `css/calcite_core_colors.css`
- `css/calcite_gray_colors.css`
- `css/calcite_highlight_colors.css`
- `css/calcite_vibrant_colors.css`
- `css/complete.css`  <- all of the above compiled into one file.

Very shortly we will list out a set of URL's from our CDN which can be used in your local projects.

## Patterns JSON Folder
The Patterns JSON folder contains the source files that are used to build the pages on Patterns.esri.com and should NOT be used within a project as they contain lots of information not needed for standalone projects.  These files are created using SCSS.

# Contributing to Patterns Color

Installing Patterns Color was designed to be fairly painless. If you have any problems, be sure to [submit an issue](https://github.com/Esri/patterns-color/issues/).

### Fork the Repository

All the code for Patterns Color lives [on GitHub](https://github.com/esri/patterns-color). We use the [fork and pull model](https://help.github.com/articles/using-pull-requests/) to manage contribution.

1. Fork the repository so you have your own copy (`your-username/patterns-color`)
2. Clone the repo locally with `git clone https://github.com/your-username/patterns-color`
3. Move into the clone repo:  `cd patterns-color`

You should also add `Esri/patterns-color` as a remote at this point. We generally call this remote branch 'upstream':

```
git remote add upstream https://github.com/Esri/patterns-color
```

### How We Use GitHub

All the code for Patterns Color lives [on GitHub](https://github.com/esri/patterns-color). We use the [fork and pull model](https://help.github.com/articles/using-pull-requests/) to manage contribution. To contribute, you should:

1. Commit your changes.
2. Note your changes in `CHANGELOG.md`
3. Make sure your copy is up to date: `git pull upstream master`
4. Push your changes to your fork: `/your-username/patterns-color`
5. Open a pull-request from your fork (`/your-username/patterns-color`) to the 'upstream' fork (`/Esri/patterns-color`).


## Still to do
- [ ] Add Color swatch files for Adobe
- [ ] Add Color PDF file
- [ ] Add link to the CDN

