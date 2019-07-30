# sketch-lib-rss-sample

xml URL:

https://raw.githubusercontent.com/jiazhewang/sketch-lib-rss-sample/master/sampleLib.xml

code in Sketch plugin:

```javascript
Library.getRemoteLibraryWithRSS(
  'https://raw.githubusercontent.com/jiazhewang/sketch-lib-rss-sample/master/sampleLib.xml',
  (err, library) => {
    if (err) {
      // failed
    }
  }
)
```

----

xml encoded URL:

https%3A%2F%2Fraw.githubusercontent.com%2Fjiazhewang%2Fsketch-lib-rss-sample%2Fmaster%2FsampleLib.xml

Sketch schema URL:

sketch://add-library?url=https%3A%2F%2Fraw.githubusercontent.com%2Fjiazhewang%2Fsketch-lib-rss-sample%2Fmaster%2FsampleLib.xml
