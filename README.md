# Résumé

This is my personal résumé in the JSON format.

[![Build Status](https://travis-ci.org/zmoog/resume.svg?branch=master)](https://travis-ci.org/zmoog/resume)

## Where can I find the rendered version?

This resume is available in multiple formats that are built automatically using [Travis CI](https://travis-ci.org/zmoog/resume/builds) each time I push new commits to the master branch.

Here's the most common formats:

* [resume.pdf](https://s3-eu-west-1.amazonaws.com/zmoog-resume/out/resume.pdf)
* [resume.html](https://s3-eu-west-1.amazonaws.com/zmoog-resume/out/resume.html)
* [resume.md](https://s3-eu-west-1.amazonaws.com/zmoog-resume/out/resume.md)
* [resume.txt](https://s3-eu-west-1.amazonaws.com/zmoog-resume/out/resume.txt)


## How to build this resume?

### Requirements

* Node — I've used v8.10.0.
* If you want to build the PDF version you must install Python 3.4+ and [WeasyPrint](https://weasyprint.readthedocs.io/en/latest/).


### Install

```bash
$ npm install 
```

### Build

```bash
$ npm run build
```

