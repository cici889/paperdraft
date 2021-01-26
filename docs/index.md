## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/cici889/paperdraft/edit/main/docs/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block





- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes


```{r}
# We divided the dataset into 60% training data set and 40% test data set
set.seed(4000200)
train_rows <- sample(rownames(sample5), dim(sample5)[1]*0.6)
sample6_train <- sample5[train_rows, ]
valid_rows <- setdiff(rownames(sample5), train_rows)
sample6_valid <- sample5[valid_rows, ]
```



Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/cici889/paperdraft/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact
https://acorn.utoronto.ca/sws/#/
Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
