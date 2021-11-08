# A work in progress

This is the core library for a a flat file based web publishing system.  It is simple, but flexible, working with Markdown files, HTML files, and JSON files.  By itself this application provides the sort of backend plumbing you need for a website, there is a separate CLI for interacting with the library from the command line and a web server app for creating static sites locally.  Right now this app simply organizes the data into types, converts Markdown to HTML via [Comrak](https://crates.io/crates/comrak), provides some things like XML sitemaps, menus and their structure, some page metadata and that's about it.

We'll see where it goes from here.