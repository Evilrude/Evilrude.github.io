---
date: '2026-02-09'
draft: false
title: 'Projet'
Summary: "summary de la page projet"
---

Contenu de la page projet

## Fields pour front matter
Juste une sélection de ceux qui pourraient m'intéresser

date: 'YYYY-MM-DD'
draft: false
title: 'À propos'
tags: ["Axe 1"]
description: "blablabla"
showAuthor: true
authors:
- "ohelary"
- "smoon"
showAuthorBadges: false


### Documentation des champs

Obtenue [ici](https://gohugo.io/content-management/front-matter/)

* cascade
	> (map) A map (or a slice of maps) of front matter keys whose values are passed down to the page’s descendants unless overwritten by self or a closer ancestor’s cascade. See the cascade section for details.

* **date**
	> (string) The date associated with the page, typically the creation date. Note that the TOML format also supports unquoted date/time values. See the dates section for examples. Access this value from a template using the Date method on a Page object.

* description
	> (string) Conceptually different than the page summary, the description is typically rendered within a meta element within the head element of the published HTML file. Access this value from a template using the Description method on a Page object

* headless
	> (bool) Applicable to leaf bundles, whether to set the render and list build options to never, creating a headless bundle of page resources.

* keywords
	> ([]string) An array of keywords, typically rendered within a meta element within the head element of the published HTML file, or used as a taxonomy to classify content. Access these values from a template using the Keywords method on a Page object.

* **lastmod**
	> (string) The date that the page was last modified. Note that the TOML format also supports unquoted date/time values. See the dates section for examples. Access this value from a template using the Lastmod method on a Page object.

* **menus**
	> (string, []string, or map) If set, Hugo adds the page to the given menu or menus. See the menus page for details.

* resources
	> (map array) An array of maps to provide metadata for page resources.

* sitemap
	> (map) A map of sitemap options. See the sitemap templates page for details. Access these values from a template using the Sitemap method on a Page object.

* **summary**
	> (string) Conceptually different than the page description, the summary either summarizes the content or serves as a teaser to encourage readers to visit the page. Access this value from a template using the Summary method on a Page object.

* **title**
	> (string) The page title. Access this value from a template using the Title method on a Page object.