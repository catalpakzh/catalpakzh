---
title: Some Questions When Built Website
author: Kang Zihao
date: "2024-10-12"
slug: questions-when-built-website
---

> When I built my website, I countered some questions. Therefore, I plan to write down it as a summary.

## Start

This step is easy. I followed the book called [Blogdown](https://bookdown.org/yihui/blogdown/) and built my website quickly. The one thing you should focus on is picking a theme that you like. You can deploy your website on the [Netlify](https://www.netlify.com/). We finish the preliminary construction of the website. 

## Adjustment according to your preference 

All things have been set by the template initially. But you can change some documents to correct what you want. You will see the <u>theme</u> folder and <u>config.yaml</u> document which are the most important things I think in the first catalog. In the theme folder, you can correct or add some code in the <u> style.css</u> to change the appearance of your website. You need some basic knowledge about CSS, but you can try to change the code step by step and see what will happen (That's what I did, although it's a little bit dumb, you can know what you have done to your website) and you can also use the AI to help you. Then, the <u>font.css</u> is about the font style. I copied the fond.css code from [yihui's githb](https://github.com/yihui), it is an elegant font style I think. About <u>config.yaml</u> document, you just add your personal information according to the template.

## Some questions I met

How to add a catalog for each article? I spent some time looking for the answer. Finally, I found that there was a html document under layout folder caller <u>single.html</u>. Using a notebook open it, and you can write down your code there to add a catalog which may also be entitled <u>toc</u> in programming. 

How to use mathematical expressions in `.md` files? Maybe you use R markdown to write an article, you will not counter this question. But if you use markdown, you can find that you can't use mathematical expressions in `.md` files. There are head_custom.html and foot_custom.html files under the <u>layout</u> folder. You can write the `javascript` type document in these two files to achieve some functions. About mathematical expressions, you can read [The Best Way to Support LaTeX Math in Markdown with MathJax](https://yihui.org/en/2018/07/latex-math-markdown/) as a reference.

How to adjust the size of figures? Using the html script, for example:
```
<img src="/img/sea.jpg" style="max-width:15%;min-width:40px;float:right;" alt="Kang Zihao" />
```
It seems that markdown can't change the size.

How to include a picture on the website? Notice the <u>static</u> folder which is used to store the pdf, images, and so on. Put your photos in the static/img, just create a folder to store your photos under the static folder, no matter the name of the fold, but ensure you can find it by yourself. 




Actually, I don't have any knowledge of HTML or CSS before. Therefore, I am still exploring the function of the website. Using AI as an assistant to help can improve your efficiency. Reading other's websites is also a good method to polish your website. But I would say, don't spend too much time adjusting your website appearance. The content is more important.


