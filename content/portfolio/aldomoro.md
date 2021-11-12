---
title: "The National Edition of Aldo Moro’s works"
subtitle: "Digital edition of the published and unpublished texts by the famous italian polititian from the second half of XX century Aldo Moro"
date: 2021-11-02T11:35:10+01:00
showDate: false
draft: false
period: "Jun. 2021 - Nov. 2021"
startDate: "2021-06-01"
endDate: "2021-11-30"
tags: ["digital publishing","web development","vue.js","vuetify","node.js","rdflib.js"]
category: "portfolio"
---

![The National Edition of Aldo Moro's works](/portfolio/aldomoro/aldomoro.png)

## Digital edition of the published and unpublished texts by Aldo Moro, a famous italian politician from the second half of XX century

The project has been funded by the Ministry of Cultural Heritage of Italy in collaboration with the Univesity of Bologna, my role as a Research Assistant was to develop the [markup web application](/portfolio/kwickk/) for the texts collection and the digital edition.

The development of the edition website was based on a preliminary benchmark (https://zenodo.org/record/5184721) of a representative sample of major digital editions currently existing on the Web, according to a series of quality criteria identified in the scientific literature. Starting from the comparative study, I designed together with my collegue the information architecture of the website. This process involved the creation of a site map and a series of wireframes of its main pages made with Figma, to plan its interface, structure, and contents. 

![Example of the Content section made with Figma](/portfolio/aldomoro/wireframe_aldomoro_contents.png)

The development of the Edition website makes use of versatile and efficient frameworks, based on criteria such as modularity, accessibility, and responsive design. We managed to compile with these principles by using Vue.js, one of the most popular open-source Javascript framework to build user interfaces, together with Vuetify, a library built from Vue that implements Google’s Material Design. The actual interactions between interface and final user depend on the Node.js backend that combined the usefull Rdflib.js features to access our RDF collection and retrive all the data needed.

![The digital edition Content section](/portfolio/aldomoro/aldomoro_contents.png)

To consult the digital edition click [here](https://doi.org/10.6092/unibo/aldomoro).

> **Skills used**
>
> - **Front-end**: 
> Vue.js, Vuetify, Javascript, SASS
> - **Back-end**:
> Node.js, Express, Rdflib.js
> - **Concepts**: 
> Web developing, RDF, FRBR, Digital Publishing, Linked Data
> - **Tools**: 
> Visual Studio Code, Figma
