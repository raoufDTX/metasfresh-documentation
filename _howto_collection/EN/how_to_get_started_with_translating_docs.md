---
title: How to get started with translating docs?
layout: default
tags:
  - metasfresh Community
lang: en
---

## 1. Understand the task
1. get access to latest version of metasfresh
1. play through the manual in german first http://docs.metasfresh.org/webui_collection/DE/NeuerProduktionsauftrag.html
1. report feedback on [github](https://github.com/metasfresh/metasfresh-documentation/issues) if documentation is not fitting
1. [switch the language](http://docs.metasfresh.org/webui_collection/EN/SwitchLanguage.html) to EN
1. play through the workflow again
1. report feedback on [github](https://github.com/metasfresh/metasfresh-documentation/issues) if not all fields are translated
1. check other examples that already have been translated:
   1. http://docs.metasfresh.org/webui_collection/DE/Auftrag_erfassen.html
   1. http://docs.metasfresh.org/webui_collection/EN/SalesOrder_recording.html

## 2. Install your tools
1. [Install github desktop](https://github-windows.s3.amazonaws.com/GitHubSetup.exe) 
1. [Install and configure Atom Editor](http://docs.metasfresh.org/howto_collection/EN/how_to_setup_atom_for_contributing_docs.html)

## 3. Prepare Repository
1. Github Desktop: clone metasfresh/metasfresh-documentation to your local disk
1. switch to the gh-pages branch
1. create a branch with the name gh70 (gh+ issue number)

## 4. Develop translation
1. open atom and duplicate existing .md file
1. create an english translation manual in markdown language

## 5. Commit your changes
1. commit the new file using:
   * **commit title**: #<issuenumber> <title of issue>
   * **commit description**: desribe your changes and add link to github issue <br> sample:
   * **commit title**: #1234 translate test page to en_US
   * **commit description**: changing stuff here and there
   * **commit description**: https://github.com/metasfresh/metasfresh-documentation/issues/1234
 
1. create a pull request for review
    * the Pull request will take title and description from your last commit

## Further Reading

- [StyleGuide](https://github.com/metasfresh/metasfresh-documentation/blob/master/StyleGuide.md)
