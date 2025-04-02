---
category: journal-article
aliases: 
- {{title}}
- {{#unless entry.author.[1]}}{{entry.author.[0].family}} ({{year}}){{/unless}}{{#unless entry.author.[2]}}{{#if entry.author.[1]}}{{entry.author.[0].family}} and {{entry.author.[1].family}} ({{year}}){{/if}}{{/unless}}{{#if entry.author.[2]}}{{entry.author.[0].family}} et al. ({{year}}){{/if}}
author: [ {{#each entry.author}}"{{this.given}} {{this.family}}"{{#unless @last}}, {{/unless}}{{/each}} ]
title: "{{title}}"
journal: "{{containerTitle}}"
year: "{{year}}"
methodology:
tags: 
- journalarticle
- toRead
---
# {{#unless entry.author.[1]}}{{entry.author.[0].family}} ({{year}}){{/unless}}{{#unless entry.author.[2]}}{{#if entry.author.[1]}}{{entry.author.[0].family}} and {{entry.author.[1].family}} ({{year}}){{/if}}{{/unless}}{{#if entry.author.[2]}}{{entry.author.[0].family}} et al. ({{year}}){{/if}}
## {{title}} 

---
### Summary
summary:: "NEEDS SUMMARY"

#### Observations

---
### Detailed Notes

---
### Quotes
#### Abstract

> {{abstract}}



---
### Figures and  Tables
#### Figures
#### Tables
---
### References

---
### Related

---
### Citations

---
### Metadata
- citekey: @{{citekey}}
- author(s): {{#each entry.author}}[[{{this.given}} {{this.family}}]]{{#unless @last}} | {{/unless}}{{/each}}
- journal: [[{{containerTitle}}]]
- DOI Link:: [{{#unless entry.author.[1]}}{{entry.author.[0].family}} ({{year}}){{/unless}}{{#unless entry.author.[2]}}{{#if entry.author.[1]}}{{entry.author.[0].family}} and {{entry.author.[1].family}} ({{year}}){{/if}}{{/unless}}{{#if entry.author.[2]}}{{entry.author.[0].family}} et al. ({{year}}){{/if}}](https://www.doi.org/{{DOI}})