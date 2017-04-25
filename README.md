# npmdoc-datatables

#### basic api documentation for  [datatables (v1.10.13)](http://datatables.net)  [![npm package](https://img.shields.io/npm/v/npmdoc-datatables.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-datatables) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-datatables.svg)](https://travis-ci.org/npmdoc/node-npmdoc-datatables)

#### DataTables enhances HTML tables with the ability to sort, filter and page the data in the table very easily. It provides a comprehensive API and set of configuration options, allowing you to consume data from virtually any data source.

[![NPM](https://nodei.co/npm/datatables.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/datatables)

- [https://npmdoc.github.io/node-npmdoc-datatables/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-datatables/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-datatables/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-datatables/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-datatables/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-datatables/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Allan Jardine",
        "url": "http://sprymedia.co.uk"
    },
    "bugs": {
        "url": "https://github.com/DataTables/DataTables/issues"
    },
    "dependencies": {
        "jquery": ">=1.7"
    },
    "description": "DataTables enhances HTML tables with the ability to sort, filter and page the data in the table very easily. It provides a comprehensive API and set of configuration options, allowing you to consume data from virtually any data source.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "9bb2dec6f7dcf02049a00e4f0e7d3fe009c39346",
        "tarball": "https://registry.npmjs.org/datatables/-/datatables-1.10.13.tgz"
    },
    "files": [
        "media/js/jquery.dataTables.js",
        "media/js/jquery.dataTables.min.js",
        "media/css/jquery.dataTables.css",
        "media/css/jquery.dataTables.min.css",
        "media/images"
    ],
    "gitHead": "403128c42f7b263a0563e862decbe69734b834e8",
    "homepage": "http://datatables.net",
    "jspm": {
        "dependencies": {
            "css": "^0.1.5",
            "jquery": "*"
        },
        "registry": "jspm",
        "shim": {
            "media/js/jquery.dataTables": {
                "deps": [
                    "jquery",
                    "../css/jquery.dataTables.css!"
                ],
                "exports": "$"
            }
        }
    },
    "keywords": [
        "DataTables",
        "DataTable",
        "table",
        "grid",
        "filter",
        "sort",
        "page",
        "internationalisable",
        "jquery-plugin"
    ],
    "license": "MIT",
    "main": "media/js/jquery.dataTables",
    "maintainers": [
        {
            "name": "datatables"
        }
    ],
    "name": "datatables",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/DataTables/DataTables.git"
    },
    "scripts": {},
    "title": "DataTables",
    "version": "1.10.13",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
