---
title: Notion Element Tests
sidebar_position: 2
slug: /b2f8c9b6-8323-403c-9daf-953cc785c75f
---

import ReactPlayer from "react-player";

:::tip

This is a normal Notion Callout

:::




## Columns {#141ce921cdac4eedaf7020f0a48df810}


There should be text on the left, and an apple on the right.


<div class='notion-row'>
<div class='notion-column' style={{width: 'calc((100% - (min(32px, 4vw) * 1)) * 0.375)'}}>

A paragraph on the left.

Another paragraph.

</div><div className='notion-spacer' />

<div class='notion-column' style={{width: 'calc((100% - (min(32px, 4vw) * 1)) * 0.625)'}}>

![](./1528015832.png)



</div><div className='notion-spacer' />
</div>


## Embedded YouTube: {#3446fbc8d858450abcca30b2ff06cfab}


<ReactPlayer controls url="https://www.youtube.com/watch?v=VjINuQX4hbM" />


## Heading Links {#1497106bd62d4d55a74f261be446a7bb}


Though Docusaurus doesn’t allow linking to heading 1 within their system (see [linking to a heading 1](/oranges) still works through docu-notion if we just code it up the same way as the others.

- Link to a [heading 2](/oranges).
- Link to a [heading 3](/oranges).

## Tables {#3b9ce733e622416287188aa8d8260472}


| head 1        | head 2 |
| ------------- | ------ |
| who           | this   |
| what<br/>yeah | that   |

