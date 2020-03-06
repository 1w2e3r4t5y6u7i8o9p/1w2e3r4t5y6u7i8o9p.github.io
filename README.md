# how to


## how to delete content

## general how to do changes

**create file**

![CREATE FILE](https://media.giphy.com/media/f5uxCSmj8PkNF97mBR/giphy.gif)

**delete file**

![DELETE FILE](https://media.giphy.com/media/LQtwESLIKOR9uZA5Jk/giphy.gif)

**upload file**

![UPLOAD FILE](https://media.giphy.com/media/gjToXYkwFLtjDhJkwv/giphy.gif)

**you wanna delete a whole gallery?**

1. delete all images asscociated to said gallery in [assets folder](assets/gallery_images/)
2. delete all files associcated to said gallery in [posts folder](_posts/)

**wanna delete a single image?**

1. delete all **image** asscociated to said gallery in [assets folder](assets/gallery_images/)
2. delete all **file** associcated to said gallery in [posts folder](_posts/)


## How to create content

* prepare pictures for upload
* prepare descriptions for images and titles
* prepare theme title

### upload image files

**see above for how to upload file**

upload images to [/assets/gallery_images/](/assets/gallery_images/)

**filename consist of**

create a file: `/assets/gallery_images/aesthetics_1.jpg`

* **theme_name**: `/assets/gallery_images/`**aesthetics**`_1.jpg`
* **number**: `/assets/gallery_images/aesthetics`**_1**`.jpg`

### 2. create theme page


**filename consist of**

create a file: `_posts/2019-02-01-headtails.markdown`

1. date: **2019-02-01**`-headtails.markdown`(use this to group things that belong together, its not a real date just a category, has to be unique)
2. name: `2019-02-01-`**headtails**`.markdown`

**put this in the file (stupid fuck):**

```markdown

---
title: "meditations on modernity"
layout: gallery
date: 2019-03-12 17:00
image: /assets/gallery_images/head_tails_1.jpg
headerImage: false
gallery: true
galleryTitle: "meditations on modernity"
hidden: true # don't count this post in blog pagination
description: ""
category: project
author: sort
externalLink: false
---

```

* **galleryTitle** and **title** has to be the same
* **image** refers to the image used as a picture for this theme site

### 3. create image for theme page

**filename consist of**

create a file: `_posts/2019-02-02-headtails_1.markdown`

1. date: **2019-02-01**`-headtails.markdown`(use this to group things that belong together, its not a real date just a category, has to be unique)
2. name: `2019-02-01-`**headtails**`.markdown`
2. number: `2019-02-01-headtails`**_1**`.markdown`

**put this in the file (stupid fuck):**

```markdown

---
title: "hoved/hale/head/tails - a werewolf"
layout: default
date: 2019-02-08 22:10
image: /assets/gallery_images/head_tails_1.jpg
headerImage: false
projects: false
galleryTitle: "meditations on modernity"
hidden: true # don't count this post in blog pagination
description: "2020 oil/acrylics"
category: project
externalLink: false
---


```

* **galleryTitle** has to be the same as one in the theme page you made [example](_posts/2019-02-01-headtails.markdown)
* **image** is the image you want displayed
* **description** is the undertitle of the image (caption)
* **title** is the title of the image


**MERRY CHRISTMAS EVERYBODY**