# Sparta Global Medium Articles

This repo contains articles written by students from [Sparta Global](http://spartaglobal.com). It is available to view at https://spartaglobal.github.io/sparta-articles/. 

## Adding an Article

To add an article to this project:

1. Fork the repo to your GitHub account.
2. Add a new object to `articles.json` (details below).
3. Add a new entry to `index.html` (details below).
4. Open a pull request to the original repo.

### The `articles.json` File

To add your article to the `articles.json` file, add a new object to the bottom of the array in the following form:

```json
{
  "author": "Danny Smith",
  "course": "sdet-7",
  "title": "DigitalOcean, DNSimple and Terraform: A very short introduction",
  "url": "https://medium.com/somethingorother"
}
```

Your course ID is the same as the name of your slack channel, all lowercase.

### The `index.html` File

To add your article to the `index.html` file, add a new list item to the list for your course in the following format:

```html
<li>
  <a href="https://medium.com/somethingorother">DigitalOcean, DNSimple and Terraform: A very short introduction</a> by <i>Danny Smith</i>
</li>
```

If your course has not yet been added, add a suitably formatted section.
