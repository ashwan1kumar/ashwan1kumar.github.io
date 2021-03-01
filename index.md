## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ashwan1kumar/ashwan1kumar.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

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

<!DOCTYPE html>
<meta content="text/html;charset=utf-8" http-equiv="Content-Type">
<meta content="utf-8" http-equiv="encoding">
<script>
    function patronus()
    {
        var search = document.getElementById('query').value;
        var prefix = "https://www.ecosia.org/search?q=";
        prefix = prefix + search;
        // alert(prefix);
        setTimeout(function(){window.location = prefix;}, 0);
    };
</script>
<style>
    .image
    {
        width:300px;
        height:300px;
        padding-top: 150px;
        /* align-items: center; */
    }
    #center
    {
        text-align: center;
    }
</style>
<title>Ecosia</title>
<body>
    <div id="center">
        <img class="image" src="Ecosia_logo.png">
    </div>
    <form>
        <div id="center" style="padding-top: 50px; ">
            <input type="Text" required id="query" placeholder="Search the web to plant trees ..." style="width:1000px; height:45px;border-radius: 10px;"> 
            <button type="Submit" style="width: 100px; height:50px; border-radius: 10px;" onclick="patronus()"/>Search</button>
        </div>
    </form>
</body>
### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ashwan1kumar/ashwan1kumar.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
