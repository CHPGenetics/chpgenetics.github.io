# Chen Lab Website
URL: [https://chenlab.pitt.edu](https://chenlab.pitt.edu)

## Quick update guidelines

You can always easily update the contents by GitHub official editor. Most of the contents are in Markdown format ([Quickstart](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)).

Update **news**: [link](https://github.com/CHPGenetics/chpgenetics.github.io/blob/main/content/news/_index.md)

Update **recent news on homepage**: [link](https://github.com/CHPGenetics/chpgenetics.github.io/blob/main/content/home/recent%20news.md)

Update **recent publications on homepage**: [link](https://github.com/CHPGenetics/chpgenetics.github.io/blob/main/content/home/recent%20publications.md)

Update **members**: [link](https://github.com/CHPGenetics/chpgenetics.github.io/tree/main/content/authors) (You may need to create a new folder for new member and refer to the structure of other existing members.)

Update **Dr. Chen's CV pdf file**: [link](https://github.com/CHPGenetics/chpgenetics.github.io/tree/main/static/files) (You may need to first delete the old file and then upload the new file.)

The website will automatically update once you modify and commit the file contents in this repository. [Check status](https://github.com/CHPGenetics/chpgenetics.github.io/actions)

## Local compile directions

Please install hugo v0.92.0 extended based on your OS. There is known issue with the latest version of hugo. Only v0.92.0 is verified. [Download link](https://github.com/gohugoio/hugo/releases/tag/v0.92.0)

If `public` folder already exists, delete it with `rm -rf public`.

Run `hugo` under the root directory of this repo to compile the static website. (You may need to add hugo v0.92.0 to PATH or specify the path of correct version.)

The generated `public` folder is the whole static website. Move it to the server where the website is hosted.

## Notes

Check the `base_url` in config/_default/config.toml if your host domain is changed.


---
*You might not need the information below, but it’s here just in case.*

# Original README of this hugo template (Some links have been confirmed as broken)

<p align="center"><a href="https://sourcethemes.com/academic/" target="_blank" rel="noopener"><img src="https://sourcethemes.com/academic/img/logo_200px.png" alt="Academic logo"></a></p>

# Academic Kickstart: The Template for [Academic Website Builder](https://sourcethemes.com/academic/)

[**Academic**](https://github.com/gcushen/hugo-academic) makes it easy to create a beautiful website for free using Markdown, Jupyter, or RStudio. Customize anything on your site with widgets, themes, and language packs. [Check out the latest demo](https://academic-demo.netlify.app/) of what you'll get in less than 10 minutes, or [view the showcase](https://sourcethemes.com/academic/#expo).

**Academic Kickstart** provides a minimal template to kickstart your new website.

- 👉 [**Get Started**](#install)
- 📚 [View the **documentation**](https://sourcethemes.com/academic/docs/)
- 💬 [Chat with the **Academic community**](https://spectrum.chat/academic) or [**Hugo community**](https://discourse.gohugo.io)
- 🐦 Twitter: [@source_themes](https://twitter.com/source_themes) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithAcademic](https://twitter.com/search?q=%23MadeWithAcademic&src=typd)
- 💡 [Request a **feature** or report a **bug**](https://github.com/gcushen/hugo-academic/issues)
- ⬆️ **Updating?** View the [Update Guide](https://sourcethemes.com/academic/docs/update/) and [Release Notes](https://sourcethemes.com/academic/updates/)
- :heart: **Support development** of Academic:
  - ☕️ [**Donate a coffee**](https://paypal.me/cushen)
  - 💵 [Become a backer on **Patreon** and **unlock rewards**](https://www.patreon.com/cushen)
  - 🖼️ [Decorate your laptop or journal with an Academic **sticker**](https://www.redbubble.com/people/neutreno/works/34387919-academic)
  - 👕 [Wear the **T-shirt**](https://academic.threadless.com/)
  - :woman_technologist: [**Contribute**](https://sourcethemes.com/academic/docs/contribute/)

[![Screenshot](https://raw.githubusercontent.com/gcushen/hugo-academic/master/academic.png)](https://github.com/gcushen/hugo-academic/)

## Install

You can choose from one of the following four methods to install:

* [**one-click install using your web browser (recommended)**](https://sourcethemes.com/academic/docs/install/#install-with-web-browser)
* [install on your computer using **Git** with the Command Prompt/Terminal app](https://sourcethemes.com/academic/docs/install/#install-with-git)
* [install on your computer by downloading the **ZIP files**](https://sourcethemes.com/academic/docs/install/#install-with-zip)
* [install on your computer with **RStudio**](https://sourcethemes.com/academic/docs/install/#install-with-rstudio)

Then [personalize your new site](https://sourcethemes.com/academic/docs/get-started/).

## Ecosystem

* **[Academic Admin](https://github.com/sourcethemes/academic-admin):** An admin tool to import publications from BibTeX or import assets for an offline site
* **[Academic Scripts](https://github.com/sourcethemes/academic-scripts):** Scripts to help migrate content to new versions of Academic

## License

Copyright 2017-present [George Cushen](https://georgecushen.com).

Released under the [MIT](https://github.com/sourcethemes/academic-kickstart/blob/master/LICENSE.md) license.

[![Analytics](https://ga-beacon.appspot.com/UA-78646709-2/academic-kickstart/readme?pixel)](https://github.com/igrigorik/ga-beacon)
