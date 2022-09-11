---
title: "About"
permalink: "/about/"
layout: page
---

## About me
Chengsong is an extraordinary Ph.D. student who is self-motivated, passionate, independent, and productive. He is highly passionate in his research, which is focused on developing robotic technologies for perception-guided weed control in crop production. With his strong background both in agronomy and computer science, Chengsong has made outstanding progress in his research. Algorithms and hardware systems have been developed that lays the foundation for the development of fully autonomous weeding robots for challenging agricultural environments. As the first author, he has published three peer-reviewed papers as a result of his research progress and one peer-reviewed paper is in the revision stage. Chengsong has also co-authored three peer-reviewed papers and participated in the writing of several grant proposals. Additionally, Chengsong is actively involved in the agronomy and engineering community. He has made ten presentations in leading conferences during the past three years, to communicate his research findings to the broader scientific community. 


## Publications
 - **Hu, C.**, Xie, S., Song, D., Thomasson, J. A., Hardin, R., & Bagavathiannan, M. (2022). Algorithm and System Development for Robotic Micro-Volume Herbicide Spray Towards Precision Weed Management. IEEE Robotics and Automation Letters.
 - **Hu, C.**, Thomasson, J. A. Reberg-Horton, C., Mirsky, S., & Bagavathiannan, M. (2022). Modeling Realistic 3D Agricultural Vegetations Using Photometric-Based Approach and its Application to Weed Detection. Computers and Electronics in Agriculture, 198, 107020.
 - Sapkota, B., **Hu, C.**, & Bagavathiannan, M. (2022). Evaluating Cross-Applicability of Weed Detection Models Across Different Crops in Similar Production Environments. Frontiers in Plant Science, 13:837726. 
 - Kutugata, M., **Hu, C.**, Sapkota, B., & Bagavathiannan, M. (2021). Seed rain potential in late-season weed escapes can be estimated using remote sensing. Weed Science, 69(6), 653-659.
 - **Hu, C.**, Thomasson, J. A., & Bagavathiannan, M. V. (2021). A powerful image synthesis and semi-supervised learning pipeline for site-specific weed detection. Computers and Electronics in Agriculture, 190, 106423.
 - Xie, S., **Hu, C.**, Bagavathiannan, M., & Song, D. (2021). Toward Robotic Weed Control: Detection of Nutsedge Weed in Bermudagrass Turf Using Inaccurate and Insufficient Training Data. IEEE Robotics and Automation Letters, 6(4), 7365-7372.
 - **Hu, C.**, Sapkota, B. B., Thomasson, J. A., & Bagavathiannan, M. V. (2021). Influence of image quality and light consistency on the performance of convolutional neural networks for weed mapping. Remote Sensing, 13(11), 2140.
 - Zhang, Z., Zhu, H., & **Hu, C.** (2020). Hardware and Software Design for Premixing In-Line Injection System Attached to Variable-Rate Orchard Sprayer. Transactions of the ASABE, 63(4), 823-821.
 - Zhang, Z., Zhu, H., **Hu, C.**, Wei, Z., & Salcedo, R. (2020). Graphical user interface design for premixing in-line injection system attached to a variable-rate orchard sprayer. In 2020 ASABE Annual International Virtual Meeting (p. 1). American Society of Agricultural and Biological Engineers.

## Based on

- [Hyde](https://github.com/poole/hyde)
- [Minima](https://github.com/jekyll/minima)
- [Lagrange](https://github.com/LeNPaul/Lagrange)
- [Font Awesome](http://fontawesome.io/)
- [KaTeX](https://katex.org/)
- [Pygments](https://github.com/richleland/pygments-css)

## Installation (jekyll-remote-theme method)

You can use this theme with the `jekyll-remote-theme` plugin. Just create an empty repo, copy over the `index.html` file and add this to your `_config.yml`:

```yaml
remote_theme: niklasbuschmann/contrast@v2.11

plugins:
  - jekyll-remote-theme
```

Note: to enable icons you also need to copy over the `_data` folder.

## Config

Your `_config.yml` could for example look like this:

```yaml
title: "Blog Title"
author: "Blog Author"
description: "My personal blog about ... something"
permalink: /:title/
lang: "en"
excerpt_separator: "\n\n\n"
date_format: "%B %d, %Y"

# Layout

show_excerpts: true        # show article excerpts on the home page
show_frame: true           # adds a gray frame to the site
show_sidebar: false        # show a sidebar instead of the usual header

# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "index.html"}
  - {file: "README.md"}

external:                  # shows a footer with social links - for available icons see fontawesome.com/icons
  - {title: Mail, icon: envelope, url: "mailto:niklasbuschmann@users.noreply.github.com"}
  - {title: Github, icon: github, url: "https://github.com/niklasbuschmann/contrast"}
  - {title: Subscribe, icon: rss, url: "/feed.xml"}

comments:
#  disqus_shortname: ""    # see https://disqus.com/
#  isso_domain: ""         # see https://posativ.org/isso/

plugins:
 - jekyll-feed

```

## MathJax

Contrast comes preinstalled with a leightweight alternative to MathJax called [KaTeX](https://katex.org/). To display equations in a post simply set `mathjax: true` in the article's front matter.

## License

[public domain](http://unlicense.org/)

## Screenshots

![screenshot](https://user-images.githubusercontent.com/4943215/109431850-cd711780-7a08-11eb-8601-2763f2ee6bb4.png)

![screenshot](https://user-images.githubusercontent.com/4943215/109431832-b6cac080-7a08-11eb-9c5e-a058680c23a1.png)

![screenshot](https://user-images.githubusercontent.com/4943215/73125194-5f0b8b80-3fa4-11ea-805c-8387187503ad.png)
