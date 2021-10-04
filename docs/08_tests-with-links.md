# Tests with links

## Background

Explanation link: [https://seadude.gitbooks.io/learn-gitbook/content/chapter1/internal.html](https://seadude.gitbooks.io/learn-gitbook/content/chapter1/internal.html) In gitbook.yml file the root of the repository for gitbook will be ./docs. All other options that specify paths will be relative to this root folder. So if you define root as ./docs/ The internal link to an image should be: \(.gitbook/assets/image%20%282%29.png\)

Clickable image in gitbook with markdown: [https://emekauche.medium.com/creating-clickable-images-on-gitbook-958069b13208](https://emekauche.medium.com/creating-clickable-images-on-gitbook-958069b13208)

**Markdown syntax** for links and images:

* link to file: `[displayname](link)` 
* display picture: `![displayname](link)`

## Absolute links to images

* **markdown - online image:**

  [link to picture](https://source.unsplash.com/69n54RVh4tE/1920x1080)

  ![picture](https://source.unsplash.com/69n54RVh4tE/210x100)

* **markdown - github images:**

  [image\_on\_github](https://github.com/BCODMO/documentation_public/blob/main/docs/.gitbook/assets/image%20%282%29.png)

  ![image\_on\ github](https://github.com/BCODMO/documentation_public/blob/main/docs/.gitbook/assets/image%20%282%29.png), this link does not get viewed in gitbook, why is that?

* **html:**
<img src="a.png" width="640" height=360 />


## Relative links to images

As indicated in the gitbook.yaml file, the root of the documentation is ./docs/ folder. Relative links need to start from that folder.

Unfortunately at this time, images must be scaled and centered using HTML as Gitbooks markdown parser does not support image manipulation.

* **markdown**

  ![file](.gitbook/assets/image%20%282%29.png) 

  ![file1](.gitbook/assets/image%20%282%29.png) 

  ![Image](.gitbook/assets/image%20%282%29.png) 

* **relatove link Pasted directly in gitbook:**

![](.gitbook/assets/image%20%283%29.png)

!\[\]\(.gitbook/assets/image%20%282%29.png\) : typed in gitbook doesn't work \(gitbook escapes the special characters?\)

* **html:**

&lt;img src=".gitbook/assets/image%20%282%29.png" alt="Test Pic not Showing" title="Test Pic" width="150" height="100" /&gt;


{% embed url="https://app.gitbook.com/@bcodmo/s/public\_resources/04\_data\_submission" caption="" %}
The above link works directly in github, but does not translate in pure markdown or a markdown parser

#### Rekative links to gitbook headers

indirect [link](07_tutorials.md) to this gitbook?
reads as `[link](07_tutorials.md)` in markdown


