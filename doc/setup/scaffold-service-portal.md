---
layout: default
title: Scaffold Service Portal
parent: Setup
nav_order: 5
---

# Scaffold Service Portal
1. Find your workspace for the above application and `cd` into the application.

2. Type `ls` and you should see a `src` folder. Service Portal Scaffold will scaffold the template files into this `src` folder.

3. To scaffold service portal using a template, use the following command `portal create --template demo`. We're scaffolding service portal using the __demo__ template. The files for the demo template can be found here: `sn-scaffold/templates/demo`. To scaffold service portal using a default template, use the following command `portal create`.

4. After the scaffolding has run successfully, sync your workspace with the instance using VS Code ServiceNow Extension.

5. Sync by clicking the `Sync Current Project icon` on the status bar in VS Code. You can also press `CMD+OPT+S` on MacOS or `CTRL+ALT+S`​​ on Windows to sync the project.

<a href="https://asc2683.github.io/sn-scaffold-doc/images/sp-scaffold-sync.gif">
  <img src="https://asc2683.github.io/sn-scaffold-doc/images/sp-scaffold-sync.gif">
</a>

More information on how to synchronize current project between [VS Code and a ServiceNow instance](https://docs.servicenow.com/bundle/paris-application-development/page/build/applications/task/synchronize-files.html).
