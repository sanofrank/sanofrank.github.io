---
title: "KwicKwocKwac"
subtitle: "An intuitive documents markup web application"
date: 2021-11-01T15:07:47+01:00
showDate: false
draft: false
period: "Jun. 2020 - May 2021"
startDate: "2020-06-01"
endDate: "2021-05-31"
tags: ["digital publishing","web development","node.js","RDFa","FRBR", "jQuery"]
category: "portfolio"
---

![KwicKwocKwac example](/portfolio/kwicKK/kwicKK_mainpage.png)

## An intuitive documents markup web application

KwicKwocKwac (KeyWords In Context, KeyWord Out of Context, KeyWord Alongside Context) is a Web environment with the goal of providing users with a simple and intuitive tool to enrich the text of documents in digital format through semi-automatic markup and metadata features.

Originally developed by professor Fabio Vitali at the Department of Computer Science and Engineering of the University of Bologna, it was then hand over to me in order to implement new features for the reasearch project of [The National Edition of Aldo Moro's works](/portfolio/aldomoro/).

![KwicKwocKwac markup gif example](/portfolio/kwicKK/kwicKK_markup.gif)

The main features of the application are:

- Extraction of concordances as alphabetically ordered lists of words that appear in a text with an indication of the textual context surrounding that word;
- Markup of intertextual elements (people, organizations, places, bibliographic references, and quotations);
- Manual entity disambiguation (as with indirect mentions, and so on);
- Data reconciliation with authority lists such as Wikidata to further disambiguate marked entities and link them to web resources, to ensure validity and quality control;
- Metadata insertion, to describe the historical and bibliographic context of each work. All the metadata are saved on a MongoDB database.
 
After the markup and the metadata insertion is completed, KwicKwocKwac output can be expressed in two forms: an HTML RDFa file that extends the number one markup language with RDF subject-predicate-object expressions, or a XML TEI file the still most used encoding standard for digital texts.

The platform was developed mainly with jQuery and Bootstrap on the front-end, while the back-end infrastructure is build on Node.js with the help of many libraries like: Express for the API and routing handling, Mammooth.js for the doc or docx convertion to HTML files, Cheerio.js for the document parsing and many others.

In order to access the web application, the researchers were provided by an account where the access is protected by JSON web tokens encryption.

You can take a look at the [Github repository](https://github.com/sanofrank/KwicKwocKwac) for more information. 

> **Skills used**
>
> - **Front-end**: 
> jQuery, Bootstrap
> - **Back-end**:
> Node.js, Express
> - **Concepts**: 
> Web developing, RDFa, TEI, Digital Publishing, Linked Data, JWT
> - **Tools**:
> Visual Studio Code, MongoDB Compass