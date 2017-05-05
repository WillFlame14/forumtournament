## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/WillFlame14/forumtournament/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/WillFlame14/forumtournament/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

<script>
var today = new Date();
var expiry = new Date(today.getTime() + 4 * 24 * 3600 * 1000);  
  
function junior() {
  document.cookie="eine=kleine";
  document.getElementById("levels").innerHTML = "Junior #1: Awareness by kaRi" 
  + "<br>ID: 30155662" 
  + "<br>Junior #2: The Final by TheOutLowLP"
  + "<br>ID: 30488711"
  + "<br>Junior #3: Colourful Darkness by Mattopia"
  + "<br>ID: 28324731, pass 159357";
  document.cookie="Name=" + today.toGMTString() + "; path=/; expires=" + expiry.toGMTString();
}
  
function senior() {
  document.getElementById("levels").innerHTML = "Senior #1: Eon Pulse by Vembz"
  + "<br>ID: 20522706"
  + "<br>Senior #2: Joyful Overdrive by ZielGD"
  + "<br>ID: 2641088, pass 2016"
  + "<br>Senior #3: Epitheton by HeroIC and Disp"
  + "<br>ID: 23104397, pass: 359000";
  var elem = document.getElementById('exit');
    elem.parentNode.removeChild(exit);
}
</script>    

<span id="exit">
<button name = "junior" type="button" onclick="junior()">April #1- Junior Levels</button>
<button name = "senior" type="button" onclick="senior()">April #1- Senior Levels</button>
</span>

    <p id="levels"></p>
