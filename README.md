<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
# Geographic Classification of Cuisine Recipes

<img src = "CuisineFromAroundTheWorld.png">

## Project proposal
### Group members: Jinhyeun Kim, Jianyuan Zhai, and Youngjo Kim*

### Introduction
As a part of cultural globalization, we are exposed to various types of cuisines every day. Cuisines are different across different countries, and are primarily affected by the geographic conditions, such as local climate, religion and trade. We may know from past experience that ingredients and food preparation methods are the key factors distinguishes one cuisine from others. However, learning thousands recipes around the world could be a very hard task for human brain. In this project, we want to build a machine learning classifier that reads a recipe and classifies the origin of the recipe.

### Methods
The project will consist of two parts: 
1. Data acquisition and preprocessing and
2. modeling

In the first part, we will need collect a large amount of recipes from recipe websites, such as <a href="https://www.allrecipes.com/" target="_blank">allrecipes.com</a> and <a href="https://www.allrecipes.com/" target="_blank">chowhound.com</a>, and preprocess these recipes into a concise data set. These recipe data will be labeled by their origins. We propose to use supervised learning methods$^1$, such as Support Vector Machine2, Logistic Regression and Artificial Neural Networks3, to build the recipe classifier. We will use a k-fold cross-validation process to find the best parameters of these model. All different types of classifiers will be tested on the same validating set. 

### Expected results
We hope to build a classifier that can accurately find the origin of the recipe. We will compare different supervised learning methods on the precision and accuracy of the classification. We will also identify the most common ingredients and preparation methods shared among the recipes from the same region. 

### Discussion
We believe this is a project that can benefit people who love food and are willing to learn about the culture behind different recipes.





You can use the [editor on GitHub](https://github.com/Youngjo-Kim/CX4240_project_2019/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Youngjo-Kim/CX4240_project_2019/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
