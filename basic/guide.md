---
title: 贡献指南
authors:
  - 徐晨曦 (@xsun2001)
date: 2020-10-11
---

# Guide of Tsinghua Survive Guide

## Introduction to Markdown

### WHAT is Markdown

> Markdown是一种轻量级标记语言，创始人为约翰·格鲁伯。它允许人们使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML（或者HTML）文档。这种语言吸收了很多在电子邮件中已有的纯文本标记的特性。
>
> 由于Markdown的轻量化、易读易写特性，并且对于图片，图表、数学式都有支持，目前许多网站都广泛使用Markdown来撰写帮助文档或是用于论坛上发表消息。如GitHub、Reddit、Diaspora、Stack Exchange、OpenStreetMap、SourceForge、简书等，甚至还能被使用来撰写电子书。
>
> Ref: [Wikipedia](https://zh.wikipedia.org/wiki/Markdown)

### WHY Markdown

- Easy to Learn
  - HTML?

    ```html
    <div role="main">
            <div class="section">
                <h1 id="welcome-to-mkdocs">Welcome to MkDocs</h1>
                <p>For full documentation visit <a href="https://www.mkdocs.org">mkdocs.org</a>.</p>
                <h2 id="commands">Commands</h2>
                <ul>
                <li><code>mkdocs new [dir-name]</code> - Create a new project.</li>
                <li><code>mkdocs serve</code> - Start the live-reloading docs server.</li>
                <li><code>mkdocs build</code> - Build the documentation site.</li>
                <li><code>mkdocs -h</code> - Print help message and exit.</li>
                </ul>
                <h2 id="project-layout">Project layout</h2>
                <pre><code>mkdocs.yml    # The configuration file.
                        docs/
                        index.md  # The documentation homepage.
                            ...       # Other markdown pages, images and other files.
                </code></pre>
                <h2 id="math-test">Math test</h2>
                <p>
                <script type="math/tex; mode=display"> x = \dfrac{-b\pm\sqrt{b^2-4ac}}{2a} </script>
                </p>
                <h2 id="image-test">Image test</h2>
                <p><img alt="THU" src="img/index/1.jpg" /></p>
            </div>
        </div>
    ```

  - Markdown!
  
    ```markdown
    # Welcome to MkDocs

    For full documentation visit [mkdocs.org](https://www.mkdocs.org).

    ## Commands

    * `mkdocs new [dir-name]` - Create a new project.
    * `mkdocs serve` - Start the live-reloading docs server.
    * `mkdocs build` - Build the documentation site.
    * `mkdocs -h` - Print help message and exit.

    ## Project layout

        mkdocs.yml    # The configuration file.
        docs/
            index.md  # The documentation homepage.
            ...       # Other markdown pages, images and other files.

    ## Math test

    $$ x = \dfrac{-b\pm\sqrt{b^2-4ac}}{2a} $$

    ## Image test

    ![THU](img/index/1.jpg)
    ```

- Functionality
- Great community resource and integration
  - MkDocs
  - GitHub
  - ReadTheDocs
  - MathJax & LaTeX
- Focus on Content, not Format
  - Office Word? Difficult to unify the format.
  - NO CSS

    ```css
    *{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}article,aside,details,figcaption,figure,footer,header,hgroup,nav,section{display:block}audio,canvas,video{display:inline-block;*display:inline;*zoom:1}audio:not([controls]){display:none}[hidden]{display:none}*{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}html{font-size:100%;-webkit-text-size-adjust:100%;-ms-text-size-adjust:100%}body{margin:0}a:hover,a:active{outline:0}abbr[title]{border-bottom:1px dotted}b,strong{font-weight:bold}blockquote{margin:0}dfn{font-style:italic}ins{background:#ff9;color:#000;text-decoration:none}mark{background:#ff0;color:#000;font-style:italic;font-weight:bold}pre,code,.rst-content tt,.rst-content code,kbd,samp{font-family:monospace,serif;_font-family:"courier new",monospace;font-size:1em}pre{white-space:pre}q{quotes:none}q:before,q:after{content:"";content:none}small{font-size:85%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sup{top:-0.5em}sub{bottom:-0.25em}ul,ol,dl{margin:0;padding:0;list-style:none;list-style-image:none}li{list-style:none}dd{margin:0}img{border:0;-ms-interpolation-mode:bicubic;vertical-align:middle;max-width:100%}svg:not(:root)
    ```

### Writing Tools

1. [Visual Studio Code](https://code.visualstudio.com/)
   - Pros:
     - Almighty editor
     - Git & GitHub Integration
   - Cons:
     - Almighty editor
     - Need configuration
2. [Typora](https://typora.io/)
   - Pros:
     - Really lightweight
     - Out of the box
     - Focus on Markdown and better writing experience
   - Cons:
     - No Git integration

### Let's write Markdown

## Introduction to Git & GitHub

### WHAT is Git & GitHub

> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
>
>Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.
>
> Ref: [Git SCM](https://git-scm.com/)

> GitHub, Inc. is an American multinational corporation that provides hosting for software development and version control using Git. It offers the distributed version control and source code management (SCM) functionality of Git, plus its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, continuous integration and wikis for every project.
>
> Ref: [Wikipedia](https://en.wikipedia.org/wiki/GitHub)

### WHY Git & GitHub

- The best multi-person collaboration solution in the world

### Get Started with GitHub and our workflow

1. Register a Github account
2. Fork our main repository
3. Write your markdown document
4. Push or Add your document to the repo in your account
5. Create a Pull Request (PR)
6. Waiting for reviewing
7. Accepted!
