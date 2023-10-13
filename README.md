# ChrisMok's GPU Server Documentation
Welcome to ChrisMok's GPU server documentation! If you are interested in the documentation, please refer to the website: https://github.com/ChrisMokServer/ChrisMokServer-Docs


## Introduction

+ All documentation is written in markdown which makes it easy to contribute to the docs (see below)
+ Website is rendered with mkdocs and the mkdocs-material theme and is hosted on GitHub pages
+ New commits to main are automatically built and deployed to the gh-pages branch


## Contributing

You are welcome to open a pull request for changes to the documentation. If you want to make larger changes and you would like to see how they would appear on the rendered site, you can run mkdocs locally.

```
# Install dependencies
conda create -n server-docs -c conda-forge python=3.8 mkdocs mkdocs-material
conda activate cluster-docs

# Build and serve documentation

git clone https://github.com/ChrisMokServer/ChrisMokServer-Docs
cd ChrisMokServer-Docs

mkdocs serve
```


## Reference
+ https://github.com/IKIM-Essen/ClusterDocs
