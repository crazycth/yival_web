---
title: "front-task"
date: 2023-10-05T11:10:36+08:00
draft: false
language: en
featured_image: ../assets/images/featured/post-demo-featured.jpg
summary: Currently YiVal website is accessible via https://yival.netlify.app/ or  https://yival.io/. The source code is hosted on Github. To make changes to the website content, you can follow the steps below.
description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed cursus, odio nec venenatis lacinia, lacus lectus varius nisi, in tristique mi purus ut libero. Vestibulum vel convallis felis. Ut finibus lorem vestibulum lobortis rhoncus.
author: MaJunHao
authorimage: ../assets/images/global/yival_author_img.jpeg
categories: Blog
tags: ["front-task", "prompting"]
---

# How to edit YiVal website

Currently YiVal website is accessible via https://yival.netlify.app/ or https://yival.io/. The source code is hosted on Github. To make changes to the website content, you can follow the steps below.

1.  Clone the website source code to your local machine.

```Bash
git clone https://github.com/crazycth/yival_web.git
```

2. Install the necessary environment on your local machine by running the command

```Bash
brew install hugo
```

3. Start the service at your local machine to preview changes

```Bash
hugo server
```

You will see logs like below

```
Watching for changes in /Users/handsome/Github/yival_web/{archetypes,assets,content,i18n,layouts,package.json,postcss.config.js,static,tailwind.config.js}
Watching for config changes in /Users/handsome/Github/yival_web/hugo.yaml
Start building sites …
hugo v0.118.2-da7983ac4b94d97d776d7c2405040de97e95c03d+extended darwin/arm64 BuildDate=2023-08-31T11:23:51Z VendorInfo=brew


                   | EN
-------------------+-----
  Pages            | 27
  Paginator pages  |  1
  Non-page files   |  0
  Static files     | 20
  Processed images | 21
  Aliases          | 10
  Sitemaps         |  1
  Cleaned          |  0

Built in 10157 ms
Environment: "development"
Serving pages from memory
Running in Fast Render Mode. For full rebuilds on change: hugo server --disableFastRender
Web Server is available at //localhost:1313/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```

Visit the local host address in your web browser to preview the website.

4. To make changes, you can create a new branch by running the following git command, and edit files

```Bash
git checkout -b branch-name
```

5. To edit home page content, or change some configs, edit hugo.yaml. For example, you can change the text and images of the index page by editing the respective paragraph content, or change the image link.
6. To edit blog content, like adding new articles or editing existing articles, add or edit markdown files under content/posts.
7. The content changes will be reflected immediately in the local environment, if you don't stop hugo server. If you think the content is OK, you can commit the changes, push to the remote, and create a pull request (PR).
8. Once the changes are reviewed and approved, you can merge the PR into the main branch, and the CI job will automatically update the website in a few seconds to minutes. You can view the updated website at https://yival.io.

Tada! That's all the steps you need to update the YiVal website! Congratulations and looking forward to your contributions!
