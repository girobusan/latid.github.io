---
title: Command Line Interface
date: 2021.01.13 10:21
section: 01.05
excerpt: <p>Latid can be invoked as command line utility. It's useful, when hosting on Jamstack. Just setup your build action, using <code>l4cli.js</code> utility.</p>
---
Latid can be invoked as command line utility. It's useful, when hosting on Jamstack. Just setup
your build action, using `l4cli.js` utility.
<!--cut-->

Execute this from the site directory:

    node l4cli.js

It will gather source files and generate output static htmls. Invoking with `-t` key initiates "time aware" generation (files with date in future won't be processed)