# Tests with links

## Background

Explanation link: [https://seadude.gitbooks.io/learn-gitbook/content/chapter1/internal.html](https://seadude.gitbooks.io/learn-gitbook/content/chapter1/internal.html) 
In gitbook.yml file the root of the repository for gitbook will be ./docs. All other options that specify paths will be relative to this root folder. So if you define root as ./docs/ 
The internal link to an image should be: (.gitbook/assets/image%20%282%29.png) 


## Absolute links to images
[https://github.com/GitbookIO/theme-faq/issues/13](https://github.com/GitbookIO/theme-faq/issues/13)


* html:

 `<img src="a.png" width="640" height=360 />`
* Inline: 
* Liquid: 

## Relative links to images

![file](.gitbook/assets/image%20%282%29.png)
!\[file1\]\(.gitbook/assets/image \(2\).png\)
![Image](.gitbook/assets/image%20%282%29.png)
* html:
* Inline: 
* Liquid: 
{% embed url="https://app.gitbook.com/@bcodmo/s/public\_resources/04\_data\_submission" caption="" %}


## Rekative links to gitbook headers
indirect[ link](07_tutorials.md) to this gitbook?



