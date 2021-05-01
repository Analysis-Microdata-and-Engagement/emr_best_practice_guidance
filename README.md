# EMR Best Practice Guidance

[![build_publish](https://github.com/Analysis-Microdata-and-Engagement/emr_best_practice_guidance/actions/workflows/build_publish.yaml/badge.svg?branch=master)](https://github.com/Analysis-Microdata-and-Engagement/emr_best_practice_guidance/actions/workflows/build_publish.yaml)

[View Here](https://analysis-microdata-and-engagement.github.io/emr_best_practice_guidance/)

The EMR Best Practice Guidance document. 

## Issues or Comments

If you have any issues or comments then please add them to the project. All feedback is welcome. Create a new issue and leave your comments. If you would like some help with raising issues on GitHub then you can look at [Issues](https://guides.github.com/features/issues/). 

If you are not confortable with using GitHub then feel free to contact a product owner directly by email or other method. 

## Contributing

The website is automatically built and deployed using GitHub Actions. You can therefore make changes using the GitHub editor. Click on the desired file and select in the top right hand side edit this file. 

> Note the deployed site is ALWAYS built by the CI process. Any local builds are not used. 

To see changes before they are published you need to clone and build locally. 

```bash
git clone https://github.com/Analysis-Microdata-and-Engagement/emr_best_practice_guidance.git
```

Open emr_guidance.Rproj in Rstudio. 

```r
# Install Dependencies
install.packages(c("govdown", 'fontawesome'))

rmarkdown::render_site(encoding = 'UTF-8')
```

You can also use the build tab in the top right pane. Select Build Website.

The master branch is the deployed branch. You are not able to merge directly into master. To contribute please create a new branch and when you are finished create a pull request and assign one of the EMR Guidelines product owners. We will review and merge into master, where your changes will be deployed.  

## Format

The document uses govdown for styling. Further details can be found at [govdown](https://ukgovdatascience.github.io/govdown/)

Fontawesome icons are used made available through the R package `fontawesome`. Go to [FontAwesome](https://fontawesome.com/icons?d=gallery&p=2&m=free). Make sure you select only Free!
Then load in any RMarkdown script using `r fontawesome::fa("laptop-code")` with laptop-code being an icon name. 










