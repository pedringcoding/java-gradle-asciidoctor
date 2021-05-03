# Generate documents with asciidoctor [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

## :clipboard: Introduction

We all have families who tell us "take a look at the laptop that is slow for me", we usually have to deal with the generation of documents. If we need to generate an installation guide, documents available to use in our project, or any other need and we want:

* Make it as automatable as possible. It is cumbersome to have a word, which somewhere is needed in PDF, in another HTML, ... All of them kept on our repository (Git, SVN or whatever is appropriate).
* Don't let the editor distract us by applying text auto-formats all the time. Microsoft Word and the like (LibreOffice?) Is NOT what we need.

[AsciiDoctor](https://asciidoctor.org/) will function as an abstraction interface on all of this. Format complexity and coupling to document editing software.

## :cloud: Getting Started

Follow along this notes. You will need to have at least [Java 8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) installed or some openJDK distribution, and [Gradle](https://gradle.org/) on the PATH. Clone this repository, and fire up a command-line tool.

> To know the document as code technique , It necessary check diff between _use editor_ and _markdown code_ to generate documents

## :computer: Commands to execute

```
gradle asciidoctor
```

## :coffee: Buy us a coffee

I will continue to do things and expose notes, but donations are one of the many ways to support what I do. <a href="https://www.buymeacoffee.com/pedringcoding" title="Donate to this content using BuyMeACoffee">Contribute</a>
