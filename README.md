# markpedia

Wikipedia in Markdown format:

1. clone the project [github.com/rognoni/markpedia](https://github.com/rognoni/markpedia)
2. create a new MediaWiki markup file, for example [wiki/Anti-pattern.wiki](https://en.wikipedia.org/w/index.php?title=Anti-pattern&action=edit)
3. execute the command `pandoc -s Anti-pattern.wiki -o Anti-pattern.md`
4. edit style and content, for example add `.md` extension to the wiki-links
5. push and browse [https://raw.githubusercontent.com/rognoni/markpedia/master/wiki/Anti-pattern.md](https://monastic.netlify.com/#/url/https://raw.githubusercontent.com/rognoni/markpedia/master/wiki/Anti-pattern.md)
6. make a pull request
