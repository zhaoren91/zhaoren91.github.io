---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**Dr.-Ing. Zhao Ren** is a *Senior Researcher* at the <a href="https://www.uni-bremen.de/csl" target="_blank">Cognitive Systems Lab</a>, <a href="https://www.uni-bremen.de" target="_blank">University of Bremen</a>, Germany. Before this, she worked as a Research Associate in <a href="https://www.l3s.de/en" target="_blank">L3S Research Center</a>, <a href="https://www.uni-hannover.de/en/" target="_blank">Leibniz Universität Hannover</a>, Germany. She received her doctoral degree from <a href="https://www.uni-augsburg.de/en/" target="_blank">University of Augsburg</a>, Germany, in 2022. 

Her research interests mainly lie in affective computing, computational paralinguistics, silent paralinguistics, and digital health. She has (co-)authored 70+ publications in peer-reviewed book chapters, journals, and conference proceedings, which have received 3k+ citations (h-index 27). She serves as a guest editor in IEEE JBHI, Cyborg and Bionic Systems, and multiple Frontiers journals. She is an associate editor of Frontiers in Digital Health, and chaired sessions in ICASSP and EMBC. 

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
