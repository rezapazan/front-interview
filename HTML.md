# HTML Interview Questions

**1. Describe HTML layout structure.**

- header
- footer
- nav
- article
- section
- aside

**2. What are Semantic Elements?**

Semantic elements are those which describe the particular meaning to the browser and the developer. Elements like **\<form\>, \<table\>, \<article\>, \<figure\>**, etc., are semantic elements.

**3. What are Web Workers?**
These are added to bring parallelism and async capability. It runs in the background to do the computationally expensive tasks without yielding to make the page responsive. It is achieved by starting a separate thread for such tasks. These are not meant to perform UI operations. There are three types of web workers:

- Dedicated Workers
- Shared Workers
- Service Workers

**4. What is a manifest file in HTML5?**
The manifest file is used to list down resources that can be cached. Browsers use this information to make the web page load faster than the first time. There are 3 sections in the manifest file:

- CACHE Manifest
- Network
- Fallback

**5. What is critical render path?**
The Critical Rendering Path is the sequence of steps the browser goes through to convert the HTML, CSS, and JavaScript into pixels on the screen. Optimizing the critical render path improves render performance. Steps are:

- DOM
- CSS Object Model
- Render Tree
- Layout
- Paint
