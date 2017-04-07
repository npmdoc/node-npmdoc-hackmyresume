# api documentation for  [hackmyresume (v1.8.0)](https://github.com/hacksalot/HackMyResume)  [![npm package](https://img.shields.io/npm/v/npmdoc-hackmyresume.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hackmyresume) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hackmyresume.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hackmyresume)
#### Generate polished résumés and CVs in HTML, Markdown, LaTeX, MS Word, PDF, plain text, JSON, XML, YAML, smoke signal, and carrier pigeon.

[![NPM](https://nodei.co/npm/hackmyresume.png?downloads=true)](https://www.npmjs.com/package/hackmyresume)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hackmyresume/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-hackmyresume_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hackmyresume/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hackmyresume/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hackmyresume/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "hacksalot",
        "email": "hacksalot@indevious.com",
        "url": "https://github.com/hacksalot"
    },
    "bin": {
        "hackmyresume": "dist/cli/index.js"
    },
    "bugs": {
        "url": "https://github.com/hacksalot/HackMyResume/issues"
    },
    "contributors": [
        {
            "name": "aruberto",
            "url": "https://github.com/aruberto"
        },
        {
            "name": "jjanusch",
            "url": "https://github.com/driftdev"
        },
        {
            "name": "robertmain",
            "url": "https://github.com/robertmain"
        },
        {
            "name": "tomheon",
            "url": "https://github.com/tomheon"
        },
        {
            "name": "zhuangya",
            "url": "https://github.com/zhuangya"
        },
        {
            "name": "hacksalot",
            "email": "hacksalot@indevious.com",
            "url": "https://github.com/hacksalot"
        }
    ],
    "dependencies": {
        "chalk": "^1.1.1",
        "commander": "^2.9.0",
        "copy": "^0.1.3",
        "escape-latex": "^0.1.2",
        "extend": "^3.0.0",
        "fresca": "~0.6.0",
        "fresh-jrs-converter": "^0.2.2",
        "fresh-resume-starter": "^0.2.2",
        "fresh-themes": "^0.15.1-beta",
        "fs-extra": "^0.26.4",
        "handlebars": "^4.0.5",
        "html": "0.0.10",
        "is-my-json-valid": "^2.12.4",
        "json-lint": "^0.1.0",
        "jsonlint": "^1.6.2",
        "lodash": "^3.10.1",
        "marked": "^0.3.5",
        "mkdirp": "^0.5.1",
        "moment": "^2.11.1",
        "parse-filepath": "^0.6.3",
        "path-exists": "^2.1.0",
        "pinkie-promise": "^2.0.0",
        "printf": "^0.2.3",
        "recursive-readdir-sync": "^1.0.6",
        "simple-html-tokenizer": "^0.2.1",
        "slash": "^1.0.0",
        "string-padding": "^1.0.2",
        "string.prototype.endswith": "^0.2.0",
        "string.prototype.startswith": "^0.2.0",
        "traverse": "^0.6.6",
        "underscore": "^1.8.3",
        "word-wrap": "^1.1.0",
        "xml-escape": "^1.0.0",
        "yamljs": "^0.2.4"
    },
    "description": "Generate polished résumés and CVs in HTML, Markdown, LaTeX, MS Word, PDF, plain text, JSON, XML, YAML, smoke signal, and carrier pigeon.",
    "devDependencies": {
        "chai": "*",
        "dir-compare": "0.0.2",
        "fresh-test-resumes": "^0.7.0",
        "grunt": "*",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-clean": "^0.7.0",
        "grunt-contrib-coffee": "^0.13.0",
        "grunt-contrib-copy": "^0.8.2",
        "grunt-contrib-jshint": "^0.11.3",
        "grunt-contrib-yuidoc": "^0.10.0",
        "grunt-jsdoc": "^1.1.0",
        "grunt-simple-mocha": "*",
        "jsonresume-theme-boilerplate": "^0.1.2",
        "jsonresume-theme-classy": "^1.0.9",
        "jsonresume-theme-modern": "0.0.18",
        "jsonresume-theme-sceptile": "^1.0.5",
        "mocha": "*",
        "resample": "github:fluentdesk/resample",
        "stripcolorcodes": "^0.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ce2b4cb7e1c27a0cabacaf25cdb4b7c8c9b999e1",
        "tarball": "https://registry.npmjs.org/hackmyresume/-/hackmyresume-1.8.0.tgz"
    },
    "gitHead": "3cf850ea0e956ca5162c792ad8dc03cc621cf79a",
    "homepage": "https://github.com/hacksalot/HackMyResume",
    "keywords": [
        "resume",
        "CV",
        "portfolio",
        "employment",
        "career",
        "Markdown",
        "JSON",
        "Word",
        "PDF",
        "YAML",
        "HTML",
        "LaTeX",
        "CLI",
        "Handlebars",
        "Underscore",
        "template"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "hacksalot",
            "email": "hacksalot@fluentdesk.com"
        }
    ],
    "name": "hackmyresume",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hacksalot/HackMyResume.git"
    },
    "scripts": {
        "grunt": "grunt",
        "test": "grunt clean:test && mocha"
    },
    "version": "1.8.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module hackmyresume](#apidoc.module.hackmyresume)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>FRESHResume ()](#apidoc.element.hackmyresume.FRESHResume)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>FRESHTheme ()](#apidoc.element.hackmyresume.FRESHTheme)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>FluentDate (dt)](#apidoc.element.hackmyresume.FluentDate)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>HtmlGenerator ()](#apidoc.element.hackmyresume.HtmlGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>HtmlPdfCliGenerator ()](#apidoc.element.hackmyresume.HtmlPdfCliGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>HtmlPngGenerator ()](#apidoc.element.hackmyresume.HtmlPngGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>JRSResume ()](#apidoc.element.hackmyresume.JRSResume)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>JRSTheme ()](#apidoc.element.hackmyresume.JRSTheme)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>JsonGenerator ()](#apidoc.element.hackmyresume.JsonGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>JsonYamlGenerator ()](#apidoc.element.hackmyresume.JsonYamlGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>LaTeXGenerator ()](#apidoc.element.hackmyresume.LaTeXGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>MarkdownGenerator ()](#apidoc.element.hackmyresume.MarkdownGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>Sheet ()](#apidoc.element.hackmyresume.Sheet)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>TextGenerator ()](#apidoc.element.hackmyresume.TextGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>WordGenerator ()](#apidoc.element.hackmyresume.WordGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>YamlGenerator ()](#apidoc.element.hackmyresume.YamlGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>alias.create ()](#apidoc.element.hackmyresume.alias.create)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>alias.generate ()](#apidoc.element.hackmyresume.alias.generate)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>verbs.analyze ()](#apidoc.element.hackmyresume.verbs.analyze)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>verbs.convert ()](#apidoc.element.hackmyresume.verbs.convert)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>verbs.peek ()](#apidoc.element.hackmyresume.verbs.peek)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>verbs.validate ()](#apidoc.element.hackmyresume.verbs.validate)
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>FRESHTheme.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>HtmlGenerator.__super__
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>HtmlGenerator.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>HtmlPdfCliGenerator.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>HtmlPngGenerator.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>JRSResume.__super__
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>JRSResume.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>JRSTheme.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>JsonGenerator.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>JsonYamlGenerator.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>LaTeXGenerator.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>MarkdownGenerator.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>ResumeFactory
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>Sheet.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>TextGenerator.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>WordGenerator.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>YamlGenerator.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>alias
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>alias.create.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>alias.generate.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>formats
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>options
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>verbs
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>verbs.analyze.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>verbs.convert.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>verbs.peek.prototype
1.  object <span class="apidocSignatureSpan">hackmyresume.</span>verbs.validate.prototype

#### [module hackmyresume.FRESHTheme](#apidoc.module.hackmyresume.FRESHTheme)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>FRESHTheme ()](#apidoc.element.hackmyresume.FRESHTheme.FRESHTheme)

