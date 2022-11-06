# Ezpit, Ezpie's Personal Snippets

![Ezpit license](https://img.shields.io/github/license/ishaan010/ezpit?style=for-the-badge)
![Ezpit starts](https://img.shields.io/github/stars/ishaan010/ezpit?style=for-the-badge)
![PR unaccepted](https://img.shields.io/badge/PR-accepted-brightgreen?style=for-the-badge)

## Features

---

All you need is to do to get your hands on the keyword to write some blogs at ezpie, **Ezpit!**

<!-- video -->

<!-- ------- -->

All these snippets are the most used and important ones you need to get started.

## Snippets

---

|       snippet       | renders                              |
| :-----------------: | :----------------------------------- |
|   **blog setup**    | set's up the base code               |
|  **intro section**  | create's the intro section           |
|      **text**       | ezpie's text setup                   |
|   **header text**   | main header for your blog            |
|   **new section**   | create's a new section               |
| **secondry header** | the secondry header for new section  |
|    **code link**    | adds srcipt tag for your github gist |
|      **link**       | adds ezpie custom link style         |
|       **CLI**       | adds a CLI for output                |

More whould be added in later versions

## Each Snippet's render

---

1. **blog setup**

   ```html
   <!DOCTYPE html>
   <html lang="en">

   <head>
       <!--Code by google -->
       <script async src="https://www.googletagmanager.com/gtag/js?id=G-SQB1SJPPPD"></script>
       <script>
           window.dataLayer = window.dataLayer || [];
           function gtag() { dataLayer.push(arguments); }
           gtag('js', new Date());

           gtag('config', 'G-SQB1SJPPPD');
       </script>
       <!------------------------------------------------------->

       <meta charset="UTF-8">
       <meta http-equiv="X-UA-Compatible" content="IE=edge">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <link rel="stylesheet" href="../../css/base.css">
       <link rel="icon" type="image/x-icon" href="../../asset/logo/profile.png">

       <title>ezpie - how to create a rest api using flask</title>
   </head>

   <body>
       <div class="main-body">
           <!-- Your code -->

           <!-- Ends here -->
           <section class="share">
               <div class="options">
                   <p class="text">Like the article? share it &#128516</p>
                   <a href="https://twitter.com/intent/tweet" target="_blank" class="link">
                       <img src="../../asset/logo/internet/Twitter-logo.png" alt="tweet about a ezpie blog" width="30px">
                   </a>
                   <a href="https://dev.to/new" target="_blank" class="link">
                       <img src="../../asset/logo/internet/dev-logo.png" alt="blog about a ezpie blog at dev" width="30px">
                   </a>
               </div>
           </section>
       </div>

       <footer class="foot">
           <section class="foot-main">
               <div class="detail">
                   <h1 class="head">Ezpie</h1>
                   <p><strong>Email</strong>: ezpie.co@gmail.com</p>
               </div>
               <div class="tags">
                   <h3 class="Header">Top tags</h3>
                   <ul class="links">
                       <li><a href="../../searcher/api.html" class="list-item">API</a></li>
                       <li><a href="../../searcher/docker.html" class="list-item">Docker</a></li>
                       <li><a href="../../searcher/python.html" class="list-item">Python</a></li>
                       <li><a href="../../searcher/javascript.html" class="list-item">Javascript</a></li>
                       <li><a href="../../searcher/github.html" class="list-item">GitHub</a></li>
                   </ul>
               </div>
               <div class="challenges">
                   <h3 class="Header">challenges</h3>
                   <!-- TODO add example links -->
                   <ul class="links">
                       <li><a href="#" class="list-item">Python challenges</a></li>
                       <li><a href="#" class="list-item">Java challenges</a></li>
                       <li><a href="#" class="list-item">Javascript challenges</a></li>
                       <li><a href="#" class="list-item">Golang challenges</a></li>
                   </ul>
               </div>

               <div class="Company">
                   <h3 class="Header">Company</h3>
                   <ul class="links">
                       <!-- TODO add links -->
                       <li><a href="../company/about.html" class="list-item">About</a></li>
                       <li><a href="../company/privacy.html" class="list-item">Privacy Policy</a></li>
                       <li><a href="../company/terms.html" class="list-item">Terms conditions</a></li>
                   </ul>
               </div>
           </section>
           <hr>
           <section class="info">
               <p class="copyright">Copyright (c) 2022 Ezpie</p>
               <div class="net">
                   <a href="https://github.com/ishaan010" target="_blank" class="link">
                       <img class="net-icon" src="../../asset/logo/internet/github-logo.png" alt="Ezpie github page"
                           width="30px">
                   </a>
                   <a href="https://twitter.com/EzpieCo" target="_blank" class="link">
                       <img src="../../asset/logo/internet/Twitter-logo.png" alt="Ezpie twitter page" width="30px"
                           class="net-icon">
                   </a>
                   <a href="https://dev.to/ishaan010" target="_blank" class="link">
                       <img src="../../asset/logo/internet/dev-logo.png" alt="Ezpie dev.to page" class="net-icon"
                           width="30px">
                   </a>
               </div>
           </section>
       </footer>

   </body>

   </html>
   ```

2. **intro section**

   ```html
   <section class="intro">
     <h2 class="head"></h2>
   </section>
   <hr />
   ```

3. **text**

   ```html
   <p class="text"></p>
   ```

4. **header text**

   ```html
   <h1 class="head"></h1>
   ```

5. **next section**

   ```html
   <section class="">
     <h2 class="head"></h2>
   </section>
   ```

6. **secondry header**

   ```html
   <h2 class="head"></h2>
   ```

7. **code link**

   ```html
   <script src=""></script>
   ```

8. **url link**

   ```html
   <a href="" class="link"></a>
   ```

9. **CLI output**

   ```html
   <div class="code"></div>
   ```

## Thank you ❤️

---

Thanks to you all in helping me out in [ezpie](https://github.com/ishaan010/ezpie). This extension is just for you to help me out. Thanks a lot ❤️

![contributors](https://contrib.rocks/image?repo=ishaan010/ezpie&columns=10)
