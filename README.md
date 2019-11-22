## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/data4d/test_page/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/data4d/test_page/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


#### Plotly Embed
<iframe width="900" height="800" frameborder="0" scrolling="no" src="//plot.ly/~tc922/3.embed"></iframe>

#### Tableau Emebd
<iframe seamless frameborder="0" src="https://public.tableau.com/views/NTSBAnalysis/Dashboard1?:embed=yes&:display_count=yes&:showVizHome=no" width = '650' height = '450' scrolling='yes' ></iframe>

#### Altair Embed
<head>
  <script src="https://cdn.jsdelivr.net/npm/vega@5"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-lite@3"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-embed@4"></script>
  <script src="https://d3js.org/d3.v3.min.js"></script>
</head>
<body>
<div id="vis"></div>
  <script type="text/javascript">
    var spec = {
      "$schema": "https://vega.github.io/schema/vega-lite/v2.json",
      "config": {
        "view": {
          "height": 300,
          "width": 400
        }
      },
      "data": {
        "url": "https://vega.github.io/vega-datasets/data/cars.json"
      },
      "encoding": {
        "color": {
          "field": "Origin",
          "type": "nominal"
        },
        "x": {
          "field": "Horsepower",
          "type": "quantitative"
        },
        "y": {
          "field": "Miles_per_Gallon",
          "type": "quantitative"
        }
      },
      "mark": "point"
    };
    var opt = {"renderer": "canvas", "actions": false};
    vegaEmbed("#vis", spec, opt);
  </script>
</body>


