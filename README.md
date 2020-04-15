# Deep Learning with R

Work in progress development of the course material for the BIOS691 "Deep Learning with R" short course, June 8-12, 2020. The course is largely based on the [**Deep learning with R**](https://www.manning.com/books/deep-learning-with-r) book by François Chollet (the creator of Keras) with J. J. Allaire (the founder of RStudio and the author of the R interfaces to Keras and TensorFlow), and the associated code repository [**R notebooks for the code samples of the book "Deep Learning with R"**](https://github.com/jjallaire/deep-learning-with-r-notebooks). Course web site is https://bios691-deep-learning-r.netlify.com/

## Site template

Site template is based on the ["Statistical Image Analysis Course for Neuroscientists"](https://github.com/laderast/stats_for_neuroscientists) repository developed by [Ted Laderas](https://laderast.github.io/). The original source is ["GSU MPA/MPP course on program evaluation and causal inference"](https://github.com/andrewheiss/evalsp20.classes.andrewheiss.com) repository by [Andrew Heiss](https://www.andrewheiss.com/)

## Theme

This site uses the [Academic Hugo theme](https://sourcethemes.com/academic/), with some slight template modifications found in `/assets/` and `layouts/`. The theme is included as a submodule, so when when cloning for the first time, use this command to get the theme too:

    git clone --recursive https://github.com/gcushen/hugo-academic.git

To get the theme later, use this command:

    git submodule add \
      https://github.com/gcushen/hugo-academic.git \
      themes/hugo-academic

To update to the latest version of the theme, use:

    git submodule update --recursive --remote
