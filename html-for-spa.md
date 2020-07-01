---
layout: default
title: HTML for SPA
---
# HTML for SPA

## Introduction
A single-page application (SPA) is a website design approach where each new page's content is served not from loading new HTML pages but generated dynamically through JavaScript's ability to manipulate the DOM elements on the existing page itself.

In a more traditional web page architecture, an index.html page might link to other HTML pages on the server that the browser will download and display from scratch.

An SPA approach allows the user to continue consuming and interacting with the page while new elements are being updated or fetched, and can result in much faster interactions and content reloading.

In addition, the HTML5 History API allows us to alter the page's URL without reloading the page, allowing us to create separate URLs for different views.

Once inside of the SPA, the application is able to dynamically fetch content from the server through AJAX requests or websockets.

This allows the browser to keep the current page open while making requests to the server in the background to fetch additional content or new "pages" altogether.

If you've ever begun a search query and had intermediate results appear below the input form as you were typing, then you've witnessed dynamic queries taking place in the background that updated those DOM elements.

In fact, the server queries can fetch any kind of data, often taking the form of JSON payloads, strings, or even HTML elements that are already prepared for rendering.
