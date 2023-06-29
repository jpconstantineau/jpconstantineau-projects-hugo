---
title: "Blog on Azure Static Web Apps"
date: 2023-04-06
summary: "This blog is hosted on Azure Static Web App for Free! Check out how!"
tags: ["Web Pages", "Github"]
skills: ["html", "markdown", "Git"]
---

Based on the great [video](https://www.youtube.com/watch?v=lqvYAI74w64) of Scott Hanselman on Youtube, this blog uses [Hugo Static Site Generator](https://gohugo.io/), [Github actions](https://github.com/features/actions) and [Azure Static Web App](https://azure.microsoft.com/en-ca/products/app-service/static/) to make the process of writing this blog and making it available.

Hugo is a great static web app generator.  Just like Wordpress, there are lots of [themes](https://themes.gohugo.io/) available.  However, unlike Wordpress, Hugo generates static web pages.  This greatly enhances security as the server that hosts your webpage only serves static pages.  There is no database or anything to break into - or get security vulnerabilities.

If you know HTML and CSS, you can easily create your own theme to generate the pages while still using [markdown](https://www.markdownguide.org/cheat-sheet/) to write the content of the pages.  GitHub uses Markdown for Readme pages.  Books have been written in Markdown. I can attest that Markdown is much easier to use than LaTex.  I wrote my PhD with LaTex.  LaTex is still better if you have lots of mathematical equations to write.  However, I wouldn't be surprised that there is a Hugo plugin/add-on for that.    

Hugo can be extended with useful graphic libraries like [Mermaidjs](https://mermaid.js.org/) to easily create graphs just by typing some code.  

You can create this graph:
```mermaid
flowchart LR
    Start --> Stop
```

With code as simple as this:

```
flowchart LR
    Start --> Stop
```


