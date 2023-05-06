<div align="center">

# Flux Emacs

[Documentation] • [FAQ]

![Made with Flux Emacs](https://img.shields.io/badge/Version-1.0.0-lightblue.svg?style=flat-square&logoColor=white)
![Supports Emacs 24.5+](https://img.shields.io/badge/Supports-Emacs_24.5+-lightblue.svg?style=flat-square&logo=GNU%20Emacs&logoColor=white)

</div>

---

### Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Install](#install)
- [Getting help](#getting-help)
- [Contribute](#contribute)


# Introduction
Flux is an excellent configuration framework for [GNU Emacs] that can help streamline your workflow and boost productivity. While it is designed with experienced Emacs users in mind, anyone looking to simplify and speed up their configuration can benefit from using Flux. It offers the advantages of a finely crafted configuration without compromising performance or the ability to install and manage packages with ease. Whether you are a seasoned Emacs user or a newcomer, Flux can serve as a solid foundation for your configuration or a valuable resource to enhance your Emacs skills.

These guiding principles inform the design of Flux:

+ **Speed and efficiency first.** Flux is designed to prioritize startup and run-time performance, ensuring a fast and smooth experience for users. Packages are optimized for speed and lazy loading to enhance the workflow.
+ **Flexibility and extensibility.** Flux can be used as a foundation for users' own Emacs configuration or as a resource for learning more about Emacs. Flux's modular design and built-in package management system make it easy to add or remove packages and customize Emacs to users' specific needs.
+ **Respect for user preferences.** Flux believes that users know best and respects their preferences. Flux does not automatically install system dependencies, leaving it up to users to install them as needed. The "Flux Doctor" tool can assist users in identifying and resolving any missing dependencies.
+ **Ease of use and convenience.** Flux includes a built-in installer that simplifies the installation and setup process for new users, and also provides a comprehensive documentation system.


# Prerequisites
+ Git
+ Emacs 24.5+
+ Any Linux distribution or Windows 7+


# Install
``` sh
git clone --depth 1 https://github.com/convict-real/Flux-Emacs or download and extract

On Linux, run install.sh
On Windows, run install.bat as Administrator
```


# Getting help
Emacs is no journey of a mere thousand miles. You _will_ run into problems and
mysterious errors. When you do, here are some places you can look for help:

+ [Our documentation][documentation] covers many use cases.
  + Your issue may be documented in the [FAQ].
+ Check out the [FAQ] or [Discourse FAQs][discourse-faq], in case your question
  has already been answered.
+ Search [Flux's issue tracker](https://github.com/convict-real/Flux-Emacs/issues) in case your issue was already
  reported.


# Contribute
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) 
[![Elisp styleguide](https://img.shields.io/badge/Elisp-Style--guide-purple?style=flat-square)](https://github.com/bbatsov/emacs-lisp-style-guide)

Although Flux is a result of my passion and dedication to Emacs, as a single person, I can't accomplish everything on my own. This is why I highly encourage and welcome any contributions, big or small, from the Emacs community to help improve and expand Flux.

+ I :heart: pull requests and bug reports (see the [Contributing
  Guidelines][contribute])!
+ Don't hesitate to [tell me my Elisp
  sucks](https://github.com/convict-real/Flux-Emacs/issues/new), but please tell me
  why.


[contribute]: docs/contributing.org
[documentation]: docs/index.org
[faq]: docs/faq.org
[modules]: docs/modules.org
[popup-system]: modules/ui/popup/README.org
[gnu emacs]: https://www.gnu.org/software/emacs/
