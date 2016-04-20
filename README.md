# The Black Hack

This project publishes the "raw text" of the Roleplaying game "The Black Hack", by David Black. As specified in the [License](LICENSE) document, the text and tables are *open game content*.

It means that anyone can use this *open game content* and make derivative works without asking for permission, as long as this derivative fits the [Open Gaming License terms](http://www.opengamingfoundation.org/ogl.html).

[![GitHub tag](https://img.shields.io/github/tag/brunobord/the-black-hack.svg?maxAge=2592000)]() [![Travis](https://img.shields.io/travis/brunobord/the-black-hack.svg?maxAge=2592000)]()

## Contribute

### Fix

Despite my keen eyes, I may have failed to correctly copy-paste the raw text and tables. Please ping me via this project issues or via [Twitter](https://twitter.com/brunobord) or [G+](https://plus.google.com/+brunobord) if you spot any typo to be fixed.

### Translate

The main purpose of this project is to allow translations of this *open game content* into other languages.

#### How-to

Let's say you want to translate "The Black Hack" into Klingon.

##### If you know how to use Github

1. fork this project on github,
2. on your local copy, create a `klingon` directory,
3. in this directory, create a ``meta.yaml`` file. This file is plain text and should be exactly like the [english/meta.yaml](english/meta.yaml) file, See the "meta" for more details.
4. in this directory, create a `the-black-hack.md` file and start translating. This file should fit the [Github Markdown](https://help.github.com/articles/basic-writing-and-formatting-syntax/) syntax,
5. when you're done, submit a [pull-request](https://help.github.com/articles/creating-a-pull-request/),
6. there may be a few discussion about your translation (mostly about the Markdown syntax). When the pull-request is "ok", it'll be merged into the main repository.

##### If you don't know how Github is working

Contact me via [e-mail](http://jehaisleprintemps.net/contact/) or [Twitter](https://twitter.com/brunobord) or [G+](https://plus.google.com/+brunobord) or any mean you can find and send me over a **raw text** translation of the game. I'll try to add it to the project ; and I may ask you to eventually help me to integrate it as best as possible.

Congratulations, you have contributed to this project

#### Make sure your contribution is okay

If you're geeky enough, you can try to use the command: ``make html`` to build HTML pages into the `build/` directory. It only requires that (a recent version of) [tox](http://tox.readthedocs.org/) is available on your system.

Browse the `build/` directory with your web browser to see your translation along with the others.

#### The Meta file

The meta file is a [YAML](http://yaml.org/), but it shouldn't be a problem. Your "klingon" meta file should look like this:

```yaml
label: Klingon
author: B'Elanna Torres
```

**Important**

* The meta file is completely optional, but it'll help improve the look'n'feel of the homepage.
* the words `label` and `author` are case sensitive, so they'll *have* to be written exactly like this.
* the `author` information is optional, although I'd recommend to provide it, in order to receive feedback (including praises from the community).

----

## References

* [David Black G+ Profile](https://plus.google.com/112905476698977529502),
* [David Black blog](http://dngnsndrgns.blogspot.fr/),
* [Square Hex](http://squarehex.myshopify.com/),
* The (very successful) [Kickstarter campaign](https://www.kickstarter.com/projects/1730454032/the-black-hack),
* [The Black Hack G+ Community](https://plus.google.com/communities/107832933727516137622),
* [The Open Gaming License](http://www.opengamingfoundation.org/ogl.html).
