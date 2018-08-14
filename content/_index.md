---
title: "Home"
date: 2018-08-13T21:38:52+08:00
lastmod: 2018-08-13T21:41:52+08:00
menu: "sidebar"
weight: 0
toc: false

---

# Overview

This website summarizes the work I've completed as a student working with the [Processing Foundation](https://processingfoundation.org/) through [Google Summer of Code 2018](https://summerofcode.withgoogle.com/).  

First of all, I’d like to say HUGE Thanks to the Processing Foundation and to Google for making Google Summer of Code a reality for students like me. Specifically I’d like to thank my mentor [Gottfried Haider](https://twitter.com/mrgohai) for spending countless hours working with me on the style and content of [Processing for Pi](http://pi.processing.org/) website and for giving me a new perspective on open source community. I feel like I’ve grown a lot as an engineer and as a contributor to the mission of Processing Foundation.

Google Summer of Code 2018 ran from May 14 to August 14 2018. In these three months I've worked with my mentor to create a brand new website and wrote a few comprehensive tutorials for using [Processing](http://processing.org/) (software) on Raspberry Pi single board computers.

The result of my work is [hosted on Github](https://github.com/processing/processing-pi-website/commits/master?author=msurguy) and is accessible at [Pi.processing.org](http://pi.processing.org).

## History and Context

In April 2018 I've applied to work with the Processing Foundation by submitting a project proposal (you can read it [here](https://docs.google.com/document/d/1SShi0Rjh6jHl6s_BIB5TBxKEygU1Knr5GQ1pwikIji8/edit)) for a set of tutorials covering various aspects of running Processing on Raspberry Pi.

The proposal was focused around developing comprehensive tutorials that lower the barrier to entry for people using Raspberry Pi and Processing together. 

There's an interesting story about how I discovered Processing Foundation as the organization that I wanted to partner with.

{{% button text="Read the full story" link="./context/"%}}

## Results

The results of my work are the following:

- [Github repository](https://github.com/processing/processing-pi-website) containing the website and the content for the website.
- [Google Drive folder](https://drive.google.com/drive/folders/1_H9PT0fjTLHWreAVIz_dLWMqnzsWSjcT?usp=sharing) with a list of research materials I gathered while building the website.

Below I'll briefly summarize the work I've done:

### Website

I developed the website using a very fast static site generator called ["Hugo"](https://gohugo.io/). 

I've learned how to use Hugo, how to create a theme for it and how to populate content using this incredible static site development framework.

Here's the breakdown of the code contributions for the site so far: 
{{< figure src="contributions.png" width="400" title="Summary of the website contributions" >}} 

The work on the site consisted of:

- Choosing what website engine to use (build from scratch or use a framework)
- Creating a responsive layout and theme fitting the content and style of the site
- Creating unique shortcodes to enable a wide variety of content (code, diagrams, figures, tables, asides, etc)

### Tutorials

I've written three tutorials so far on the following topics:

- Building a visual synthesizer (complete and [publised](https://pi.processing.org/tutorial/visual-synth/))
- Using Camera with Processing on the Pi ([under review](https://github.com/processing/processing-pi-website/tree/tutorial-camera))
- Building a capacitive touch musical instrument ([being rewritten](https://github.com/processing/processing-pi-website/tree/tutorial-capacitive-touch-keyboard))

In each tutorial, I've used various media to better convey the meaning to the reader:

- Text
- Video
- Screenshots
- Screen Recordings
- Schematics
- Diagrams

### User Research

Before I made the layout, structure and the content for the website, I've worked with one of my  classmates to do a great deal of user research to understand what people would need the most. We have captured the outcomes of that research in this report: https://drive.google.com/file/d/1FT_tDqWqY2RS66tmwVXCIke6VYXAW_6V/view?usp=sharing 

## Process

Here's the progression of my process for this project:

1. User Research
2. Concept
3. Static Site Generator Research 
4. Choice of Static Site Generator
5. Create theme for the website
6. Create SASS stylesheets
7. Write Tutorial 1 (Visual Synthesizer)
8. Write tutorial 2 (Capacitive touch instruments)
9. Write Tutorial 3 (Using Camera)

{{% button text="See the whole process" link="./process/" %}}

## Next Steps

What can be done

## Fin

{{< figure src="maks-dancing-short.gif" class="center"  title="Maks Dancing" >}} 



