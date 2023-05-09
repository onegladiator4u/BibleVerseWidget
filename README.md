# Notion Random Bible Verse
This is a widget for [Notion](https://notion.so). You can insert the URL of this repository in an [embed item](https://www.notion.so/help/embed-and-connect-other-apps).

## Settings
On the right bottom corner, you can change settings. They are developed in a way to integrate this widget perfectly.


## Add a different source
You can add a different source for random Bible Verse. This source must be a JSON file hosted somewhere.
As an example you can use [Github Gist](https://gist.github.com/).

The valid JSON file must be in this format:
```json
[
  {
    "verseref": "Bible Verse Reference",
    "content": "Bible Verse Content"
  },
  {
    "verseref": "Bible Verse Reference",
    "content": "Bible Verse Content"
  }
]
```
## Bold Content
To make words of Bible Verse Content bold use '<strong>' tag. For example.
```
"verseref": "Genesis 1:27–28Aa",
    "content": "So <strong>God </strong>created man <strong>in his own image</strong>, in the <strong>image of God</strong> he created him; male and female he created them. And God blessed them."
  }
```

Here is an example for [my gist](https://gist.github.com/onegladiator4u/ac7405d0374bfb8917a4d795454bc248):
## How to Use it?
You have to add the url of your JSON file with parameter `f` into query parameters.
If you're using a gist, make sure you use the raw version. If you update raw file, the file url will change. So update the file url.

Use this code in Notion to embed
```
https://onegladiator4u.github.io/Notion-Bibleverse/?f=https://raw.githubusercontent.com/onegladiator4u/Notion-Bibleverse/main/Bible-verses.json
```
