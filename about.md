---
layout: about
title: About
---

<img id="headerImg" alt="headshot" src="/assets/images/about/headshot.jpeg" />

## About Me
Swiftjective-C is written by me, [Jordan Morgan](https://www.twitter.com/jordanmorgan10){:target="_blank"}. I'm an iOS engineer from Ozark, Missouri where I live with my [wife](https://www.instagram.com/jmorgan){:target="_blank"} and three kids. Currently, I work remotely on the iOS team at [Buffer](https://www.buffer.com){:target="_blank"}, where we build a suite of social media tools.

#### Articles 
<ul>
  {% for item in site.data.myWork.articles %}
    <li><a href="{{ item.link }}" target="_blank">{{ item.title }}</a></li>
  {% endfor %}
</ul>

#### Books 
<ul>
  {% for item in site.data.myWork.books %}
    <li><a href="{{ item.link }}" target="_blank">{{ item.title }}</a></li>
  {% endfor %}
</ul>

#### Talks and Slides 
<ul>
  {% for item in site.data.myWork.talks %}
    <li><a href="{{ item.link }}" target="_blank">{{ item.title }}</a></li>
  {% endfor %}
</ul>

#### Online Presence 
<ul>
  {% for item in site.data.myWork.online %}
    <li><a href="{{ item.link }}" target="_blank">{{ item.title }}</a></li>
  {% endfor %}
</ul>

## Site History
This journal originally started on Medium in 2013 and was called "[The Traveled iOS Developer's Guide](https://medium.com/the-traveled-ios-developers-guide){:target="_blank"}". I enjoyed several years writing there, and to the best of my knowledge, I was lucky enough to grow it into one of the largest iOS blogs on the platform with around 13,000 subscribers when I had left.

I eventually opted to move things over here for a few reasons:

- I wanted to change the name to something much shorter than "The Traveled iOS Developer's Guide".
- I wanted to host and truly own my own content.
- And I had the itch to do some web development.

Movtivation to write about iOS development and create a dedicated space for it stemmed from a few things: 

- I have a natural love of writing, and doing so scratches an itch that's otherwise left untouched. 
- Sharing knowledge, what I know and what I hope to learn is also built into my ethos. It's rewarding, I get to meet other developers and hopefully it's helpful. 
- Finally, with three kids - I've found it extremely challenging to attend or speak at conferences anymore. I'm naturally extroverted so I miss this; Swiftjective-C acts as a creative outlet to participate in the conversation at large that's always happening in our industry.

Tonally, I opt for much more of an "open journal" style of writing. My hope is that each post feels more like you and I having a conversation that it does reading a tutorial on how to do X or Y.

## Colophon
[Jekyll](https://jekyllrb.com){:target="_blank"}, a robust static site generator, is used to manage and create Swiftjective-C. It uses no existing theme and is rolled from scratch.

[Sublime](https://www.sublimetext.com){:target="_blank"} is my text editor of choice for web development. Additionally, I also write each blog post using markdown in it as well.

[Netlify](https://www.netlify.com){:target="_blank"} handles domain management and all deployment of its source code. Without it, I'm not sure this site would exist. It's easily the most inuitive way I've found to get a website up and rolling.

[Github](https://www.github.com){:target="_blank"} is used for source control, and each article and the entire source code for this site is available there for collobaration and learning purposes. It's free to use and to change however you wish.

[Fathom](https://usefathom.com){:target="_blank"} is used for analytics, and it has an emphasis on respecting user privacy. It shows just what I need, and nothing more.

Finally, accessibility is extremely important to me. If you spot anything off or have any suggestions to improve this site's accessbility, please get in touch. Additionally, feel free to open an issue or create a pull request.