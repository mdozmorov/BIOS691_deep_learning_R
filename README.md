# Deep Learning with R

Work in progress development of the course material for the BIOS691 "Deep Learning with R" short course, June 8-12, 2020. The course is largely based on the [**Deep learning with R**](https://www.manning.com/books/deep-learning-with-r) book by François Chollet (the creator of Keras) with J. J. Allaire (the founder of RStudio and the author of the R interfaces to Keras and TensorFlow), and the associated code repository [**R notebooks for the code samples of the book "Deep Learning with R"**](https://github.com/jjallaire/deep-learning-with-r-notebooks). Course web site is https://bios691-deep-learning-r.netlify.com/. Links to non-book images and material are added to the slides. 

## Course Description

Title: "Deep Learning with R"
Course web site: https://bios691-deep-learning-r.netlify.app/
Time: Monday-Friday, June 8th - June 12th 2020, 9:00am-12:00pm  
Location: online only, Zoom (link will be provided)
Equipment Required:  A computer with Internet access
Registrant Limit: 50  
Description: This course is an introduction to deep learning theory and practice. It will cover the basics of neural network architectures, main statistical concepts behind training neural networks, and implementation aspects. The main focus will be on programming deep neural networks using TensorFlow and its Keras front-end in R, although the knowledge will also be useful for Python practitioners. The goal of this course is to build a foundation for general understanding of deep learning and hands-on implementation of main types of neural network architectures, and provide material for further development


## Site template

Site template is based on the ["Statistical Image Analysis Course for Neuroscientists"](https://github.com/laderast/stats_for_neuroscientists) repository developed by [Ted Laderas](https://laderast.github.io/). The original source is ["GSU MPA/MPP course on program evaluation and causal inference"](https://github.com/andrewheiss/evalsp20.classes.andrewheiss.com) repository by [Andrew Heiss](https://www.andrewheiss.com/)

## Site building 

```
# Build and serve site
blogdown::serve_site()
# Stop server
blogdown::stop_server()
```

## Theme

This site uses the [Academic Hugo theme](https://sourcethemes.com/academic/), with some slight template modifications found in `/assets/` and `layouts/`. The theme is included as a submodule, so when when cloning for the first time, use this command to get the theme too:

    git clone --recursive https://github.com/gcushen/hugo-academic.git

To get the theme later, use this command:

    git submodule add \
      https://github.com/gcushen/hugo-academic.git \
      themes/hugo-academic

To update to the latest version of the theme, use:

    git submodule update --recursive --remote
