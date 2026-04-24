# README

## Version: 0.1

This code implements a NFA to DFA converter. I made it in 2020 for the purpose of checking my exercises during a lecture in theoretical computer science. This project aims to rewrite and expand this simple code until it performs the conversion correctly and minimizes the result.
Another goal is to keep this tool in a single HTML file, no `npm` or similar needed for installation and no subfolders for CSS and JavaScript. In my humble opinion, this is the fastest way to deploy such simple software that does not need any dependencies or databases.



### TODO

- Add support for &epsilon; - enclosure. There was no need for it when i wrote this, so this tool does not support it yet.
- Create a better UI
- Add minimization support for the resulting DFAs
