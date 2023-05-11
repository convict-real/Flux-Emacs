<div align="center">

# Flux Emacs

[Documentation] • [FAQ]

![Made with Flux Emacs](https://img.shields.io/badge/Version-1.0.0-lightblue.svg?style=flat-square&logoColor=white)
![Supports Emacs 24.5+](https://img.shields.io/badge/Supports-Emacs_24.5+-lightblue.svg?style=flat-square&logo=GNU%20Emacs&logoColor=white)

</div>

---

### Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Install](#install)
- [Getting help](#getting-help)
- [Contribute](#contribute)


# Introduction
Flux is an excellent configuration framework for [GNU Emacs] that can help streamline your workflow and boost productivity. While it is designed with experienced Emacs users in mind, anyone looking to simplify and speed up their configuration can benefit from using Flux. It offers the advantages of a finely crafted configuration without compromising performance or the ability to install and manage packages with ease. Whether you are a seasoned Emacs user or a newcomer, Flux can serve as a solid foundation for your configuration or a valuable resource to enhance your Emacs skills.

These guiding principles inform the design of Flux:

+ **Beyond the capabilities of a traditional IDE.** Flux is not just an IDE, it's a next-generation coding platform that pushes the boundaries of what an IDE can do. With Flux, you get access to a powerful suite of tools and packages that are simply not available in traditional IDEs.
+ **Unmatched power and performance.** Flux's cutting-edge technology provides unparalleled power and performance. With optimized packages and lazy loading, you'll experience lightning-fast coding that simply isn't possible with other IDEs.
+ **Limitless customization and extensibility.** Flux's modular design and built-in package management system make it easy to customize your environment to suit your specific needs. With Flux, you can extend your coding capabilities beyond what you thought was possible, creating a truly unique and tailored coding experience.
+ **User-focused design philosophy.** Flux puts the user at the center of everything it does. Flux's flexible design and respect for user preferences mean you can create a coding environment that is perfectly suited to your style and workflow.
+ **Comprehensive documentation and support.**  Flux's built-in installer and comprehensive documentation system make it easy for new users to get started, while advanced users can take advantage of the extensive support available from the Flux community. With Flux, you're never alone in your coding journey.


# Prerequisites
+ Emacs 24.5+
+ Git (Optional, but needed for magit)
+ Windows 7+ (If you are using windows)


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
+ Check out the [FAQ] in case your question has already been answered.
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
