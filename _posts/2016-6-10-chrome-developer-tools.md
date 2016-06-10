---
layout: post
title: chrome development tools

---
<p>
Google Chrome is a rich and powerful web browser, pioneering what is possible for applications on the web. Google has worked hard to deliver a very fast, very stable, feature rich browsing experience for end users. Google has also ensured that developers like you have a great experience with Chrome. The Developer Tools, bundled and available in Chrome and Safari, allows web developers and programmers deep access into the internals of the browser and their web application.</p>

<p>The Developer Tools are part of the open source Webkit project. Most of the discussion in this article applies to both Google Chrome and Safari. However, the screenshots were taken using Google Chrome 6, so there may be slight differences in your browser.
In this article, we will take an overview tour of Developer Tools and point out its most popular, and useful, features. Our target audience are web developers who did not know of, or have not yet investigated, the Developer Tools. However, we are sure that even if you are an experienced web developer, you will pick up a tip or two</p>

Chrome 5 now offers
<h1>Elements</h>
<p>The Elements tool allows you to see the web page as the browser sees it. That is, using the Elements tool, you can see the raw HTML, raw CSS styles, the Document Object Model, and manipulate either in real time.</p>

<h1>Resources</h1>
<p>Use the Resources tool to learn what components your web page or application is requesting from web servers, how long these requests take, and how much bandwidth is required. You can also view the HTTP request and response headers for each of your resources. The Resources tool is perfect for helping you speed up page load times.</p>

<h1> Scripts</h1>
<p>To peer inside the JavaScript for a page, you will use the Scripts tool. Here you can find a list of scripts required by the page plus a full featured script debugger. You can even change the JavaScript on the fly. </p>

<h1> Timeline</h1>
<p>For advanced timing and speed analysis, the Timeline tool offers in-depth visibility into the various Chrome behind-the-scenes activities. You can learn how long the browser takes to handle DOM events, rendering page layouts, and paint the window.</p>

<h1>Profiles</h1>
<p>The Profiles tool helps you capture and analyze the performance of JavaScript scripts. For example, you can learn which functions take the most time to execute and zero in on exactly where to optimize. </P>

<h1> Storage</h1>
<p>Modern web applications require more persistence than simply cookies, and the Storage tool helps you track, query, and debug local browser storage. This tool can display and query data stored in local databases, local storage, session storage, and cookies.</p>

<h1>Audits</h1>
<p>The Audit tool is like having your own web optimization consultant sitting next to you. This tool can analyze a page as it loads and provide suggestions and optimizations for decreasing page load time and increase perceived (and real) responsiveness</p>

    </p>


Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.
