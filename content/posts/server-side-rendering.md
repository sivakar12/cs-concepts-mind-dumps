---
title: Server Side Rendering
date: 2020-09-14 19:32
---
Single page applications has content populated by JavaScript. Web crawlers from search engines run with javascript disabled. So they don’t index these things. To make this work, server side rendering gets the url and renders the app for that url and returns. After that render the page is the usual single page app. For this to work, you need a server. Just hosting static files in a CDN don’t work. This is mostly a nodejs server. Next js is a serverside rendering framework.