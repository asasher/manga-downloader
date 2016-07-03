# manga-downloader
A web scrapping utilty for downloading mangas for manga reader websites.

Supports resume. Stores progress in a file called .mget.

## Usage

```
mget <base url> <page url> <image css> <next css> <naming regex>

base url: 
e.g 'readmanga.com'

page url: 
e.g 'some-manga/12/1.html'

image css: 
css selector for image 
e.g '.img-holder img'

next css: 
css selector for next link 
e.g '.nav a.next'

naming regex: 
regex to extract name and chapter from url 
e.g '[\w:]+\/\/[\w\.]+\/(?P<chapter>.+)\/(?P<page>.+)\.html'
```
