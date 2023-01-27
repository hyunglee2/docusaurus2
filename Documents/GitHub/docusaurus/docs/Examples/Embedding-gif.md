---
title: Embedding gif
sidebar_position: 5
slug: /049d5bb1-f7d1-47a2-b23b-8f2ea3f48fc9
---



If you embed a gif in notion, it should be embedded in Docusaurus


## Imgur {#8af84e6e17f14c4680f08ee54160f365}


![](./1607379524.gif)


## Giffy,  {#b00b995890fd4793ac7cedf73614df24}


![](./705447076.gif)


When it detects an embedded gif, docu-notion does the following:

- Adds a `import GifPlayer from "react-gif-player";` to the markdown.
- Inserts html like `<GifPlayer gif="https://media.giphy.com/media/VhiAuDYHkNPydiNnOs/giphy.gif" />`

:::info

If your site is not based on `docu-notion-sample-site`, you may need to add react-gif-player to your Docusaurus project:
`yarn add react-gif-player` or `npm i react-gif-player`

:::