#### [module hackmyresume.FRESHTheme.prototype](#apidoc.module.hackmyresume.FRESHTheme.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.FRESHTheme.prototype.</span>getFormat (fmt)](#apidoc.element.hackmyresume.FRESHTheme.prototype.getFormat)
1.  [function <span class="apidocSignatureSpan">hackmyresume.FRESHTheme.prototype.</span>hasFormat (fmt)](#apidoc.element.hackmyresume.FRESHTheme.prototype.hasFormat)
1.  [function <span class="apidocSignatureSpan">hackmyresume.FRESHTheme.prototype.</span>open (themeFolder)](#apidoc.element.hackmyresume.FRESHTheme.prototype.open)

#### [module hackmyresume.FluentDate](#apidoc.module.hackmyresume.FluentDate)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>FluentDate (dt)](#apidoc.element.hackmyresume.FluentDate.FluentDate)
1.  [function <span class="apidocSignatureSpan">hackmyresume.FluentDate.</span>fmt (dt, throws)](#apidoc.element.hackmyresume.FluentDate.fmt)
1.  [function <span class="apidocSignatureSpan">hackmyresume.FluentDate.</span>isCurrent (dt)](#apidoc.element.hackmyresume.FluentDate.isCurrent)

#### [module hackmyresume.HtmlGenerator](#apidoc.module.hackmyresume.HtmlGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>HtmlGenerator ()](#apidoc.element.hackmyresume.HtmlGenerator.HtmlGenerator)
1.  object <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.</span>__super__

#### [module hackmyresume.HtmlGenerator.__super__](#apidoc.module.hackmyresume.HtmlGenerator.__super__)
1.  [function <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.__super__.</span>constructor (outputFormat, templateFormat, cssFile)](#apidoc.element.hackmyresume.HtmlGenerator.__super__.constructor)
1.  [function <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.__super__.</span>generate (rez, f, opts)](#apidoc.element.hackmyresume.HtmlGenerator.__super__.generate)
1.  [function <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.__super__.</span>invoke (rez, opts)](#apidoc.element.hackmyresume.HtmlGenerator.__super__.invoke)
1.  [function <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.__super__.</span>transform (json, jst, format, opts, theme, curFmt)](#apidoc.element.hackmyresume.HtmlGenerator.__super__.transform)

#### [module hackmyresume.HtmlGenerator.prototype](#apidoc.module.hackmyresume.HtmlGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.HtmlGenerator.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.prototype.</span>onBeforeSave (info)](#apidoc.element.hackmyresume.HtmlGenerator.prototype.onBeforeSave)

#### [module hackmyresume.HtmlPdfCliGenerator](#apidoc.module.hackmyresume.HtmlPdfCliGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>HtmlPdfCliGenerator ()](#apidoc.element.hackmyresume.HtmlPdfCliGenerator.HtmlPdfCliGenerator)
1.  object <span class="apidocSignatureSpan">hackmyresume.HtmlPdfCliGenerator.</span>__super__

#### [module hackmyresume.HtmlPdfCliGenerator.prototype](#apidoc.module.hackmyresume.HtmlPdfCliGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.HtmlPdfCliGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.HtmlPdfCliGenerator.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">hackmyresume.HtmlPdfCliGenerator.prototype.</span>onBeforeSave (info)](#apidoc.element.hackmyresume.HtmlPdfCliGenerator.prototype.onBeforeSave)
1.  [function <span class="apidocSignatureSpan">hackmyresume.HtmlPdfCliGenerator.prototype.</span>onError (ex, param)](#apidoc.element.hackmyresume.HtmlPdfCliGenerator.prototype.onError)

#### [module hackmyresume.HtmlPngGenerator](#apidoc.module.hackmyresume.HtmlPngGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>HtmlPngGenerator ()](#apidoc.element.hackmyresume.HtmlPngGenerator.HtmlPngGenerator)
1.  object <span class="apidocSignatureSpan">hackmyresume.HtmlPngGenerator.</span>__super__

#### [module hackmyresume.HtmlPngGenerator.prototype](#apidoc.module.hackmyresume.HtmlPngGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.HtmlPngGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.HtmlPngGenerator.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">hackmyresume.HtmlPngGenerator.prototype.</span>generate (rez, f, opts)](#apidoc.element.hackmyresume.HtmlPngGenerator.prototype.generate)
1.  [function <span class="apidocSignatureSpan">hackmyresume.HtmlPngGenerator.prototype.</span>invoke (rez, themeMarkup, cssInfo, opts)](#apidoc.element.hackmyresume.HtmlPngGenerator.prototype.invoke)

#### [module hackmyresume.JRSResume](#apidoc.module.hackmyresume.JRSResume)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>JRSResume ()](#apidoc.element.hackmyresume.JRSResume.JRSResume)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.</span>default ()](#apidoc.element.hackmyresume.JRSResume.default)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.</span>stringify (obj)](#apidoc.element.hackmyresume.JRSResume.stringify)
1.  object <span class="apidocSignatureSpan">hackmyresume.JRSResume.</span>__super__

#### [module hackmyresume.JRSResume.__super__](#apidoc.module.hackmyresume.JRSResume.__super__)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.__super__.</span>duration (collKey, startKey, endKey, unit)](#apidoc.element.hackmyresume.JRSResume.__super__.duration)

#### [module hackmyresume.JRSResume.prototype](#apidoc.module.hackmyresume.JRSResume.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>add (moniker)](#apidoc.element.hackmyresume.JRSResume.prototype.add)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>constructor ()](#apidoc.element.hackmyresume.JRSResume.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>dupe ()](#apidoc.element.hackmyresume.JRSResume.prototype.dupe)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>duration (unit)](#apidoc.element.hackmyresume.JRSResume.prototype.duration)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>format ()](#apidoc.element.hackmyresume.JRSResume.prototype.format)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>harden ()](#apidoc.element.hackmyresume.JRSResume.prototype.harden)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>hasProfile (socialNetwork)](#apidoc.element.hackmyresume.JRSResume.prototype.hasProfile)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>hasSkill (skill)](#apidoc.element.hackmyresume.JRSResume.prototype.hasSkill)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>i ()](#apidoc.element.hackmyresume.JRSResume.prototype.i)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>isValid ()](#apidoc.element.hackmyresume.JRSResume.prototype.isValid)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>keywords ()](#apidoc.element.hackmyresume.JRSResume.prototype.keywords)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>parse (stringData, opts)](#apidoc.element.hackmyresume.JRSResume.prototype.parse)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>parseJSON (rep, opts)](#apidoc.element.hackmyresume.JRSResume.prototype.parseJSON)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>save (filename)](#apidoc.element.hackmyresume.JRSResume.prototype.save)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>saveAs (filename, format)](#apidoc.element.hackmyresume.JRSResume.prototype.saveAs)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>sort ()](#apidoc.element.hackmyresume.JRSResume.prototype.sort)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>stringify ()](#apidoc.element.hackmyresume.JRSResume.prototype.stringify)

#### [module hackmyresume.JRSTheme](#apidoc.module.hackmyresume.JRSTheme)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>JRSTheme ()](#apidoc.element.hackmyresume.JRSTheme.JRSTheme)

#### [module hackmyresume.JRSTheme.prototype](#apidoc.module.hackmyresume.JRSTheme.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSTheme.prototype.</span>getFormat (fmt)](#apidoc.element.hackmyresume.JRSTheme.prototype.getFormat)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSTheme.prototype.</span>hasFormat (fmt)](#apidoc.element.hackmyresume.JRSTheme.prototype.hasFormat)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JRSTheme.prototype.</span>open (thFolder)](#apidoc.element.hackmyresume.JRSTheme.prototype.open)

#### [module hackmyresume.JsonGenerator](#apidoc.module.hackmyresume.JsonGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>JsonGenerator ()](#apidoc.element.hackmyresume.JsonGenerator.JsonGenerator)
1.  object <span class="apidocSignatureSpan">hackmyresume.JsonGenerator.</span>__super__

#### [module hackmyresume.JsonGenerator.prototype](#apidoc.module.hackmyresume.JsonGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JsonGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.JsonGenerator.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JsonGenerator.prototype.</span>generate (rez, f)](#apidoc.element.hackmyresume.JsonGenerator.prototype.generate)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JsonGenerator.prototype.</span>invoke (rez)](#apidoc.element.hackmyresume.JsonGenerator.prototype.invoke)

#### [module hackmyresume.JsonYamlGenerator](#apidoc.module.hackmyresume.JsonYamlGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>JsonYamlGenerator ()](#apidoc.element.hackmyresume.JsonYamlGenerator.JsonYamlGenerator)
1.  object <span class="apidocSignatureSpan">hackmyresume.JsonYamlGenerator.</span>__super__

#### [module hackmyresume.JsonYamlGenerator.prototype](#apidoc.module.hackmyresume.JsonYamlGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JsonYamlGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.JsonYamlGenerator.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JsonYamlGenerator.prototype.</span>generate (rez, f, opts)](#apidoc.element.hackmyresume.JsonYamlGenerator.prototype.generate)
1.  [function <span class="apidocSignatureSpan">hackmyresume.JsonYamlGenerator.prototype.</span>invoke (rez, themeMarkup, cssInfo, opts)](#apidoc.element.hackmyresume.JsonYamlGenerator.prototype.invoke)

#### [module hackmyresume.LaTeXGenerator](#apidoc.module.hackmyresume.LaTeXGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>LaTeXGenerator ()](#apidoc.element.hackmyresume.LaTeXGenerator.LaTeXGenerator)
1.  object <span class="apidocSignatureSpan">hackmyresume.LaTeXGenerator.</span>__super__

#### [module hackmyresume.LaTeXGenerator.prototype](#apidoc.module.hackmyresume.LaTeXGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.LaTeXGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.LaTeXGenerator.prototype.constructor)

#### [module hackmyresume.MarkdownGenerator](#apidoc.module.hackmyresume.MarkdownGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>MarkdownGenerator ()](#apidoc.element.hackmyresume.MarkdownGenerator.MarkdownGenerator)
1.  object <span class="apidocSignatureSpan">hackmyresume.MarkdownGenerator.</span>__super__

#### [module hackmyresume.MarkdownGenerator.prototype](#apidoc.module.hackmyresume.MarkdownGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.MarkdownGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.MarkdownGenerator.prototype.constructor)

#### [module hackmyresume.ResumeFactory](#apidoc.module.hackmyresume.ResumeFactory)
1.  [function <span class="apidocSignatureSpan">hackmyresume.ResumeFactory.</span>load (sources, opts, emitter)](#apidoc.element.hackmyresume.ResumeFactory.load)
1.  [function <span class="apidocSignatureSpan">hackmyresume.ResumeFactory.</span>loadOne (src, opts, emitter)](#apidoc.element.hackmyresume.ResumeFactory.loadOne)

#### [module hackmyresume.Sheet](#apidoc.module.hackmyresume.Sheet)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>Sheet ()](#apidoc.element.hackmyresume.Sheet.Sheet)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.</span>default ()](#apidoc.element.hackmyresume.Sheet.default)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.</span>stringify (obj)](#apidoc.element.hackmyresume.Sheet.stringify)
1.  object <span class="apidocSignatureSpan">hackmyresume.Sheet.</span>__super__

#### [module hackmyresume.Sheet.prototype](#apidoc.module.hackmyresume.Sheet.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>add (moniker)](#apidoc.element.hackmyresume.Sheet.prototype.add)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>clear (clearMeta)](#apidoc.element.hackmyresume.Sheet.prototype.clear)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>constructor ()](#apidoc.element.hackmyresume.Sheet.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>count (obj)](#apidoc.element.hackmyresume.Sheet.prototype.count)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>dupe ()](#apidoc.element.hackmyresume.Sheet.prototype.dupe)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>duration (unit)](#apidoc.element.hackmyresume.Sheet.prototype.duration)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>format ()](#apidoc.element.hackmyresume.Sheet.prototype.format)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>getProfile (socialNetwork)](#apidoc.element.hackmyresume.Sheet.prototype.getProfile)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>getProfiles (socialNetwork)](#apidoc.element.hackmyresume.Sheet.prototype.getProfiles)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>hasProfile (socialNetwork)](#apidoc.element.hackmyresume.Sheet.prototype.hasProfile)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>hasSkill (skill)](#apidoc.element.hackmyresume.Sheet.prototype.hasSkill)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>i ()](#apidoc.element.hackmyresume.Sheet.prototype.i)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>isValid (info)](#apidoc.element.hackmyresume.Sheet.prototype.isValid)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>keywords ()](#apidoc.element.hackmyresume.Sheet.prototype.keywords)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>markdownify ()](#apidoc.element.hackmyresume.Sheet.prototype.markdownify)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>parse (stringData, opts)](#apidoc.element.hackmyresume.Sheet.prototype.parse)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>parseJSON (rep, opts)](#apidoc.element.hackmyresume.Sheet.prototype.parseJSON)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>save (filename)](#apidoc.element.hackmyresume.Sheet.prototype.save)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>saveAs (filename, format)](#apidoc.element.hackmyresume.Sheet.prototype.saveAs)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>sort ()](#apidoc.element.hackmyresume.Sheet.prototype.sort)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>stringify ()](#apidoc.element.hackmyresume.Sheet.prototype.stringify)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>transformStrings (filt, transformer)](#apidoc.element.hackmyresume.Sheet.prototype.transformStrings)
1.  [function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>xmlify ()](#apidoc.element.hackmyresume.Sheet.prototype.xmlify)

#### [module hackmyresume.TextGenerator](#apidoc.module.hackmyresume.TextGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>TextGenerator ()](#apidoc.element.hackmyresume.TextGenerator.TextGenerator)
1.  object <span class="apidocSignatureSpan">hackmyresume.TextGenerator.</span>__super__

#### [module hackmyresume.TextGenerator.prototype](#apidoc.module.hackmyresume.TextGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.TextGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.TextGenerator.prototype.constructor)

#### [module hackmyresume.WordGenerator](#apidoc.module.hackmyresume.WordGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>WordGenerator ()](#apidoc.element.hackmyresume.WordGenerator.WordGenerator)
1.  object <span class="apidocSignatureSpan">hackmyresume.WordGenerator.</span>__super__

#### [module hackmyresume.WordGenerator.prototype](#apidoc.module.hackmyresume.WordGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.WordGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.WordGenerator.prototype.constructor)

#### [module hackmyresume.YamlGenerator](#apidoc.module.hackmyresume.YamlGenerator)
1.  [function <span class="apidocSignatureSpan">hackmyresume.</span>YamlGenerator ()](#apidoc.element.hackmyresume.YamlGenerator.YamlGenerator)
1.  object <span class="apidocSignatureSpan">hackmyresume.YamlGenerator.</span>__super__

#### [module hackmyresume.YamlGenerator.prototype](#apidoc.module.hackmyresume.YamlGenerator.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.YamlGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.YamlGenerator.prototype.constructor)

#### [module hackmyresume.alias](#apidoc.module.hackmyresume.alias)
1.  [function <span class="apidocSignatureSpan">hackmyresume.alias.</span>create ()](#apidoc.element.hackmyresume.alias.create)
1.  [function <span class="apidocSignatureSpan">hackmyresume.alias.</span>generate ()](#apidoc.element.hackmyresume.alias.generate)

#### [module hackmyresume.alias.create](#apidoc.module.hackmyresume.alias.create)
1.  [function <span class="apidocSignatureSpan">hackmyresume.alias.</span>create ()](#apidoc.element.hackmyresume.alias.create.create)
1.  object <span class="apidocSignatureSpan">hackmyresume.alias.create.</span>__super__

#### [module hackmyresume.alias.create.prototype](#apidoc.module.hackmyresume.alias.create.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.alias.create.prototype.</span>constructor ()](#apidoc.element.hackmyresume.alias.create.prototype.constructor)

#### [module hackmyresume.alias.generate](#apidoc.module.hackmyresume.alias.generate)
1.  [function <span class="apidocSignatureSpan">hackmyresume.alias.</span>generate ()](#apidoc.element.hackmyresume.alias.generate.generate)
1.  object <span class="apidocSignatureSpan">hackmyresume.alias.generate.</span>__super__

#### [module hackmyresume.alias.generate.prototype](#apidoc.module.hackmyresume.alias.generate.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.alias.generate.prototype.</span>constructor ()](#apidoc.element.hackmyresume.alias.generate.prototype.constructor)

#### [module hackmyresume.verbs](#apidoc.module.hackmyresume.verbs)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>analyze ()](#apidoc.element.hackmyresume.verbs.analyze)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>build ()](#apidoc.element.hackmyresume.verbs.build)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>convert ()](#apidoc.element.hackmyresume.verbs.convert)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>new ()](#apidoc.element.hackmyresume.verbs.new)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>peek ()](#apidoc.element.hackmyresume.verbs.peek)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>validate ()](#apidoc.element.hackmyresume.verbs.validate)

#### [module hackmyresume.verbs.analyze](#apidoc.module.hackmyresume.verbs.analyze)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>analyze ()](#apidoc.element.hackmyresume.verbs.analyze.analyze)
1.  object <span class="apidocSignatureSpan">hackmyresume.verbs.analyze.</span>__super__

#### [module hackmyresume.verbs.analyze.prototype](#apidoc.module.hackmyresume.verbs.analyze.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.analyze.prototype.</span>constructor ()](#apidoc.element.hackmyresume.verbs.analyze.prototype.constructor)

#### [module hackmyresume.verbs.convert](#apidoc.module.hackmyresume.verbs.convert)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>convert ()](#apidoc.element.hackmyresume.verbs.convert.convert)
1.  object <span class="apidocSignatureSpan">hackmyresume.verbs.convert.</span>__super__

#### [module hackmyresume.verbs.convert.prototype](#apidoc.module.hackmyresume.verbs.convert.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.convert.prototype.</span>constructor ()](#apidoc.element.hackmyresume.verbs.convert.prototype.constructor)

#### [module hackmyresume.verbs.peek](#apidoc.module.hackmyresume.verbs.peek)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>peek ()](#apidoc.element.hackmyresume.verbs.peek.peek)
1.  object <span class="apidocSignatureSpan">hackmyresume.verbs.peek.</span>__super__

#### [module hackmyresume.verbs.peek.prototype](#apidoc.module.hackmyresume.verbs.peek.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.peek.prototype.</span>constructor ()](#apidoc.element.hackmyresume.verbs.peek.prototype.constructor)

#### [module hackmyresume.verbs.validate](#apidoc.module.hackmyresume.verbs.validate)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>validate ()](#apidoc.element.hackmyresume.verbs.validate.validate)
1.  object <span class="apidocSignatureSpan">hackmyresume.verbs.validate.</span>__super__

#### [module hackmyresume.verbs.validate.prototype](#apidoc.module.hackmyresume.verbs.validate.prototype)
1.  [function <span class="apidocSignatureSpan">hackmyresume.verbs.validate.prototype.</span>constructor ()](#apidoc.element.hackmyresume.verbs.validate.prototype.constructor)



# <a name="apidoc.module.hackmyresume"></a>[module hackmyresume](#apidoc.module.hackmyresume)

#### <a name="apidoc.element.hackmyresume.FRESHResume"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>FRESHResume ()](#apidoc.element.hackmyresume.FRESHResume)
- description and source-code
```javascript
function FreshResume() {
  return FreshResume.__super__.constructor.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.FRESHTheme"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>FRESHTheme ()](#apidoc.element.hackmyresume.FRESHTheme)
- description and source-code
```javascript
function FRESHTheme() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.FluentDate"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>FluentDate (dt)](#apidoc.element.hackmyresume.FluentDate)
- description and source-code
```javascript
function FluentDate(dt) {
  this.rep = this.fmt(dt);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.HtmlGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>HtmlGenerator ()](#apidoc.element.hackmyresume.HtmlGenerator)
- description and source-code
```javascript
function HtmlGenerator() {
  HtmlGenerator.__super__.constructor.call(this, 'html');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.HtmlPdfCliGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>HtmlPdfCliGenerator ()](#apidoc.element.hackmyresume.HtmlPdfCliGenerator)
- description and source-code
```javascript
function HtmlPdfCLIGenerator() {
  HtmlPdfCLIGenerator.__super__.constructor.call(this, 'pdf', 'html');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.HtmlPngGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>HtmlPngGenerator ()](#apidoc.element.hackmyresume.HtmlPngGenerator)
- description and source-code
```javascript
function HtmlPngGenerator() {
  HtmlPngGenerator.__super__.constructor.call(this, 'png', 'html');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>JRSResume ()](#apidoc.element.hackmyresume.JRSResume)
- description and source-code
```javascript
function JRSResume() {
  return JRSResume.__super__.constructor.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSTheme"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>JRSTheme ()](#apidoc.element.hackmyresume.JRSTheme)
- description and source-code
```javascript
function JRSTheme() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JsonGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>JsonGenerator ()](#apidoc.element.hackmyresume.JsonGenerator)
- description and source-code
```javascript
function JsonGenerator() {
  JsonGenerator.__super__.constructor.call(this, 'json');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JsonYamlGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>JsonYamlGenerator ()](#apidoc.element.hackmyresume.JsonYamlGenerator)
- description and source-code
```javascript
function JsonYamlGenerator() {
  JsonYamlGenerator.__super__.constructor.call(this, 'yml');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.LaTeXGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>LaTeXGenerator ()](#apidoc.element.hackmyresume.LaTeXGenerator)
- description and source-code
```javascript
function LaTeXGenerator() {
  LaTeXGenerator.__super__.constructor.call(this, 'latex', 'tex');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.MarkdownGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>MarkdownGenerator ()](#apidoc.element.hackmyresume.MarkdownGenerator)
- description and source-code
```javascript
function MarkdownGenerator() {
  MarkdownGenerator.__super__.constructor.call(this, 'md', 'txt');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>Sheet ()](#apidoc.element.hackmyresume.Sheet)
- description and source-code
```javascript
function FreshResume() {
  return FreshResume.__super__.constructor.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.TextGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>TextGenerator ()](#apidoc.element.hackmyresume.TextGenerator)
- description and source-code
```javascript
function TextGenerator() {
  TextGenerator.__super__.constructor.call(this, 'txt');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.WordGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>WordGenerator ()](#apidoc.element.hackmyresume.WordGenerator)
- description and source-code
```javascript
function WordGenerator() {
  WordGenerator.__super__.constructor.call(this, 'doc', 'xml');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.YamlGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>YamlGenerator ()](#apidoc.element.hackmyresume.YamlGenerator)
- description and source-code
```javascript
function YAMLGenerator() {
  YAMLGenerator.__super__.constructor.call(this, 'yml', 'yml');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.alias.create"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>alias.create ()](#apidoc.element.hackmyresume.alias.create)
- description and source-code
```javascript
function CreateVerb() {
  CreateVerb.__super__.constructor.call(this, 'new', _create);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.alias.generate"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>alias.generate ()](#apidoc.element.hackmyresume.alias.generate)
- description and source-code
```javascript
function BuildVerb() {
  BuildVerb.__super__.constructor.call(this, 'build', _build);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.verbs.analyze"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>verbs.analyze ()](#apidoc.element.hackmyresume.verbs.analyze)
- description and source-code
```javascript
function AnalyzeVerb() {
  AnalyzeVerb.__super__.constructor.call(this, 'analyze', _analyze);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.verbs.convert"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>verbs.convert ()](#apidoc.element.hackmyresume.verbs.convert)
- description and source-code
```javascript
function ConvertVerb() {
  ConvertVerb.__super__.constructor.call(this, 'convert', _convert);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.verbs.peek"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>verbs.peek ()](#apidoc.element.hackmyresume.verbs.peek)
- description and source-code
```javascript
function PeekVerb() {
  PeekVerb.__super__.constructor.call(this, 'peek', _peek);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.verbs.validate"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>verbs.validate ()](#apidoc.element.hackmyresume.verbs.validate)
- description and source-code
```javascript
function ValidateVerb() {
  ValidateVerb.__super__.constructor.call(this, 'validate', _validate);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.FRESHTheme"></a>[module hackmyresume.FRESHTheme](#apidoc.module.hackmyresume.FRESHTheme)

#### <a name="apidoc.element.hackmyresume.FRESHTheme.FRESHTheme"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>FRESHTheme ()](#apidoc.element.hackmyresume.FRESHTheme.FRESHTheme)
- description and source-code
```javascript
function FRESHTheme() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.FRESHTheme.prototype"></a>[module hackmyresume.FRESHTheme.prototype](#apidoc.module.hackmyresume.FRESHTheme.prototype)

#### <a name="apidoc.element.hackmyresume.FRESHTheme.prototype.getFormat"></a>[function <span class="apidocSignatureSpan">hackmyresume.FRESHTheme.prototype.</span>getFormat (fmt)](#apidoc.element.hackmyresume.FRESHTheme.prototype.getFormat)
- description and source-code
```javascript
getFormat = function (fmt) {
  return this.formats[fmt];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.FRESHTheme.prototype.hasFormat"></a>[function <span class="apidocSignatureSpan">hackmyresume.FRESHTheme.prototype.</span>hasFormat (fmt)](#apidoc.element.hackmyresume.FRESHTheme.prototype.hasFormat)
- description and source-code
```javascript
hasFormat = function (fmt) {
  return _.has(this.formats, fmt);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.FRESHTheme.prototype.open"></a>[function <span class="apidocSignatureSpan">hackmyresume.FRESHTheme.prototype.</span>open (themeFolder)](#apidoc.element.hackmyresume.FRESHTheme.prototype.open)
- description and source-code
```javascript
open = function (themeFolder) {
  var cached, formatsHash, pathInfo, that, themeFile, themeInfo;
  this.folder = themeFolder;
  pathInfo = parsePath(themeFolder);
  formatsHash = {};
  themeFile = PATH.join(themeFolder, 'theme.json');
  themeInfo = loadSafeJson(themeFile);
  if (themeInfo.ex) {
    throw {
      fluenterror: themeInfo.ex.operation === 'parse' ? HMSTATUS.parseError : HMSTATUS.readError,
      inner: themeInfo.ex.inner
    };
  }
  that = this;
  EXTEND(true, this, themeInfo.json);
  if (this.inherits) {
    cached = {};
    _.each(this.inherits, function(th, key) {
      var d, themePath, themesFolder;
      themesFolder = require.resolve('fresh-themes');
      d = parsePath(themeFolder).dirname;
      themePath = PATH.join(d, th);
      cached[th] = cached[th] || new FRESHTheme().open(themePath);
      return formatsHash[key] = cached[th].getFormat(key);
    });
  }
  formatsHash = _load.call(this, formatsHash);
  this.formats = formatsHash;
  this.name = parsePath(this.folder).name;
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.FluentDate"></a>[module hackmyresume.FluentDate](#apidoc.module.hackmyresume.FluentDate)

#### <a name="apidoc.element.hackmyresume.FluentDate.FluentDate"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>FluentDate (dt)](#apidoc.element.hackmyresume.FluentDate.FluentDate)
- description and source-code
```javascript
function FluentDate(dt) {
  this.rep = this.fmt(dt);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.FluentDate.fmt"></a>[function <span class="apidocSignatureSpan">hackmyresume.FluentDate.</span>fmt (dt, throws)](#apidoc.element.hackmyresume.FluentDate.fmt)
- description and source-code
```javascript
fmt = function (dt, throws) {
  var month, mt, parts, ref, temp;
  throws = (throws === void 0 || throws === null) || throws;
  if (typeof dt === 'string' || dt instanceof String) {
    dt = dt.toLowerCase().trim();
    if (/^(present|now|current)$/.test(dt)) {
      return moment();
    } else if (/^\D+\s+\d{4}$/.test(dt)) {
      parts = dt.split(' ');
      month = months[parts[0]] || abbr[parts[0]];
      temp = parts[1] + '-' + ((ref = month < 10) != null ? ref : '0' + {
        month: month.toString()
      });
      return moment(temp, 'YYYY-MM');
    } else if (/^\d{4}-\d{1,2}$/.test(dt)) {
      return moment(dt, 'YYYY-MM');
    } else if (/^\s*\d{4}\s*$/.test(dt)) {
      return moment(dt, 'YYYY');
    } else if (/^\s*$/.test(dt)) {
      return moment();
    } else {
      mt = moment(dt);
      if (mt.isValid()) {
        return mt;
      }
      if (throws) {
        throw 'Invalid date format encountered.';
      }
      return null;
    }
  } else {
    if (!dt) {
      return moment();
    } else if (dt.isValid && dt.isValid()) {
      return dt;
    }
    if (throws) {
      throw 'Unknown date object encountered.';
    }
    return null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.FluentDate.isCurrent"></a>[function <span class="apidocSignatureSpan">hackmyresume.FluentDate.</span>isCurrent (dt)](#apidoc.element.hackmyresume.FluentDate.isCurrent)
- description and source-code
```javascript
isCurrent = function (dt) {
  return !dt || (String.is(dt) && /^(present|now|current)$/.test(dt));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.HtmlGenerator"></a>[module hackmyresume.HtmlGenerator](#apidoc.module.hackmyresume.HtmlGenerator)

#### <a name="apidoc.element.hackmyresume.HtmlGenerator.HtmlGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>HtmlGenerator ()](#apidoc.element.hackmyresume.HtmlGenerator.HtmlGenerator)
- description and source-code
```javascript
function HtmlGenerator() {
  HtmlGenerator.__super__.constructor.call(this, 'html');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.HtmlGenerator.__super__"></a>[module hackmyresume.HtmlGenerator.__super__](#apidoc.module.hackmyresume.HtmlGenerator.__super__)

#### <a name="apidoc.element.hackmyresume.HtmlGenerator.__super__.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.__super__.</span>constructor (outputFormat, templateFormat, cssFile)](#apidoc.element.hackmyresume.HtmlGenerator.__super__.constructor)
- description and source-code
```javascript
function TemplateGenerator(outputFormat, templateFormat, cssFile) {
  TemplateGenerator.__super__.constructor.call(this, outputFormat);
  this.tplFormat = templateFormat || outputFormat;
  return;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.HtmlGenerator.__super__.generate"></a>[function <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.__super__.</span>generate (rez, f, opts)](#apidoc.element.hackmyresume.HtmlGenerator.__super__.generate)
- description and source-code
```javascript
generate = function (rez, f, opts) {
  var curFmt, genInfo, outFolder;
  this.opts = EXTEND(true, {}, _defaultOpts, opts);
  genInfo = this.invoke(rez, null);
  outFolder = parsePath(f).dirname;
  curFmt = opts.themeObj.getFormat(this.format);
  genInfo.files.forEach(function(file) {
    var thisFilePath;
    file.info.orgPath = file.info.orgPath || '';
    thisFilePath = file.info.primary ? f : PATH.join(outFolder, file.info.orgPath);
    if (file.info.action !== 'copy' && this.onBeforeSave) {
      file.data = this.onBeforeSave({
        theme: opts.themeObj,
        outputFile: thisFilePath,
        mk: file.data,
        opts: this.opts,
        ext: file.info.ext
      });
      if (!file.data) {
        return;
      }
    }
    if (typeof opts.beforeWrite === "function") {
      opts.beforeWrite(thisFilePath);
    }
    MKDIRP.sync(PATH.dirname(thisFilePath));
    if (file.info.action !== 'copy') {
      FS.writeFileSync(thisFilePath, file.data, {
        encoding: 'utf8',
        flags: 'w'
      });
    } else {
      FS.copySync(file.info.path, thisFilePath);
    }
    if (typeof opts.afterWrite === "function") {
      opts.afterWrite(thisFilePath);
    }
    if (this.onAfterSave) {
      return this.onAfterSave({
        outputFile: fileName,
        mk: file.data,
        opts: this.opts
      });
    }
  }, this);
  createSymLinks(curFmt, outFolder);
  return genInfo;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.HtmlGenerator.__super__.invoke"></a>[function <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.__super__.</span>invoke (rez, opts)](#apidoc.element.hackmyresume.HtmlGenerator.__super__.invoke)
- description and source-code
```javascript
invoke = function (rez, opts) {
  var curFmt, results;
  opts = opts ? (this.opts = EXTEND(true, {}, _defaultOpts, opts)) : this.opts;
  curFmt = opts.themeObj.getFormat(this.format);
  curFmt.files = _.sortBy(curFmt.files, function(fi) {
    return fi.ext !== 'css';
  });
  results = curFmt.files.map(function(tplInfo, idx) {
    var trx;
    if (tplInfo.action === 'transform') {
      trx = this.transform(rez, tplInfo.data, this.format, opts, opts.themeObj, curFmt);
      if (tplInfo.ext === 'css') {
        curFmt.files[idx].data = trx;
      } else {
        tplInfo.ext === 'html';
      }
    } else {

    }
    if (typeof opts.onTransform === "function") {
      opts.onTransform(tplInfo);
    }
    return {
      info: tplInfo,
      data: trx
    };
  }, this);
  return {
    files: results
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.HtmlGenerator.__super__.transform"></a>[function <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.__super__.</span>transform (json, jst, format, opts, theme, curFmt)](#apidoc.element.hackmyresume.HtmlGenerator.__super__.transform)
- description and source-code
```javascript
transform = function (json, jst, format, opts, theme, curFmt) {
  var eng, result;
  if (this.opts.freezeBreaks) {
    jst = freeze(jst);
  }
  eng = require('../renderers/' + theme.engine + '-generator');
  result = eng.generate(json, jst, format, curFmt, opts, theme);
  if (this.opts.freezeBreaks) {
    result = unfreeze(result);
  }
  return result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.HtmlGenerator.prototype"></a>[module hackmyresume.HtmlGenerator.prototype](#apidoc.module.hackmyresume.HtmlGenerator.prototype)

#### <a name="apidoc.element.hackmyresume.HtmlGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.HtmlGenerator.prototype.constructor)
- description and source-code
```javascript
function HtmlGenerator() {
  HtmlGenerator.__super__.constructor.call(this, 'html');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.HtmlGenerator.prototype.onBeforeSave"></a>[function <span class="apidocSignatureSpan">hackmyresume.HtmlGenerator.prototype.</span>onBeforeSave (info)](#apidoc.element.hackmyresume.HtmlGenerator.prototype.onBeforeSave)
- description and source-code
```javascript
onBeforeSave = function (info) {
  if (info.outputFile.endsWith('.css')) {
    return info.mk;
  }
  if (this.opts.prettify) {
    return HTML.prettyPrint(info.mk, this.opts.prettify);
  } else {
    return info.mk;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.HtmlPdfCliGenerator"></a>[module hackmyresume.HtmlPdfCliGenerator](#apidoc.module.hackmyresume.HtmlPdfCliGenerator)

#### <a name="apidoc.element.hackmyresume.HtmlPdfCliGenerator.HtmlPdfCliGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>HtmlPdfCliGenerator ()](#apidoc.element.hackmyresume.HtmlPdfCliGenerator.HtmlPdfCliGenerator)
- description and source-code
```javascript
function HtmlPdfCLIGenerator() {
  HtmlPdfCLIGenerator.__super__.constructor.call(this, 'pdf', 'html');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.HtmlPdfCliGenerator.prototype"></a>[module hackmyresume.HtmlPdfCliGenerator.prototype](#apidoc.module.hackmyresume.HtmlPdfCliGenerator.prototype)

#### <a name="apidoc.element.hackmyresume.HtmlPdfCliGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.HtmlPdfCliGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.HtmlPdfCliGenerator.prototype.constructor)
- description and source-code
```javascript
function HtmlPdfCLIGenerator() {
  HtmlPdfCLIGenerator.__super__.constructor.call(this, 'pdf', 'html');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.HtmlPdfCliGenerator.prototype.onBeforeSave"></a>[function <span class="apidocSignatureSpan">hackmyresume.HtmlPdfCliGenerator.prototype.</span>onBeforeSave (info)](#apidoc.element.hackmyresume.HtmlPdfCliGenerator.prototype.onBeforeSave)
- description and source-code
```javascript
onBeforeSave = function (info) {
  var safe_eng;
  if (info.ext !== 'html' && info.ext !== 'pdf') {
    return info.mk;
  }
  safe_eng = info.opts.pdf || 'wkhtmltopdf';
  if (safe_eng === 'phantom') {
    safe_eng = 'phantomjs';
  }
  if (_.has(engines, safe_eng)) {
    this.errHandler = info.opts.errHandler;
    engines[safe_eng].call(this, info.mk, info.outputFile, this.onError);
    return null;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.HtmlPdfCliGenerator.prototype.onError"></a>[function <span class="apidocSignatureSpan">hackmyresume.HtmlPdfCliGenerator.prototype.</span>onError (ex, param)](#apidoc.element.hackmyresume.HtmlPdfCliGenerator.prototype.onError)
- description and source-code
```javascript
onError = function (ex, param) {
  var ref;
  if ((ref = param.errHandler) != null) {
    if (typeof ref.err === "function") {
      ref.err(HMSTATUS.pdfGeneration, ex);
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.HtmlPngGenerator"></a>[module hackmyresume.HtmlPngGenerator](#apidoc.module.hackmyresume.HtmlPngGenerator)

#### <a name="apidoc.element.hackmyresume.HtmlPngGenerator.HtmlPngGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>HtmlPngGenerator ()](#apidoc.element.hackmyresume.HtmlPngGenerator.HtmlPngGenerator)
- description and source-code
```javascript
function HtmlPngGenerator() {
  HtmlPngGenerator.__super__.constructor.call(this, 'png', 'html');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.HtmlPngGenerator.prototype"></a>[module hackmyresume.HtmlPngGenerator.prototype](#apidoc.module.hackmyresume.HtmlPngGenerator.prototype)

#### <a name="apidoc.element.hackmyresume.HtmlPngGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.HtmlPngGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.HtmlPngGenerator.prototype.constructor)
- description and source-code
```javascript
function HtmlPngGenerator() {
  HtmlPngGenerator.__super__.constructor.call(this, 'png', 'html');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.HtmlPngGenerator.prototype.generate"></a>[function <span class="apidocSignatureSpan">hackmyresume.HtmlPngGenerator.prototype.</span>generate (rez, f, opts)](#apidoc.element.hackmyresume.HtmlPngGenerator.prototype.generate)
- description and source-code
```javascript
generate = function (rez, f, opts) {
  var htmlFile, htmlResults;
  htmlResults = opts.targets.filter(function(t) {
    return t.fmt.outFormat === 'html';
  });
  htmlFile = htmlResults[0].final.files.filter(function(fl) {
    return fl.info.ext === 'html';
  });
  phantom(htmlFile[0].data, f);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.HtmlPngGenerator.prototype.invoke"></a>[function <span class="apidocSignatureSpan">hackmyresume.HtmlPngGenerator.prototype.</span>invoke (rez, themeMarkup, cssInfo, opts)](#apidoc.element.hackmyresume.HtmlPngGenerator.prototype.invoke)
- description and source-code
```javascript
invoke = function (rez, themeMarkup, cssInfo, opts) {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.JRSResume"></a>[module hackmyresume.JRSResume](#apidoc.module.hackmyresume.JRSResume)

#### <a name="apidoc.element.hackmyresume.JRSResume.JRSResume"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>JRSResume ()](#apidoc.element.hackmyresume.JRSResume.JRSResume)
- description and source-code
```javascript
function JRSResume() {
  return JRSResume.__super__.constructor.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.default"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.</span>default ()](#apidoc.element.hackmyresume.JRSResume.default)
- description and source-code
```javascript
default = function () {
  return new JRSResume().parseJSON(require('fresh-resume-starter').jrs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.stringify"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.</span>stringify (obj)](#apidoc.element.hackmyresume.JRSResume.stringify)
- description and source-code
```javascript
stringify = function (obj) {
  var replacer;
  replacer = function(key, value) {
    var temp;
    temp = _.some(['imp', 'warnings', 'computed', 'filt', 'ctrl', 'index', 'safeStartDate', 'safeEndDate', 'safeDate', 'safeReleaseDate
', 'result', 'isModified', 'htmlPreview', 'display_progress_bar'], function(val) {
      return key.trim() === val;
    });
    if (temp) {
      return void 0;
    } else {
      return value;
    }
  };
  return JSON.stringify(obj, replacer, 2);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.JRSResume.__super__"></a>[module hackmyresume.JRSResume.__super__](#apidoc.module.hackmyresume.JRSResume.__super__)

#### <a name="apidoc.element.hackmyresume.JRSResume.__super__.duration"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.__super__.</span>duration (collKey, startKey, endKey, unit)](#apidoc.element.hackmyresume.JRSResume.__super__.duration)
- description and source-code
```javascript
duration = function (collKey, startKey, endKey, unit) {
  var firstDate, hist, lastDate, new_e;
  unit = unit || 'years';
  hist = __.get(this, collKey);
  if (!hist || !hist.length) {
    return 0;
  }
  new_e = hist.map(function(job) {
    var obj;
    obj = _.pick(job, [startKey, endKey]);
    if (!_.has(obj, endKey)) {
      obj[endKey] = 'current';
    }
    if (obj && (obj[startKey] || obj[endKey])) {
      obj = _.pairs(obj);
      obj[0][1] = FluentDate.fmt(obj[0][1]);
      if (obj.length > 1) {
        obj[1][1] = FluentDate.fmt(obj[1][1]);
      }
    }
    return obj;
  });
  new_e = _.filter(_.flatten(new_e, true), function(v) {
    return v && v.length && v[0] && v[0].length;
  });
  if (!new_e || !new_e.length) {
    return 0;
  }
  new_e = _.sortBy(new_e, function(elem) {
    return elem[1].unix();
  });
  firstDate = _.first(new_e)[1];
  lastDate = _.last(new_e)[1];
  return lastDate.diff(firstDate, unit);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.JRSResume.prototype"></a>[module hackmyresume.JRSResume.prototype](#apidoc.module.hackmyresume.JRSResume.prototype)

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.add"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>add (moniker)](#apidoc.element.hackmyresume.JRSResume.prototype.add)
- description and source-code
```javascript
add = function (moniker) {
  var defSheet, newObject;
  defSheet = JRSResume["default"]();
  newObject = $.extend(true, {}, defSheet[moniker][0]);
  this[moniker] = this[moniker] || [];
  this[moniker].push(newObject);
  return newObject;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>constructor ()](#apidoc.element.hackmyresume.JRSResume.prototype.constructor)
- description and source-code
```javascript
function JRSResume() {
  return JRSResume.__super__.constructor.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.dupe"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>dupe ()](#apidoc.element.hackmyresume.JRSResume.prototype.dupe)
- description and source-code
```javascript
dupe = function () {
  var rnew;
  rnew = new JRSResume();
  rnew.parse(this.stringify(), {});
  return rnew;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.duration"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>duration (unit)](#apidoc.element.hackmyresume.JRSResume.prototype.duration)
- description and source-code
```javascript
duration = function (unit) {
  return JRSResume.__super__.duration.call(this, 'work', 'startDate', 'endDate', unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.format"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>format ()](#apidoc.element.hackmyresume.JRSResume.prototype.format)
- description and source-code
```javascript
format = function () {
  return 'JRS';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.harden"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>harden ()](#apidoc.element.hackmyresume.JRSResume.prototype.harden)
- description and source-code
```javascript
harden = function () {
  var HD, HDIN, hardenStringsInObject, ret, that;
  that = this;
  ret = this.dupe();
  HD = function(txt) {
    return '@@@@~' + txt + '~@@@@';
  };
  HDIN = function(txt) {
    return HD(txt);
  };
  hardenStringsInObject = function(obj, inline) {
    if (!obj) {
      return;
    }
    inline = inline === void 0 || inline;
    if (Object.prototype.toString.call(obj) === '[object Array]') {
      return obj.forEach(function(elem, idx, ar) {
        if (typeof elem === 'string' || elem instanceof String) {
          return ar[idx] = inline ? HDIN(elem) : HD(elem);
        } else {
          return hardenStringsInObject(elem);
        }
      });
    } else if (typeof obj === 'object') {
      return Object.keys(obj).forEach(function(key) {
        var sub;
        sub = obj[key];
        if (typeof sub === 'string' || sub instanceof String) {
          if (_.contains(['skills', 'url', 'website', 'startDate', 'endDate', 'releaseDate', 'date', 'phone', 'email', 'address', '
postalCode', 'city', 'country', 'region'], key)) {
            return;
          }
          if (key === 'summary') {
            return obj[key] = HD(obj[key]);
          } else {
            return obj[key] = inline ? HDIN(obj[key]) : HD(obj[key]);
          }
        } else {
          return hardenStringsInObject(sub);
        }
      });
    }
  };
  Object.keys(ret).forEach(function(member) {
    return hardenStringsInObject(ret[member]);
  });
  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.hasProfile"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>hasProfile (socialNetwork)](#apidoc.element.hackmyresume.JRSResume.prototype.hasProfile)
- description and source-code
```javascript
hasProfile = function (socialNetwork) {
  socialNetwork = socialNetwork.trim().toLowerCase();
  return this.basics.profiles && _.some(this.basics.profiles, function(p) {
    return p.network.trim().toLowerCase() === socialNetwork;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.hasSkill"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>hasSkill (skill)](#apidoc.element.hackmyresume.JRSResume.prototype.hasSkill)
- description and source-code
```javascript
hasSkill = function (skill) {
  skill = skill.trim().toLowerCase();
  return this.skills && _.some(this.skills, function(sk) {
    return sk.keywords && _.some(sk.keywords, function(kw) {
      return kw.trim().toLowerCase() === skill;
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.i"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>i ()](#apidoc.element.hackmyresume.JRSResume.prototype.i)
- description and source-code
```javascript
i = function () {
  var ref;
  return this.imp = (ref = this.imp) != null ? ref : {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.isValid"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>isValid ()](#apidoc.element.hackmyresume.JRSResume.prototype.isValid)
- description and source-code
```javascript
isValid = function () {
  var ret, schema, schemaObj, temp, validate;
  schema = FS.readFileSync(PATH.join(__dirname, 'resume.json'), 'utf8');
  schemaObj = JSON.parse(schema);
  validator = require('is-my-json-valid');
  validate = validator(schemaObj, {
    formats: {
      date: /^\d{4}(?:-(?:0[0-9]{1}|1[0-2]{1})(?:-[0-9]{2})?)?$/
    }
  });
  temp = this.imp;
  delete this.imp;
  ret = validate(this);
  this.imp = temp;
  if (!ret) {
    this.imp = this.imp || {};
    this.imp.validationErrors = validate.errors;
  }
  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.keywords"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>keywords ()](#apidoc.element.hackmyresume.JRSResume.prototype.keywords)
- description and source-code
```javascript
keywords = function () {
  var flatSkills;
  flatSkills = [];
  if (this.skills && this.skills.length) {
    this.skills.forEach(function(s) {
      return flatSkills = _.union(flatSkills, s.keywords);
    });
  }
  return flatSkills;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.parse"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>parse (stringData, opts)](#apidoc.element.hackmyresume.JRSResume.prototype.parse)
- description and source-code
```javascript
parse = function (stringData, opts) {
  var ref;
  this.imp = (ref = this.imp) != null ? ref : {
    raw: stringData
  };
  return this.parseJSON(JSON.parse(stringData), opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.parseJSON"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>parseJSON (rep, opts)](#apidoc.element.hackmyresume.JRSResume.prototype.parseJSON)
- description and source-code
```javascript
parseJSON = function (rep, opts) {
  var ignoreList, ref, scrubbed, that, traverse;
  opts = opts || {};
  that = this;
  traverse = require('traverse');
  ignoreList = [];
  scrubbed = traverse(rep).map(function(x) {
    if (!this.isLeaf && this.node.ignore) {
      if (this.node.ignore === true || this.node.ignore === 'true') {
        ignoreList.push(this.node);
        return this.remove();
      }
    }
  });
  extend(true, this, scrubbed);
  if (!((ref = this.imp) != null ? ref.processed : void 0)) {
    opts = opts || {};
    if (opts.imp === void 0 || opts.imp) {
      this.imp = this.imp || {};
      this.imp.title = (opts.title || this.imp.title) || this.basics.name;
      if (!this.imp.raw) {
        this.imp.raw = JSON.stringify(rep);
      }
    }
    this.imp.processed = true;
  }
  (opts.date === void 0 || opts.date) && _parseDates.call(this);
  (opts.sort === void 0 || opts.sort) && this.sort();
  if (opts.compute === void 0 || opts.compute) {
    this.basics.computed = {
      numYears: this.duration(),
      keywords: this.keywords()
    };
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.save"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>save (filename)](#apidoc.element.hackmyresume.JRSResume.prototype.save)
- description and source-code
```javascript
save = function (filename) {
  this.imp.file = filename || this.imp.file;
  FS.writeFileSync(this.imp.file, this.stringify(this), 'utf8');
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.saveAs"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>saveAs (filename, format)](#apidoc.element.hackmyresume.JRSResume.prototype.saveAs)
- description and source-code
```javascript
saveAs = function (filename, format) {
  var newRep, stringRep;
  if (format === 'JRS') {
    this.imp.file = filename || this.imp.file;
    FS.writeFileSync(this.imp.file, this.stringify(), 'utf8');
  } else {
    newRep = CONVERTER.toFRESH(this);
    stringRep = CONVERTER.toSTRING(newRep);
    FS.writeFileSync(filename, stringRep, 'utf8');
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.sort"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>sort ()](#apidoc.element.hackmyresume.JRSResume.prototype.sort)
- description and source-code
```javascript
sort = function () {
  var byDateDesc;
  byDateDesc = function(a, b) {
    if (a.safeStartDate.isBefore(b.safeStartDate)) {
      return 1;
    } else {
      return (a.safeStartDate.isAfter(b.safeStartDate) && -1) || 0;
    }
  };
  this.work && this.work.sort(byDateDesc);
  this.education && this.education.sort(byDateDesc);
  this.volunteer && this.volunteer.sort(byDateDesc);
  this.awards && this.awards.sort(function(a, b) {
    if (a.safeDate.isBefore(b.safeDate)) {
      return 1;
    } else {
      return (a.safeDate.isAfter(b.safeDate) && -1) || 0;
    }
  });
  return this.publications && this.publications.sort(function(a, b) {
    if (a.safeReleaseDate.isBefore(b.safeReleaseDate)) {
      return 1;
    } else {
      return (a.safeReleaseDate.isAfter(b.safeReleaseDate) && -1) || 0;
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSResume.prototype.stringify"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSResume.prototype.</span>stringify ()](#apidoc.element.hackmyresume.JRSResume.prototype.stringify)
- description and source-code
```javascript
stringify = function () {
  return JRSResume.stringify(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.JRSTheme"></a>[module hackmyresume.JRSTheme](#apidoc.module.hackmyresume.JRSTheme)

#### <a name="apidoc.element.hackmyresume.JRSTheme.JRSTheme"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>JRSTheme ()](#apidoc.element.hackmyresume.JRSTheme.JRSTheme)
- description and source-code
```javascript
function JRSTheme() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.JRSTheme.prototype"></a>[module hackmyresume.JRSTheme.prototype](#apidoc.module.hackmyresume.JRSTheme.prototype)

#### <a name="apidoc.element.hackmyresume.JRSTheme.prototype.getFormat"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSTheme.prototype.</span>getFormat (fmt)](#apidoc.element.hackmyresume.JRSTheme.prototype.getFormat)
- description and source-code
```javascript
getFormat = function (fmt) {
  return this.formats[fmt];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSTheme.prototype.hasFormat"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSTheme.prototype.</span>hasFormat (fmt)](#apidoc.element.hackmyresume.JRSTheme.prototype.hasFormat)
- description and source-code
```javascript
hasFormat = function (fmt) {
  return _.has(this.formats, fmt);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JRSTheme.prototype.open"></a>[function <span class="apidocSignatureSpan">hackmyresume.JRSTheme.prototype.</span>open (thFolder)](#apidoc.element.hackmyresume.JRSTheme.prototype.open)
- description and source-code
```javascript
open = function (thFolder) {
  var pathInfo, pkgJsonPath, thApi, thPkg;
  this.folder = thFolder;
  pathInfo = parsePath(thFolder);
  pkgJsonPath = PATH.join(thFolder, 'package.json');
  if (pathExists(pkgJsonPath)) {
    thApi = require(thFolder);
    thPkg = require(pkgJsonPath);
    this.name = thPkg.name;
    this.render = (thApi && thApi.render) || void 0;
    this.engine = 'jrs';
    this.formats = {
      html: {
        outFormat: 'html',
        files: [
          {
            action: 'transform',
            render: this.render,
            primary: true,
            ext: 'html',
            css: null
          }
        ]
      },
      pdf: {
        outFormat: 'pdf',
        files: [
          {
            action: 'transform',
            render: this.render,
            primary: true,
            ext: 'pdf',
            css: null
          }
        ]
      }
    };
  } else {
    throw {
      fluenterror: HACKMYSTATUS.missingPackageJSON
    };
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.JsonGenerator"></a>[module hackmyresume.JsonGenerator](#apidoc.module.hackmyresume.JsonGenerator)

#### <a name="apidoc.element.hackmyresume.JsonGenerator.JsonGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>JsonGenerator ()](#apidoc.element.hackmyresume.JsonGenerator.JsonGenerator)
- description and source-code
```javascript
function JsonGenerator() {
  JsonGenerator.__super__.constructor.call(this, 'json');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.JsonGenerator.prototype"></a>[module hackmyresume.JsonGenerator.prototype](#apidoc.module.hackmyresume.JsonGenerator.prototype)

#### <a name="apidoc.element.hackmyresume.JsonGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.JsonGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.JsonGenerator.prototype.constructor)
- description and source-code
```javascript
function JsonGenerator() {
  JsonGenerator.__super__.constructor.call(this, 'json');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JsonGenerator.prototype.generate"></a>[function <span class="apidocSignatureSpan">hackmyresume.JsonGenerator.prototype.</span>generate (rez, f)](#apidoc.element.hackmyresume.JsonGenerator.prototype.generate)
- description and source-code
```javascript
generate = function (rez, f) {
  FS.writeFileSync(f, this.invoke(rez), 'utf8');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JsonGenerator.prototype.invoke"></a>[function <span class="apidocSignatureSpan">hackmyresume.JsonGenerator.prototype.</span>invoke (rez)](#apidoc.element.hackmyresume.JsonGenerator.prototype.invoke)
- description and source-code
```javascript
invoke = function (rez) {
  var altRez;
  altRez = FJCV['to' + (rez.format() === 'FRESH' ? 'JRS' : 'FRESH')](rez);
  return altRez = FJCV.toSTRING(altRez);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.JsonYamlGenerator"></a>[module hackmyresume.JsonYamlGenerator](#apidoc.module.hackmyresume.JsonYamlGenerator)

#### <a name="apidoc.element.hackmyresume.JsonYamlGenerator.JsonYamlGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>JsonYamlGenerator ()](#apidoc.element.hackmyresume.JsonYamlGenerator.JsonYamlGenerator)
- description and source-code
```javascript
function JsonYamlGenerator() {
  JsonYamlGenerator.__super__.constructor.call(this, 'yml');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.JsonYamlGenerator.prototype"></a>[module hackmyresume.JsonYamlGenerator.prototype](#apidoc.module.hackmyresume.JsonYamlGenerator.prototype)

#### <a name="apidoc.element.hackmyresume.JsonYamlGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.JsonYamlGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.JsonYamlGenerator.prototype.constructor)
- description and source-code
```javascript
function JsonYamlGenerator() {
  JsonYamlGenerator.__super__.constructor.call(this, 'yml');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JsonYamlGenerator.prototype.generate"></a>[function <span class="apidocSignatureSpan">hackmyresume.JsonYamlGenerator.prototype.</span>generate (rez, f, opts)](#apidoc.element.hackmyresume.JsonYamlGenerator.prototype.generate)
- description and source-code
```javascript
generate = function (rez, f, opts) {
  var data;
  data = YAML.stringify(JSON.parse(rez.stringify()), Infinity, 2);
  FS.writeFileSync(f, data, 'utf8');
  return data;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.JsonYamlGenerator.prototype.invoke"></a>[function <span class="apidocSignatureSpan">hackmyresume.JsonYamlGenerator.prototype.</span>invoke (rez, themeMarkup, cssInfo, opts)](#apidoc.element.hackmyresume.JsonYamlGenerator.prototype.invoke)
- description and source-code
```javascript
invoke = function (rez, themeMarkup, cssInfo, opts) {
  return YAML.stringify(JSON.parse(rez.stringify()), Infinity, 2);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.LaTeXGenerator"></a>[module hackmyresume.LaTeXGenerator](#apidoc.module.hackmyresume.LaTeXGenerator)

#### <a name="apidoc.element.hackmyresume.LaTeXGenerator.LaTeXGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>LaTeXGenerator ()](#apidoc.element.hackmyresume.LaTeXGenerator.LaTeXGenerator)
- description and source-code
```javascript
function LaTeXGenerator() {
  LaTeXGenerator.__super__.constructor.call(this, 'latex', 'tex');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.LaTeXGenerator.prototype"></a>[module hackmyresume.LaTeXGenerator.prototype](#apidoc.module.hackmyresume.LaTeXGenerator.prototype)

#### <a name="apidoc.element.hackmyresume.LaTeXGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.LaTeXGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.LaTeXGenerator.prototype.constructor)
- description and source-code
```javascript
function LaTeXGenerator() {
  LaTeXGenerator.__super__.constructor.call(this, 'latex', 'tex');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.MarkdownGenerator"></a>[module hackmyresume.MarkdownGenerator](#apidoc.module.hackmyresume.MarkdownGenerator)

#### <a name="apidoc.element.hackmyresume.MarkdownGenerator.MarkdownGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>MarkdownGenerator ()](#apidoc.element.hackmyresume.MarkdownGenerator.MarkdownGenerator)
- description and source-code
```javascript
function MarkdownGenerator() {
  MarkdownGenerator.__super__.constructor.call(this, 'md', 'txt');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.MarkdownGenerator.prototype"></a>[module hackmyresume.MarkdownGenerator.prototype](#apidoc.module.hackmyresume.MarkdownGenerator.prototype)

#### <a name="apidoc.element.hackmyresume.MarkdownGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.MarkdownGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.MarkdownGenerator.prototype.constructor)
- description and source-code
```javascript
function MarkdownGenerator() {
  MarkdownGenerator.__super__.constructor.call(this, 'md', 'txt');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.ResumeFactory"></a>[module hackmyresume.ResumeFactory](#apidoc.module.hackmyresume.ResumeFactory)

#### <a name="apidoc.element.hackmyresume.ResumeFactory.load"></a>[function <span class="apidocSignatureSpan">hackmyresume.ResumeFactory.</span>load (sources, opts, emitter)](#apidoc.element.hackmyresume.ResumeFactory.load)
- description and source-code
```javascript
load = function (sources, opts, emitter) {
  return sources.map(function(src) {
    return this.loadOne(src, opts, emitter);
  }, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.ResumeFactory.loadOne"></a>[function <span class="apidocSignatureSpan">hackmyresume.ResumeFactory.</span>loadOne (src, opts, emitter)](#apidoc.element.hackmyresume.ResumeFactory.loadOne)
- description and source-code
```javascript
loadOne = function (src, opts, emitter) {
  var ResumeClass, info, isFRESH, json, objectify, orgFormat, rez, toFormat;
  toFormat = opts.format;
  objectify = opts.objectify;
  toFormat && (toFormat = toFormat.toLowerCase().trim());
  info = _parse(src, opts, emitter);
  if (info.fluenterror) {
    return info;
  }
  json = info.json;
  isFRESH = json.meta && json.meta.format && json.meta.format.startsWith('FRESH@');
  orgFormat = isFRESH ? 'fresh' : 'jrs';
  if (toFormat && (orgFormat !== toFormat)) {
    json = ResumeConverter['to' + toFormat.toUpperCase()](json);
  }
  rez = null;
  if (objectify) {
    ResumeClass = require('../core/' + (toFormat || orgFormat) + '-resume');
    rez = new ResumeClass().parseJSON(json, opts.inner);
    rez.i().file = src;
  }
  return {
    file: src,
    json: info.json,
    rez: rez
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.Sheet"></a>[module hackmyresume.Sheet](#apidoc.module.hackmyresume.Sheet)

#### <a name="apidoc.element.hackmyresume.Sheet.Sheet"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>Sheet ()](#apidoc.element.hackmyresume.Sheet.Sheet)
- description and source-code
```javascript
function FreshResume() {
  return FreshResume.__super__.constructor.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.default"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.</span>default ()](#apidoc.element.hackmyresume.Sheet.default)
- description and source-code
```javascript
default = function () {
  return new FreshResume().parseJSON(require('fresh-resume-starter').fresh);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.stringify"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.</span>stringify (obj)](#apidoc.element.hackmyresume.Sheet.stringify)
- description and source-code
```javascript
stringify = function (obj) {
  var replacer;
  replacer = function(key, value) {
    var exKeys;
    exKeys = ['imp', 'warnings', 'computed', 'filt', 'ctrl', 'index', 'safe', 'result', 'isModified', 'htmlPreview', 'display_progress_bar
'];
    if (_.some(exKeys, function(val) {
      return key.trim() === val;
    })) {
      return void 0;
    } else {
      return value;
    }
  };
  return JSON.stringify(obj, replacer, 2);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.Sheet.prototype"></a>[module hackmyresume.Sheet.prototype](#apidoc.module.hackmyresume.Sheet.prototype)

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.add"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>add (moniker)](#apidoc.element.hackmyresume.Sheet.prototype.add)
- description and source-code
```javascript
add = function (moniker) {
  var defSheet, newObject;
  defSheet = FreshResume["default"]();
  newObject = defSheet[moniker].history ? $.extend(true, {}, defSheet[moniker].history[0]) : moniker === 'skills' ? $.extend(true
, {}, defSheet.skills.sets[0]) : $.extend(true, {}, defSheet[moniker][0]);
  this[moniker] = this[moniker] || [];
  if (this[moniker].history) {
    this[moniker].history.push(newObject);
  } else if (moniker === 'skills') {
    this.skills.sets.push(newObject);
  } else {
    this[moniker].push(newObject);
  }
  return newObject;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.clear"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>clear (clearMeta)](#apidoc.element.hackmyresume.Sheet.prototype.clear)
- description and source-code
```javascript
clear = function (clearMeta) {
  clearMeta = ((clearMeta === void 0) && true) || clearMeta;
  if (clearMeta) {
    delete this.imp;
  }
  delete this.computed;
  delete this.employment;
  delete this.service;
  delete this.education;
  delete this.recognition;
  delete this.reading;
  delete this.writing;
  delete this.interests;
  delete this.skills;
  return delete this.social;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>constructor ()](#apidoc.element.hackmyresume.Sheet.prototype.constructor)
- description and source-code
```javascript
function FreshResume() {
  return FreshResume.__super__.constructor.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.count"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>count (obj)](#apidoc.element.hackmyresume.Sheet.prototype.count)
- description and source-code
```javascript
count = function (obj) {
  if (!obj) {
    return 0;
  }
  if (obj.history) {
    return obj.history.length;
  }
  if (obj.sets) {
    return obj.sets.length;
  }
  return obj.length || 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.dupe"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>dupe ()](#apidoc.element.hackmyresume.Sheet.prototype.dupe)
- description and source-code
```javascript
dupe = function () {
  var jso, rnew;
  jso = extend(true, {}, this);
  rnew = new FreshResume();
  rnew.parseJSON(jso, {});
  return rnew;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.duration"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>duration (unit)](#apidoc.element.hackmyresume.Sheet.prototype.duration)
- description and source-code
```javascript
duration = function (unit) {
  return FreshResume.__super__.duration.call(this, 'employment.history', 'start', 'end', unit);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.format"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>format ()](#apidoc.element.hackmyresume.Sheet.prototype.format)
- description and source-code
```javascript
format = function () {
  return 'FRESH';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.getProfile"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>getProfile (socialNetwork)](#apidoc.element.hackmyresume.Sheet.prototype.getProfile)
- description and source-code
```javascript
getProfile = function (socialNetwork) {
  socialNetwork = socialNetwork.trim().toLowerCase();
  return this.social && _.find(this.social, function(sn) {
    return sn.network.trim().toLowerCase() === socialNetwork;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.getProfiles"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>getProfiles (socialNetwork)](#apidoc.element.hackmyresume.Sheet.prototype.getProfiles)
- description and source-code
```javascript
getProfiles = function (socialNetwork) {
  socialNetwork = socialNetwork.trim().toLowerCase();
  return this.social && _.filter(this.social, function(sn) {
    return sn.network.trim().toLowerCase() === socialNetwork;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.hasProfile"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>hasProfile (socialNetwork)](#apidoc.element.hackmyresume.Sheet.prototype.hasProfile)
- description and source-code
```javascript
hasProfile = function (socialNetwork) {
  socialNetwork = socialNetwork.trim().toLowerCase();
  return this.social && _.some(this.social, function(p) {
    return p.network.trim().toLowerCase() === socialNetwork;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.hasSkill"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>hasSkill (skill)](#apidoc.element.hackmyresume.Sheet.prototype.hasSkill)
- description and source-code
```javascript
hasSkill = function (skill) {
  skill = skill.trim().toLowerCase();
  return this.skills && _.some(this.skills, function(sk) {
    return sk.keywords && _.some(sk.keywords, function(kw) {
      return kw.trim().toLowerCase() === skill;
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.i"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>i ()](#apidoc.element.hackmyresume.Sheet.prototype.i)
- description and source-code
```javascript
i = function () {
  return this.imp = this.imp || {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.isValid"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>isValid (info)](#apidoc.element.hackmyresume.Sheet.prototype.isValid)
- description and source-code
```javascript
isValid = function (info) {
  var ret, schemaObj, validate;
  schemaObj = require('fresca');
  validator = require('is-my-json-valid');
  validate = validator(schemaObj, {
    formats: {
      date: /^\d{4}(?:-(?:0[0-9]{1}|1[0-2]{1})(?:-[0-9]{2})?)?$/
    }
  });
  ret = validate(this);
  if (!ret) {
    this.imp = this.imp || {};
    this.imp.validationErrors = validate.errors;
  }
  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.keywords"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>keywords ()](#apidoc.element.hackmyresume.Sheet.prototype.keywords)
- description and source-code
```javascript
keywords = function () {
  var flatSkills;
  flatSkills = [];
  if (this.skills) {
    if (this.skills.sets) {
      flatSkills = this.skills.sets.map(function(sk) {
        return sk.skills;
      }).reduce(function(a, b) {
        return a.concat(b);
      });
    } else if (this.skills.list) {
      flatSkills = flatSkills.concat(this.skills.list.map(function(sk) {
        return sk.name;
      }));
    }
    flatSkills = _.uniq(flatSkills);
  }
  return flatSkills;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.markdownify"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>markdownify ()](#apidoc.element.hackmyresume.Sheet.prototype.markdownify)
- description and source-code
```javascript
markdownify = function () {
  var MDIN, trx;
  MDIN = function(txt) {
    return MD(txt || '').replace(/^\s*<p>|<\/p>\s*$/gi, '');
  };
  trx = function(key, val) {
    if (key === 'summary') {
      return MD(val);
    }
    return MDIN(val);
  };
  return this.transformStrings(['skills', 'url', 'start', 'end', 'date'], trx);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.parse"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>parse (stringData, opts)](#apidoc.element.hackmyresume.Sheet.prototype.parse)
- description and source-code
```javascript
parse = function (stringData, opts) {
  var ref;
  this.imp = (ref = this.imp) != null ? ref : {
    raw: stringData
  };
  return this.parseJSON(JSON.parse(stringData), opts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.parseJSON"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>parseJSON (rep, opts)](#apidoc.element.hackmyresume.Sheet.prototype.parseJSON)
- description and source-code
```javascript
parseJSON = function (rep, opts) {
  var ignoreList, ref, scrubbed, that, traverse;
  that = this;
  traverse = require('traverse');
  ignoreList = [];
  scrubbed = traverse(rep).map(function(x) {
    if (!this.isLeaf && this.node.ignore) {
      if (this.node.ignore === true || this.node.ignore === 'true') {
        ignoreList.push(this.node);
        return this.remove();
      }
    }
  });
  extend(true, this, scrubbed);
  if (!((ref = this.imp) != null ? ref.processed : void 0)) {
    opts = opts || {};
    if (opts.imp === void 0 || opts.imp) {
      this.imp = this.imp || {};
      this.imp.title = (opts.title || this.imp.title) || this.name;
      if (!this.imp.raw) {
        this.imp.raw = JSON.stringify(rep);
      }
    }
    this.imp.processed = true;
    (opts.date === void 0 || opts.date) && _parseDates.call(this);
    (opts.sort === void 0 || opts.sort) && this.sort();
    (opts.compute === void 0 || opts.compute) && (this.computed = {
      numYears: this.duration(),
      keywords: this.keywords()
    });
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.save"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>save (filename)](#apidoc.element.hackmyresume.Sheet.prototype.save)
- description and source-code
```javascript
save = function (filename) {
  this.imp.file = filename || this.imp.file;
  FS.writeFileSync(this.imp.file, this.stringify(), 'utf8');
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.saveAs"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>saveAs (filename, format)](#apidoc.element.hackmyresume.Sheet.prototype.saveAs)
- description and source-code
```javascript
saveAs = function (filename, format) {
  var newRep;
  if (format !== 'JRS') {
    this.imp.file = filename || this.imp.file;
    FS.writeFileSync(this.imp.file, this.stringify(), 'utf8');
  } else {
    newRep = CONVERTER.toJRS(this);
    FS.writeFileSync(filename, JRSResume.stringify(newRep), 'utf8');
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.sort"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>sort ()](#apidoc.element.hackmyresume.Sheet.prototype.sort)
- description and source-code
```javascript
sort = function () {
  var byDateDesc, sortSection;
  byDateDesc = function(a, b) {
    if (a.safe.start.isBefore(b.safe.start)) {
      return 1;
    } else {
      if (a.safe.start.isAfter(b.safe.start)) {
        return -1;
      } else {
        return 0;
      }
    }
  };
  sortSection = function(key) {
    var ar, datedThings;
    ar = __.get(this, key);
    if (ar && ar.length) {
      datedThings = obj.filter(function(o) {
        return o.start;
      });
      return datedThings.sort(byDateDesc);
    }
  };
  sortSection('employment.history');
  sortSection('education.history');
  sortSection('service.history');
  sortSection('projects');
  return this.writing && this.writing.sort(function(a, b) {
    if (a.safe.date.isBefore(b.safe.date)) {
      return 1;
    } else {
      return (a.safe.date.isAfter(b.safe.date) && -1) || 0;
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.stringify"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>stringify ()](#apidoc.element.hackmyresume.Sheet.prototype.stringify)
- description and source-code
```javascript
stringify = function () {
  return FreshResume.stringify(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.transformStrings"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>transformStrings (filt, transformer)](#apidoc.element.hackmyresume.Sheet.prototype.transformStrings)
- description and source-code
```javascript
transformStrings = function (filt, transformer) {
  var ret, trx;
  ret = this.dupe();
  trx = require('../utils/string-transformer');
  return trx(ret, filt, transformer);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.Sheet.prototype.xmlify"></a>[function <span class="apidocSignatureSpan">hackmyresume.Sheet.prototype.</span>xmlify ()](#apidoc.element.hackmyresume.Sheet.prototype.xmlify)
- description and source-code
```javascript
xmlify = function () {
  var trx;
  trx = function(key, val) {
    return XML(val);
  };
  return this.transformStrings([], trx);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.TextGenerator"></a>[module hackmyresume.TextGenerator](#apidoc.module.hackmyresume.TextGenerator)

#### <a name="apidoc.element.hackmyresume.TextGenerator.TextGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>TextGenerator ()](#apidoc.element.hackmyresume.TextGenerator.TextGenerator)
- description and source-code
```javascript
function TextGenerator() {
  TextGenerator.__super__.constructor.call(this, 'txt');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.TextGenerator.prototype"></a>[module hackmyresume.TextGenerator.prototype](#apidoc.module.hackmyresume.TextGenerator.prototype)

#### <a name="apidoc.element.hackmyresume.TextGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.TextGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.TextGenerator.prototype.constructor)
- description and source-code
```javascript
function TextGenerator() {
  TextGenerator.__super__.constructor.call(this, 'txt');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.WordGenerator"></a>[module hackmyresume.WordGenerator](#apidoc.module.hackmyresume.WordGenerator)

#### <a name="apidoc.element.hackmyresume.WordGenerator.WordGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>WordGenerator ()](#apidoc.element.hackmyresume.WordGenerator.WordGenerator)
- description and source-code
```javascript
function WordGenerator() {
  WordGenerator.__super__.constructor.call(this, 'doc', 'xml');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.WordGenerator.prototype"></a>[module hackmyresume.WordGenerator.prototype](#apidoc.module.hackmyresume.WordGenerator.prototype)

#### <a name="apidoc.element.hackmyresume.WordGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.WordGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.WordGenerator.prototype.constructor)
- description and source-code
```javascript
function WordGenerator() {
  WordGenerator.__super__.constructor.call(this, 'doc', 'xml');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.YamlGenerator"></a>[module hackmyresume.YamlGenerator](#apidoc.module.hackmyresume.YamlGenerator)

#### <a name="apidoc.element.hackmyresume.YamlGenerator.YamlGenerator"></a>[function <span class="apidocSignatureSpan">hackmyresume.</span>YamlGenerator ()](#apidoc.element.hackmyresume.YamlGenerator.YamlGenerator)
- description and source-code
```javascript
function YAMLGenerator() {
  YAMLGenerator.__super__.constructor.call(this, 'yml', 'yml');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.YamlGenerator.prototype"></a>[module hackmyresume.YamlGenerator.prototype](#apidoc.module.hackmyresume.YamlGenerator.prototype)

#### <a name="apidoc.element.hackmyresume.YamlGenerator.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.YamlGenerator.prototype.</span>constructor ()](#apidoc.element.hackmyresume.YamlGenerator.prototype.constructor)
- description and source-code
```javascript
function YAMLGenerator() {
  YAMLGenerator.__super__.constructor.call(this, 'yml', 'yml');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.alias"></a>[module hackmyresume.alias](#apidoc.module.hackmyresume.alias)

#### <a name="apidoc.element.hackmyresume.alias.create"></a>[function <span class="apidocSignatureSpan">hackmyresume.alias.</span>create ()](#apidoc.element.hackmyresume.alias.create)
- description and source-code
```javascript
function CreateVerb() {
  CreateVerb.__super__.constructor.call(this, 'new', _create);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.alias.generate"></a>[function <span class="apidocSignatureSpan">hackmyresume.alias.</span>generate ()](#apidoc.element.hackmyresume.alias.generate)
- description and source-code
```javascript
function BuildVerb() {
  BuildVerb.__super__.constructor.call(this, 'build', _build);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.alias.create"></a>[module hackmyresume.alias.create](#apidoc.module.hackmyresume.alias.create)

#### <a name="apidoc.element.hackmyresume.alias.create.create"></a>[function <span class="apidocSignatureSpan">hackmyresume.alias.</span>create ()](#apidoc.element.hackmyresume.alias.create.create)
- description and source-code
```javascript
function CreateVerb() {
  CreateVerb.__super__.constructor.call(this, 'new', _create);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.alias.create.prototype"></a>[module hackmyresume.alias.create.prototype](#apidoc.module.hackmyresume.alias.create.prototype)

#### <a name="apidoc.element.hackmyresume.alias.create.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.alias.create.prototype.</span>constructor ()](#apidoc.element.hackmyresume.alias.create.prototype.constructor)
- description and source-code
```javascript
function CreateVerb() {
  CreateVerb.__super__.constructor.call(this, 'new', _create);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.alias.generate"></a>[module hackmyresume.alias.generate](#apidoc.module.hackmyresume.alias.generate)

#### <a name="apidoc.element.hackmyresume.alias.generate.generate"></a>[function <span class="apidocSignatureSpan">hackmyresume.alias.</span>generate ()](#apidoc.element.hackmyresume.alias.generate.generate)
- description and source-code
```javascript
function BuildVerb() {
  BuildVerb.__super__.constructor.call(this, 'build', _build);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.alias.generate.prototype"></a>[module hackmyresume.alias.generate.prototype](#apidoc.module.hackmyresume.alias.generate.prototype)

#### <a name="apidoc.element.hackmyresume.alias.generate.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.alias.generate.prototype.</span>constructor ()](#apidoc.element.hackmyresume.alias.generate.prototype.constructor)
- description and source-code
```javascript
function BuildVerb() {
  BuildVerb.__super__.constructor.call(this, 'build', _build);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.verbs"></a>[module hackmyresume.verbs](#apidoc.module.hackmyresume.verbs)

#### <a name="apidoc.element.hackmyresume.verbs.analyze"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>analyze ()](#apidoc.element.hackmyresume.verbs.analyze)
- description and source-code
```javascript
function AnalyzeVerb() {
  AnalyzeVerb.__super__.constructor.call(this, 'analyze', _analyze);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.verbs.build"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>build ()](#apidoc.element.hackmyresume.verbs.build)
- description and source-code
```javascript
function BuildVerb() {
  BuildVerb.__super__.constructor.call(this, 'build', _build);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.verbs.convert"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>convert ()](#apidoc.element.hackmyresume.verbs.convert)
- description and source-code
```javascript
function ConvertVerb() {
  ConvertVerb.__super__.constructor.call(this, 'convert', _convert);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.verbs.new"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>new ()](#apidoc.element.hackmyresume.verbs.new)
- description and source-code
```javascript
function CreateVerb() {
  CreateVerb.__super__.constructor.call(this, 'new', _create);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.verbs.peek"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>peek ()](#apidoc.element.hackmyresume.verbs.peek)
- description and source-code
```javascript
function PeekVerb() {
  PeekVerb.__super__.constructor.call(this, 'peek', _peek);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hackmyresume.verbs.validate"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>validate ()](#apidoc.element.hackmyresume.verbs.validate)
- description and source-code
```javascript
function ValidateVerb() {
  ValidateVerb.__super__.constructor.call(this, 'validate', _validate);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.verbs.analyze"></a>[module hackmyresume.verbs.analyze](#apidoc.module.hackmyresume.verbs.analyze)

#### <a name="apidoc.element.hackmyresume.verbs.analyze.analyze"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>analyze ()](#apidoc.element.hackmyresume.verbs.analyze.analyze)
- description and source-code
```javascript
function AnalyzeVerb() {
  AnalyzeVerb.__super__.constructor.call(this, 'analyze', _analyze);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.verbs.analyze.prototype"></a>[module hackmyresume.verbs.analyze.prototype](#apidoc.module.hackmyresume.verbs.analyze.prototype)

#### <a name="apidoc.element.hackmyresume.verbs.analyze.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.analyze.prototype.</span>constructor ()](#apidoc.element.hackmyresume.verbs.analyze.prototype.constructor)
- description and source-code
```javascript
function AnalyzeVerb() {
  AnalyzeVerb.__super__.constructor.call(this, 'analyze', _analyze);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.verbs.convert"></a>[module hackmyresume.verbs.convert](#apidoc.module.hackmyresume.verbs.convert)

#### <a name="apidoc.element.hackmyresume.verbs.convert.convert"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>convert ()](#apidoc.element.hackmyresume.verbs.convert.convert)
- description and source-code
```javascript
function ConvertVerb() {
  ConvertVerb.__super__.constructor.call(this, 'convert', _convert);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.verbs.convert.prototype"></a>[module hackmyresume.verbs.convert.prototype](#apidoc.module.hackmyresume.verbs.convert.prototype)

#### <a name="apidoc.element.hackmyresume.verbs.convert.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.convert.prototype.</span>constructor ()](#apidoc.element.hackmyresume.verbs.convert.prototype.constructor)
- description and source-code
```javascript
function ConvertVerb() {
  ConvertVerb.__super__.constructor.call(this, 'convert', _convert);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.verbs.peek"></a>[module hackmyresume.verbs.peek](#apidoc.module.hackmyresume.verbs.peek)

#### <a name="apidoc.element.hackmyresume.verbs.peek.peek"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>peek ()](#apidoc.element.hackmyresume.verbs.peek.peek)
- description and source-code
```javascript
function PeekVerb() {
  PeekVerb.__super__.constructor.call(this, 'peek', _peek);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.verbs.peek.prototype"></a>[module hackmyresume.verbs.peek.prototype](#apidoc.module.hackmyresume.verbs.peek.prototype)

#### <a name="apidoc.element.hackmyresume.verbs.peek.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.peek.prototype.</span>constructor ()](#apidoc.element.hackmyresume.verbs.peek.prototype.constructor)
- description and source-code
```javascript
function PeekVerb() {
  PeekVerb.__super__.constructor.call(this, 'peek', _peek);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.verbs.validate"></a>[module hackmyresume.verbs.validate](#apidoc.module.hackmyresume.verbs.validate)

#### <a name="apidoc.element.hackmyresume.verbs.validate.validate"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.</span>validate ()](#apidoc.element.hackmyresume.verbs.validate.validate)
- description and source-code
```javascript
function ValidateVerb() {
  ValidateVerb.__super__.constructor.call(this, 'validate', _validate);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hackmyresume.verbs.validate.prototype"></a>[module hackmyresume.verbs.validate.prototype](#apidoc.module.hackmyresume.verbs.validate.prototype)

#### <a name="apidoc.element.hackmyresume.verbs.validate.prototype.constructor"></a>[function <span class="apidocSignatureSpan">hackmyresume.verbs.validate.prototype.</span>constructor ()](#apidoc.element.hackmyresume.verbs.validate.prototype.constructor)
- description and source-code
```javascript
function ValidateVerb() {
  ValidateVerb.__super__.constructor.call(this, 'validate', _validate);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
