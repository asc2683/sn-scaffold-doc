---
layout: default
title: Default Template
parent: Template
nav_order: 1
---

# Default Template
To scaffold a __default__ template to your Service Portal project run the following command without the `--template` option.
```
portal create

```
This will copy the contents `sn-scaffold/template/default/src` folder to your scoped application's `src` folder. The __default__ template scaffolds the following Service Portal files: 

```
Service Portal
│
├──Style Sheets
│  └──Style.css
│
├──Themes
│  └──Theme.css_variables.scss
│
└──Widgets
   ├──Header
   │  ├──Header.template.html
   │  ├──Header.client_script.js
   │  ├──Header.css.scss
   │  ├──Header.option_schema.json
   │  ├──Header.script.js
   │  ├──Header.link.js
   │  └──Header.demo_data.json
   ├──Main
   │  ├──Main.template.html
   │  ├──Main.client_script.js
   │  ├──Main.css.scss
   │  ├──Main.option_schema.json
   │  ├──Main.script.js
   │  ├──Main.link.js
   │  └──Main.demo_data.json   
   └──Footer
      ├──Footer.template.html
      ├──Footer.client_script.js
      ├──Footer.css.scss
      ├──Footer.option_schema.json
      ├──Footer.script.js
      ├──Footer.link.js
      └──Footer.demo_data.json
```
The contents of __default__ template widgets, themes and style sheets files are empty. 