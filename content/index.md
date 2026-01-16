---
title: Сергей Лето
tags:
  - main
---
[[Some text link]]

## [[МТС IoT Hub]]
[![[img/iot-cover.png]]](<МТС IoT Hub.md>)



Test page of Quartz

Some changes

![[img/img.png|100]]
# Callouts:
[Use callouts - Obsidian Help](https://help.obsidian.md/How+to/Use+callouts)


> Standart callout

Примеры "коллаутов":

> [!note] note

> [!abstract] abstract, summary, tldr

> [!info] info

> [!todo] todo

> [!tip] tip, hint, important

> [!success] sucess, check, done

>[!question] question, help, faq

>[!warning] warning, caution, attention

>[!failure] failure, fail, missing

>[!danger] danger, error

>[!bug] bug

>[!example] example

>[!quote] quote, cite


---

> [!INFO] > Some title here

> [!INFO]- 
> Some
>> Some more

> [!question] Can callouts be nested? 
> > [!todo] Yes!, they can. 
> > > [!example] You can even use multiple layers of nesting.


```markdown
> [!INFO]
> Here's a callout block.
> It supports **markdown**, [[Internal link|wikilinks]], and [[Embed files|embeds]]!
> ![[img.png]]
```

> [!INFO]
> Here's a callout block.
> It supports **markdown**, [[Internal link|wikilinks]], and [[Embed files|embeds]]!



# Images:
[Format your notes - Obsidian Help](https://help.obsidian.md/How+to/Format+your+notes)

```md
![Einstein](https://upload.wikimedia.org/wikipedia/en/8/86/Einstein_tongue.jpg)
```

Resized to 200px wide
```md
![Einstein|200](https://upload.wikimedia.org/wikipedia/en/8/86/Einstein_tongue.jpg)
```


![Einstein|200](https://upload.wikimedia.org/wikipedia/en/8/86/Einstein_tongue.jpg)

```md
![[img.png]]
```

```md
![[img.png|200]]
```



# Embed
[Embed Files - Obsidian Help](https://help.obsidian.md/How+to/Embed+files)

```md
[[filename.png]]
```

You can embed a PDF file in your notes with the same syntax. Additionally, you can write `![[My File.pdf#page=number]]` to open to that specific page of the PDF directly.

Obsidian recognizes the following file formats right now:

1.  Markdown files: `md`;
2.  Image files: `png`, `jpg`, `jpeg`, `gif`, `bmp`, `svg`;
3.  Audio files: `mp3`, `webm`, `wav`, `m4a`, `ogg`, `3gp`, `flac`;
4.  Video files: `mp4`, `webm`, `ogv`, `mov`, `mkv`;
5.  PDF files: `pdf`.

All these types of files can be embedded in a note.

Note that audio and video formats support depend on the availability of codecs on your device.

You can resize images using the following syntax:

For markdown images, use `![AltText|100x100](https://url/to/image.png)`

For embeds, use `![[image.png|100x100]]`

To have the image scale according to its aspect ratio, omit the height `![[image.png|100]]`


# Tables
## Creating tables

```
| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Item 1 | Item 2 | Item 3 |
| Item 4 | Item 5 | Item 6 |
```

| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Item 1 | Item 2 | Item 3 |
| Item 4 | Item 5 | Item 6 |

```
| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| | | |
| | | |
```

| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| | | |
| | | |

## Aligning

```
| Header 1 | Header 2 | Header 3 |
| -------: | :------: | :------ |
| Item 1 | Item 2 | Item 3 |
| Item 4 | Item 5 | Item 6 |
```

| Header 1 | Header 2 | Header 3 |
| -------: | :------: | :------ |
| Item 1 | Item 2 | Item 3 |
| Item 4 | Item 5 | Item 6 |

## Formatting

```
| Header 1 | Header 2 | Header 3 |
| :------: | :------: | :------: |
| **Bold** | *Italic* | ~~Strikethrough~~ | 
| ![[muologo.jpg]] | [Link](https://obsidian.md) | `<div> code! </div>` |
```


| Header 1 | Header 2 | Header 3 |
| :------: | :------: | :------: |
| **Bold** | *Italic* | ~~Strikethrough~~ | 
| ![[muologo.jpg]] | [Link](https://obsidian.md) | `<div> code! </div>` |


