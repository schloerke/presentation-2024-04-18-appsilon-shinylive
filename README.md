# `{shinylive}`: Serverless Shiny apps

<!-- ## Slides -->

<!-- * HTML:
http://schloerke.com/presentation-2024-04-18-appsilon-shinylive/ -->

Live demo app: https://schloerke.com/presentation-2024-04-18-appsilon-shinylive/

Slides: https://schloerke.com/presentation-2024-04-18-appsilon-shinylive/slides/


## Resources for learning more

* [`{shinylive}`](https://posit-dev.github.io/shinylive/) [:octocat:](https://github.com/posit-dev/shinylive): Serverless Shiny apps

* [`{shiny}`](https://shiny.rstudio.com/) [:octocat:](https://github.com/rstudio/shiny): Web Application Framework for R



## Abstract

In the rapidly evolving landscape of web technologies, the integration of R (and Python) with modern web frameworks has become increasingly important for data scientists and developers. This presentation introduces {shinylive}, a new R package that exports Shiny applications to be run within statically hosted websites. We will explore the capabilities of {shinylive} through its use of the innovative R package {webR}, which allows for the execution of R code in the browser (via WebAssembly and service workers) without the need for a centralized server.

The presentation will cover the technical foundation of {shinylive}, including its architecture and the integration process with Quarto documents. We will also discuss the practical aspects and drawbacks of exporting Shiny apps with {shinylive}, highlighting the ease of exporting apps to a folder for local use or hosting them on GitHub pages.

{shinylive} bridges the gap between Shiny and static websites, making it a valuable resource for interactive data analysis and presentation.
