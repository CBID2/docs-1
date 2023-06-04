﻿---
Title: 'src'
Description: 'An HTML attribute used to specify the location of a digital resource.'
Subjects:
  - 'Web Development'
  - 'Web Design'
Tags:
  - 'Attributes'
  - 'Elements'
  - 'Style'
CatalogContent: 
   - 'learn-html'
  - 'paths/front-end-engineer-career-path'
---

The  **`src`** attribute is  used to specify the location of a digital source, which is typically a URL. It is required for HTML elements like [`<img>`](https://www.codecademy.com/resources/docs/html/elements/img) so that they can appear on a website or application. 

## Syntax

```pseudo
<element  src="url">
```

`src` can also be used in the following elements :

| Direction | Description                                                                                                          |
| --------- | -------------------------------------------------------------------------------------------------------------------- |
| [`<audio>`](https://www.codecademy.com/resources/docs/html/elements/audio)    | Embeds sound files on websites and applications                                                         |
| [`<input>`](https://www.codecademy.com/resources/docs/html/elements/input)     | Creates interactive textboxes for online forms.                                                                          |
| [`<script>`](https://www.codecademy.com/resources/docs/html/elements/script)    | Embeds Javascript and other executive code or data into a HTML file . |
| `<track>`( | Specifies the subtitles and closed captions for  `<audio>` and  `<video>` elements. |
| [`<video>`](https://www.codecademy.com/resources/docs/html/elements/video)  | Embeds movie clips or other video sources into an HTML file. |

## Example #1: Image 
The snippet below shows a logo being inserted into an HTML file:  

```html
<img src="logo.png" alt="Codecademy logo" />
```

> **Note:** When using online images or images from the folders in an IDE workspace, always add `alt` text at the end of the `<img>`  element just in case the browser has trouble finding them.
## Example #2: Video

The snippet below shows a [video](https://www.codecademy.com/resources/docs/html/videos) being inserted into an HTML file: 

```html
<video source controls width="200" src="https://youtu.be/0QHaxrUkSE"  type="youtube"/>
```

 