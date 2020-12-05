---
title: "Best practices for developer documentation"
linkTitle: "Best practices"
weight: 8
date: 2020-03-16
description: >
    Follow these best practices when developing Axway product documentation.
---

## Organizing your documentation

To make your documentation easy to read and helpful for customers, consider the following best practices for organizing your documentation.

### Use a navigation menu

It is important to create a clear navigation menu, because it helps the user to navigate through the documentation.

Firstly, consider the main topics that users might search for. If you need to create subtopics to get in more depth about the subject matter, nest those subtopics underneath the main topic as _child_ topics.

For example, place all of the installation and upgrade manuals under the main **Installation instructions** topic. This makes it easier to find all of the information that is related to installation in one place.

It is good practice to have a well-structured menu hierarchy to help users to navigate the documentation website, ordering the most important content at the top of the menu. However, it is also common for users to land on a page from a search result. In this case, the order of the menu is not relevant.

{{% alert title="Note" %}}
Be mindful of the number of levels of subtopics in your menu. More than three levels can make the menu confusing and difficult to navigate.
{{% /alert %}}

To see an example of a well-structured navigation menu, see the [Kong Enterprise Documentation](https://docs.konghq.com/enterprise/).

### Make the documentation discoverable

Documentation must be easy to find and the key to this is to ensure that it can be found by a Google search. To improve the documentation visibility in search engines, apply the following search engine optimization (SEO) rules:

* Create short, unique, and accurate page titles.
* Use a well-structured navigation menu - this helps search engines to understand what content is important.
* [Use meaningful link text](#use-meaningful-link-text) when you create URLs.

## Include helpful sections in the documentation

The following sections help to provide more in-depth information to your documentation.

### Add a getting started section

A getting started section introduces your product and provides the first steps that the users need to take to start using the product.

For some examples of well-written getting started guides, see the following websites:

* [Getting Started with Amazon API Gateway](https://docs.aws.amazon.com/apigateway/latest/developerguide/getting-started.html)
* [Getting Started with Docker](https://docs.docker.com/get-started/)

### Add a reference

A reference section supports the performance of a task by providing more detail or quick guidance to the user. For example, you can add technical references of the software’s code, functions, APIs, CLI, or parameters. For guidance about writing reference content, see the [DITA reference topic guide](https://docs.oasis-open.org/dita/v1.2/os/spec/archSpec/dita_reference_topic.html).

For some examples of well-written references, see the following websites:

* [Apigee Edge flow variables reference documentation](https://docs.apigee.com/api-platform/reference/variables-reference)
* [Docker reference documentation](https://docs.docker.com/reference/)
* [Kubernetes reference documentation](https://kubernetes.io/docs/reference/)

### Add a glossary

The glossary defines all of the terms that might be unique to your company or product. In some cases, the user’s understanding of the documentation might depend on the clarity and alignment of specific terms.

For some examples of well-written glossaries, see the following websites:

* [Amazon AWS glossary](https://docs.aws.amazon.com/general/latest/gr/glos-chap.html)
* [Docker glossary](https://docs.docker.com/glossary/)

### Add tutorials

Tutorials are lessons that walk the reader through a series of steps to complete a procedure. A tutorial shows how to accomplish a goal that is larger than a single task.

For some examples of well-written tutorials, see the following website:

* [Kubernetes tutorials](https://kubernetes.io/docs/tutorials/)

### Add how-to guides

How-to guides assume that users already possess some basic knowledge of features and tools, and how to perform simple tasks. They help intermediate or experienced users to solve a real-world task by using the software.

For some examples of well-written how-to guides, see the following websites:

* [Tyk Planning for Production](https://tyk.io/docs/deploy-tyk-premise-production/)
* [Kubernetes Assign-memory-resource](https://kubernetes.io/docs/tasks/configure-pod-container/assign-memory-resource/)

### Add videos

Producing a video is a lengthy and costly task. Videos can get obsolete very quickly, especially when they demonstrate the screens of a user interface (UI).

Nevertheless, in Axway, we have been receiving more and more feedback from customers asking for videos to help them to use our products. Therefore, we add videos to complement complex procedures and help the user to be successful when they are trying to accomplish a task.

## Code samples and scripts

Code samples and downloadable scripts help the user to get up and running fast. Include an explanation about how to use the code to achieve a specific goal.

### Add code samples

Code samples are small snippets of code that help the user to understand a concept that is explained in the documentation. They can also be used to demonstrate the syntax of attributes or parameters.

For some examples of well-written code samples, see the following websites:

* [Apache Configuration Sections](https://httpd.apache.org/docs/2.4/sections.html)
* [Oracle Create and Deploy Replication Nodes](https://docs.oracle.com/en/database/other-databases/nosql-database/19.5/admin/create-and-deploy-replication-nodes.html)

### Add downloadable scripts

Provide code examples in a way that customers can copy and paste and try out your product. The sample could also be downloadable, which is less error-prone than copying and pasting.

For some examples of copyable and downloadable scripts, see the following websites:

* [A Sample: Array of JSON Documents](https://docs.oracle.com/en/database/other-databases/nosql-database/19.5/full-text-search/appa-json-array.html).
* [Twilio Autopilot Templates repo on GitHub](https://www.twilio.com/docs/autopilot/twilio-autopilot-cli#schema-files).

## Review your work

Quality documentation must be continuously reviewed and improved. You can request the review of another writer or ask an end user or subject matter expert (SME) to validate your instructions and descriptions.

### Delete dead documentation

Remove old, outdated, or no-longer-used guides, because they can misinform and slow down the user experience. They can also display results in the search that are no longer relevant or correct.

### Avoid duplicated information

Duplicated content creates inconsistency and frustration, and it is hard to maintain. Follow these best practices:

* Record the information in one place where it most needed and relevant.
* Instead of rewriting information about a common technology or process, link to existing information about it.

## Writing style

Follow these guidelines to make your content more concise and clear.

### Page length

To determine the appropriate length for you page, consider the following points:

* If your topic is about completing a task, keep all of the required information in one single page. Users shouldn't need to jump back and forth between pages to achieve their goal.
* Users can use a right-side menu (like the one that is used in the Axway open docs pages) to navigate the content in a topic, so they don't need to scroll excessively.
* Keep all related content in one page. It easier to find information by using a `Ctrl+F` search.

### Be minimalist

Find a balance between no documentation and excessive documentation. Follow these best practices:

* Make documentation _skimmable_ by using action-oriented headings with strong, clear verbs.
* Remember that users scan pages in an F-shaped pattern, so design your content accordingly. For more information, see the the presentation by Kevin Burke called [How to write documentation for users that don't read](https://kevin.burke.dev/slides/documentation/).
* Break up the text often with diagrams, animated GIFs, or other media.
* Be intentional with the first 3-5 words of every paragraph.
* Use bulleted lists.
* Use variations in typeface appropriately, such as links or bold text.
* Use code snippets.
* Use screenshots sparingly.

### Use meaningful link text

Effective link text helps the user to understand where each link leads and decide whether they want to click the link or not.

Observe these guidelines to improve user experience and accessibility:

* Do not print a URL in the page as this does not read well and causes accessibility problems for screen reader software.
* Do not use the text **Click here** in the link, because it doesn't work well for SEO. 
* Describe the target of the link by using meaningful words or phrases.

### Do not overuse tables

Not all analyses or results warrant a table or image. Some simple results are best stated in a simple and short paragraph. In addition, complex tables can be a challenge for adaptive technology users, such as users of screen reader software.

Use tables as quick references to reveal trends, patterns, or relationships that might otherwise be difficult to grasp in plain-text format. 

Tables permit relatively easy comparison of information and easy access to information. For tables to be usable, they must be simple. For example, do not fill table cells with long texts; aim to use only single paragraphs.

For more information about when to use tables over text, see the University of Minnesota's topic on [Data vs. Layout Tables](https://accessibility.umn.edu/tutorials/data-vs-layout-tables).

### Do not overuse screenshots

Screenshots can become outdated very quickly, so to users, they can be misleading. The maintenance of updating screenshots is very time-consuming.

Also, too many unnecessary screenshots can clutter the page.

If you can present your results clearly in a few short sentences or in a list of steps, then an screenshot image is probably unnecessary.

## Reference articles

* [A Guide to Writing Your First Software Documentation](https://www.sitepoint.com/writing-software-documentation/)
* [Core Practices for Agile/Lean Documentation](http://www.agilemodeling.com/essays/agileDocumentationBestPractices.htm)
* [How to write documentation for users that don't read](https://kevin.burke.dev/slides/documentation/)
* [Chromium Documentation Best Practices](https://chromium.googlesource.com/chromium/src/+/master/docs/documentation_best_practices.md)
* [Why agile teams should care about documentation](https://techbeacon.com/app-dev-testing/why-agile-teams-should-care-about-documentation)
* [Google Search Engine Optimization (SEO) Starter Guide](https://support.google.com/webmasters/answer/7451184?hl=en)
* [I'd Rather Be Writing, API glossary](https://idratherbewriting.com/learnapidoc/docapis_glossary_section.html)
* [Google developer documentation, Link text](https://developers.google.com/style/link-text)
* [Infinite Scrolling Is Not for Every Website](https://www.nngroup.com/articles/infinite-scrolling/)
* [Web Style Guide, Page length](https://webstyleguide.com/wsg2/page/length.html)
* [DITA Reference topics](https://docs.oasis-open.org/dita/v1.2/os/spec/archSpec/dita_reference_topic.html)
* [Data vs. Layout Tables](https://accessibility.umn.edu/tutorials/data-vs-layout-tables)
* _Read Me First! A Style Guide for the Computer Industry_ is available in paperback or PDF.
