# api documentation for  [grunt-ssh (v0.12.9)](https://github.com/israelroldan/grunt-ssh)  [![npm package](https://img.shields.io/npm/v/npmdoc-grunt-ssh.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-grunt-ssh) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-grunt-ssh.svg)](https://travis-ci.org/npmdoc/node-npmdoc-grunt-ssh)
#### SSH and SFTP tasks for Grunt

[![NPM](https://nodei.co/npm/grunt-ssh.png?downloads=true)](https://www.npmjs.com/package/grunt-ssh)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-ssh/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-grunt-ssh_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-ssh/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-grunt-ssh/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-grunt-ssh/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Jones",
        "email": "andrew@arjones.co.uk",
        "url": "http://andrew-jones.com"
    },
    "bugs": {
        "url": "https://github.com/israelroldan/grunt-ssh/issues"
    },
    "contributors": [
        {
            "name": "Andrew Jones",
            "email": "andrewjones86@googlemail.com"
        },
        {
            "name": "Andrew Jones",
            "email": "andrew@arjones.co.uk"
        },
        {
            "name": "Charlie Rosenbury",
            "email": "gmail@rosenbury.com"
        },
        {
            "name": "Marcin Szczepanski",
            "email": "marcins@webqem.com"
        },
        {
            "name": "andrewrjones",
            "email": "andrewjones86@googlemail.com"
        },
        {
            "name": "David J. Bradshaw",
            "email": "dave@bradshaw.net"
        },
        {
            "name": "John Wright",
            "email": "johngeorge.wright@gmail.com"
        },
        {
            "name": "John Wright",
            "email": "johnwright@fairfaxmedia.com.au"
        },
        {
            "name": "MFR",
            "email": "franc@fg.cz"
        },
        {
            "name": "rysi3k",
            "email": "rysi3k@gmail.com"
        },
        {
            "name": "xescuGC",
            "email": "xescugil@gmail.com"
        },
        {
            "name": "Mark Stosberg",
            "email": "mark@rideamigos.com"
        },
        {
            "name": "Andrew Stewart",
            "email": "andy@rocketboots.com"
        },
        {
            "name": "sheo13666",
            "email": "sheo13666q@gmail.com"
        },
        {
            "name": "Anders Johnson",
            "email": "adjohnson916@gmail.com"
        },
        {
            "name": "Robert Price",
            "email": "robert.price@gmail.com"
        },
        {
            "name": "Yannis Sgarra",
            "email": "yannis.sgarra@gmail.com"
        },
        {
            "name": "fayebear",
            "email": "lolbummer@gmail.com"
        },
        {
            "name": "harriha",
            "email": "harri.halikka@gmail.com"
        },
        {
            "name": "jabes",
            "email": "bull.justin@gmail.com"
        },
        {
            "name": "owenmead",
            "email": "owenmead@gmail.com"
        },
        {
            "name": "Jason Williams",
            "email": "jaswilli@gmail.com"
        },
        {
            "name": "Alexandre Richonnier",
            "email": "heralight+github@gmail.com"
        },
        {
            "name": "Andy Royle",
            "email": "ajroyle@gmail.com"
        },
        {
            "name": "Andy Shinn",
            "email": "andys@andyshinn.as"
        },
        {
            "name": "Bernd Matzner",
            "email": "bernd@matznermatzner.de"
        },
        {
            "name": "Brian White",
            "email": "mscdex@mscdex.net"
        },
        {
            "name": "Caleb Tomlinson",
            "email": "ctomlinson@opentable.com"
        },
        {
            "name": "Christoph Krautz",
            "email": "christoph.krautz@comerge.net"
        },
        {
            "name": "Evan Stoner",
            "email": "evan.stoner@gmail.com"
        },
        {
            "name": "Franco Luciano Aguilera",
            "email": "flaalf+git@gmail.com"
        },
        {
            "name": "Fredrik Boström",
            "email": "fredrik@fredrikbostrom.net"
        },
        {
            "name": "James Wyse",
            "email": "james@jameswyse.net"
        },
        {
            "name": "Alexander Afanasiev",
            "email": "afanasieffav@gmail.com"
        },
        {
            "name": "Justin Kulesza",
            "email": "justin.kulesza@atomicobject.com"
        },
        {
            "name": "Michael Lam",
            "email": "treadsafely@gmail.com"
        },
        {
            "name": "Niels van Aken",
            "email": "vanaken@10uur.nl"
        },
        {
            "name": "Uri Chandler",
            "email": "uri@kungfoo.bar"
        }
    ],
    "dependencies": {
        "async": ">=1.0.0",
        "progress": "~1.1.3",
        "ssh2": "~0.4.6"
    },
    "description": "SSH and SFTP tasks for Grunt",
    "devDependencies": {
        "grunt": "~0.4.1",
        "grunt-beautify": "git+https://github.com/terryweiss/grunt-beautify.git#FixForGrunt040",
        "grunt-bump": "~0.0.2",
        "grunt-cli": "~0.1",
        "grunt-contrib-jshint": "~0.1.1",
        "grunt-contrib-nodeunit": "~0.2.2",
        "grunt-npm": "0.0.2",
        "nodeunit": "~0.7.4",
        "sinon": "~1.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "21551a373981f0ea28dc799d38a769e54cd4d904",
        "tarball": "https://registry.npmjs.org/grunt-ssh/-/grunt-ssh-0.12.9.tgz"
    },
    "engines": {
        "node": ">= 0.8.7"
    },
    "gitHead": "f7b36c7089a9ab3d46224fe7bbfdcbf900530ef5",
    "homepage": "https://github.com/israelroldan/grunt-ssh",
    "keywords": [
        "gruntplugin",
        "ssh",
        "scp",
        "sftp",
        "remote",
        "exec",
        "rexec"
    ],
    "license": "MIT",
    "main": "grunt.js",
    "maintainers": [
        {
            "name": "andrewrjones",
            "email": "andrew@andrew-jones.com"
        },
        {
            "name": "chuckmo",
            "email": "gmail@rosenbury.com"
        },
        {
            "name": "israelroldan",
            "email": "israel@palu.io"
        }
    ],
    "name": "grunt-ssh",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": "~0.4.1"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/israelroldan/grunt-ssh.git"
    },
    "scripts": {
        "test": "grunt"
    },
    "version": "0.12.9"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module grunt-ssh](#apidoc.module.grunt-ssh)



# <a name="apidoc.module.grunt-ssh"></a>[module grunt-ssh](#apidoc.module.grunt-ssh)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
