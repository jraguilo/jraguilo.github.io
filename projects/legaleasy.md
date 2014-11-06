---
layout: page
title: "Legal Easy"
description: "Project Page for Legal Easy"
---
{% include JB/setup %}

Legaleasy is a cleanly designed, simply implemented Web/Android hybrid application to translate hard-to-read legal documents from "legalese" into plain old easy-to-read English.

Legal Easy was developed by my team of four members for HackSC, a hackathon hosted by the University of Southern California. We were given 36 hours to develop any project, and we chose to use this time to develop our legalese application, because we felt that it was a product that would be beneficial to the average person who must read legal documents and is having trouble understanding the technical terms within them.

We chose to develop our web application using Python with the Django web framework. We utilized a local SQLite database to store collection of legalese terms and their translations into simple English. 

We also chose to develop an Android application to work alongside our web application, and made it a goal to allow a user to take a picture of a document with their mobile device, and have it translated. To achieve this end, we utilized Abbyy OCR, a third-party ORC software, to convert the image into plain text, which we then used with our web application to translate into simple English.

- <a href="https://github.com/jraguilo/LegalEZApp">View Web Application Code on GitHub</a>
- <a href="https://github.com/CaryAndo/legaleasy">View Android Application Code on GitHub</a>