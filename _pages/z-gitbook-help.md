---
title: gitbook help
date: 2024-06-22
layout: post
---

More information see: [Jekyll Git Book theme](https://github.com/sighingnow/jekyll-gitbook) 

### Scale images on page

```
<img src="https://user-images.githubusercontent.com/link-to-your-image.png" width="100%" />
```

### Add non-breaking space: 

```
&nbsp;
```

### Buttons Open New Tab

<button onclick="buttonFunc()">w3schools.com</button>
<script>
function buttonFunc() {
  window.open("link");
}
</script>


### PDF Containers

```
<div class="pdf-container">
    <iframe src="/assets/mc-graw-accounting-course/biz.entities.test.pdf#zoom=FitH" height="600" width="100%" allowFullScreen="true">
    </iframe>
</div>
```

### 3 Blocks


```
> Green Tip
{: .block-tip }
```

```
> Yellow Warning
{: .block-warning }
```

```
> Red Danger
{: .block-danger }
```

```
| :warning: White box :warning: |
|:---------:|
| White box |
```


### Emojis

https://gist.github.com/rxaviers/7360908

https://github-emoji-picker.rickstaa.dev/

### Links

```
[Absolute link to a page](https://mcc-us.github.io/2020-02-28-sample-markdown/)
```

```
[Relative link to a section inside a page](#local-urls)
```


### Bookmark Links on the Same Page

If you want to link to a heading on the same page, first add an ID tag to the header like this:

```
## Headings with ID Tags {#someIdTag}
```

Then reference it with a normal Markdown link:

```
[Some link](#someIdTag)
```



### Pictures

```
![lion](/assets/img/lion_head-144x144.png)
```

Images can also be centered!

```
![lion](/assets/img/lion_head-144x144.png){: .mx-auto.d-block :}
```

|ImageTitle|
|:-:|
|![abc](/assets/a.png)|

### Code chunks 

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

### Tables

```
| nameA | nameB | nameC |
| :---: |:----- | :---- |
| A1    | B1    | C1    |
```

```markdown
<div class="table-wrapper" markdown="block">
|title1|title2|title3|title4|title5|title6|title7|title8|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|1|2|3|4|5|6|7|8|
</div>
```

### Dictionary  

```
<dl>
  <dt>QBO</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Term 2</dt>
  <dd>This is one definition of the second term.</dd>
  <dd>This is another definition of the second term.</dd>
</dl>
```
