# Hiconic

`Hiconic` is an open-source general-purpose technology for building software with paradigms worthy of the 21st century.

## Short Intro

The essence of `Hiconic` is a (new) paradigm based on consequent application of modeling to different aspects of SW development. 

On the **lowest level** we offer what can be considered an **extension of the programming language** - a type system dedicated for defining entities (data types). This contrasts with languages usually using classes with fields and getters/setters, which frankly sucks.

Our **data types are treated as first class citizens**, allowing much more nimble and flexible data manipulation than classes. E.g. our types have their own reflection, which treats them as entities with properties rather than classes with methods. This makes writing generic algorithms and useful APIs easy, and it comes very naturally.

On top we have a whole ecosystem (for lack of a better word) of tools/extensions/platforms that take advantage of the **model-driven approach**. Over the years we've kept applying modeling to many aspects of SW, as it turned out to lead to **significantly more robust architectures** (see the link to `Our Vision` below for more details).

For the record, we offer this technology for both `Java` and `JavaScript`.

## Products

#### Reflex Platform

The primary "product" showcasing the model-driven paradigm is a platform called `Reflex`, an alternative to e.g. `Spring Boot` or `Quarkus`. It applies modeling across many domains like _configuration_, _APIs_, _error handling_ and more, leading to intuitive designs and lots of convention of over configuration.

#### Spring Boot Extensions (coming soon)

Seeing the enormous popularity of **`Spring Boot`**, we are also working on an integration for this platform. Stay tuned!

#### hiconic.js

We also offer a `JavScript` library (with `TypeScript` declarations) called `hiconic.js`. It manifests our core technology (espacially support for modeling), is perfectly compatible with the `Java` based back-ends, and runs in the browser as well as on `Node.js`.

👉 If you have any questions [join our Discord](https://discord.gg/S4BVrpdAHz).


## Documentation
* [Our Vision](https://hiconic-os.github.io/hiconic.about/posts/vision.html) - **high level introduction** to our technology
* [Reflex - Getting started](https://hiconic-os.github.io/hiconic.platform.reflex/getting-started/getting-started.html) - simple tutorial for our **microservices platform**
* [Reflex - Home](https://hiconic-os.github.io/hiconic.platform.reflex/) - home of our **microservices platform**


## Downloads
* [Hiconic SDK (latest)](https://api.hiconic-os.org/dowload-latest-artifact-part.php?groupId=tribefire.extension.setup&artifactId=hiconic-sdk&type=zip)


## Eclipse Plugins
Location: `https://eclipse.hiconic-os.org/beta`


## Tech Overview Documents
* [Introduction to the GenericModel Invention [EN] (pdf)](https://hiconic-os.github.io/web-resources/technical-overview/gm-invention.en.pdf)
* [Einführung in die GenericModel Erfindung [DE] (pdf)](https://hiconic-os.github.io/web-resources/technical-overview/gm-invention.de.pdf)
* [High-Level Overview - Slides (pdf)](https://hiconic-os.github.io/web-resources/technical-overview/hiconic-highlevel-slides.pdf)
* [Practical Relevance for Distributed Computing (pdf)](https://hiconic-os.github.io/web-resources/technical-overview/relevance-for-distributed-computing.pdf)
* [Projektskizze für Forschungsantrag [DE] (pdf)](https://hiconic-os.github.io/web-resources/technical-overview/projektskizze.pdf)
* [US Patent (pdf)](https://patentimages.storage.googleapis.com/fb/43/c3/6a7041491ebdf8/US10095488.pdf)


## For Contributors

* [Go to README for contributors...](https://github.com/hiconic-os/.github/blob/main/profile/README-CONTRIBUTORS.md)
* [Builds Status](https://github.com/hiconic-os/.github/blob/main/profile/builds-status.md)
