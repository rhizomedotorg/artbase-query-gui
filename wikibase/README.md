# The ArtBase SPARQL query GUI

This repository is a fork of Wikimedia's release of the [Wikidata Query GUI](https://github.com/wikimedia/wikidata-query-gui), with adaptions required to make it work with Rhizome's [ArtBase](https://artbase.rhizome.org), an independently operated instance of Wikibase.

The goal of this fork was to make all critical features of the Wikidata Query Service work for users of the ArtBase:
* Support Rhizome's custom URL prefixes in the SPARQL text editor, including support for autocompletion.
* Make the GUI query builder work with Rhizome's Wikibase.
* Support displaying local images in addition to Commons images in query results.
* Provide custom sample queries.
* Customize the GUI to at least remove elements that do not work / seem abandoned by developers, or are too confusing for our purposes.
* Light branding.
* Be a drop-in replacement for wdqs container in the [official Wikibase docker setup](https://github.com/wmde/wikibase-docker/).

This fork is based on initial work by [Professional.Wiki](https://github.com/ProfessionalWiki/), which was [submitted](https://gerrit.wikimedia.org/r/c/wikidata/query/gui/+/630871) to Wikimedia's Gerrit source code platform, but not merged.

:fire: **[All code changes are annotated](https://github.com/rhizomedotorg/artbase-query-gui/commit/29ce17b225a3fb9d9bcd16896778f94495fdf9c9)** so that the **customizations can be abstracted into configuration** in the future. The annotations present where the query GUI's code would need to introduce variables or configuration files.

---

→ [Original README file for this repository](README_wmde.md)





