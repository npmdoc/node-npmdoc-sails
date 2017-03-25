# api documentation for  [sails (v0.12.13)](http://sailsjs.org)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sails.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sails)
#### API-driven framework for building realtime apps, using MVC conventions (based on Express and Socket.io)

[![NPM](https://nodei.co/npm/sails.png?downloads=true)](https://www.npmjs.com/package/sails)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-sails_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-sails/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Mike McNeil",
        "email": "@mikermcneil"
    },
    "bin": {
        "sails": "./bin/sails.js"
    },
    "bugs": {
        "url": "http://github.com/balderdashy/sails/issues"
    },
    "dependencies": {
        "@sailshq/express": "^3.21.3",
        "@sailshq/lodash": "^3.10.2",
        "anchor": "~0.10.5",
        "async": "1.5.0",
        "captains-log": "1.0.0",
        "chalk": "1.1.3",
        "commander": "2.9.0",
        "compression": "1.6.2",
        "connect": "3.4.1",
        "connect-flash": "0.1.1",
        "consolidate": "0.14.1",
        "cookie": "0.1.2",
        "cookie-parser": "1.3.5",
        "cookie-signature": "1.0.6",
        "csurf": "1.9.0",
        "ejs": "2.3.4",
        "ejs-locals": "1.0.2",
        "express-handlebars": "3.0.0",
        "express-session": "1.14.2",
        "flaverr": "^1.0.0",
        "glob": "5.0.15",
        "grunt": "1.0.1",
        "grunt-cli": "1.2.0",
        "grunt-contrib-clean": "1.0.0",
        "grunt-contrib-coffee": "1.0.0",
        "grunt-contrib-concat": "1.0.1",
        "grunt-contrib-copy": "1.0.0",
        "grunt-contrib-cssmin": "1.0.1",
        "grunt-contrib-jst": "1.0.0",
        "grunt-contrib-less": "1.3.0",
        "grunt-contrib-uglify": "1.0.1",
        "grunt-contrib-watch": "1.0.0",
        "grunt-sails-linker": "~0.10.1",
        "grunt-sync": "0.5.2",
        "i18n": "0.8.1",
        "include-all": "^1.0.0",
        "merge-defaults": "~0.2.1",
        "method-override": "2.3.5",
        "mock-req": "0.2.0",
        "mock-res": "0.3.0",
        "parseurl": "1.3.1",
        "path-to-regexp": "1.5.3",
        "pluralize": "1.2.1",
        "prompt": "0.2.14",
        "rc": "1.0.1",
        "reportback": "~0.1.9",
        "rttc": "9.3.3",
        "sails-disk": "~0.10.9",
        "sails-generate": "~0.13.0",
        "sails-hook-orm": "~1.0.9",
        "sails-hook-sockets": "^0.13.9",
        "sails-stringfile": "~0.3.2",
        "sails-util": "~0.11.0",
        "semver": "5.1.0",
        "serve-favicon": "2.3.0",
        "serve-static": "1.10.2",
        "skipper": "~0.7.0",
        "uid-safe": "1.1.0",
        "walk": "2.3.9"
    },
    "description": "API-driven framework for building realtime apps, using MVC conventions (based on Express and Socket.io)",
    "devDependencies": {
        "benchmark": "1.0.0",
        "checksum": "0.1.1",
        "coffee-script": "1.9.1",
        "expect.js": "0.3.1",
        "fs-extra": "0.30.0",
        "istanbul": "0.4.1",
        "machinepack-fs": "^8.0.2",
        "machinepack-process": "^2.0.2",
        "mocha": "3.0.0",
        "portfinder": "0.4.0",
        "request": "2.68.0",
        "root-require": "0.3.1",
        "should": "5.2.0",
        "socket.io-client": "1.4.6",
        "supertest": "1.1.0",
        "tmp": "0.0.30"
    },
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "e060710dd1080bee11840f8f085e396f8aa08ff4",
        "tarball": "https://registry.npmjs.org/sails/-/sails-0.12.13.tgz"
    },
    "engines": {
        "node": ">= 0.10.0",
        "npm": ">= 1.4.0"
    },
    "gitHead": "594cd89d5989c9e4fcab094a39174793cf6128ed",
    "homepage": "http://sailsjs.org",
    "keywords": [
        "mvc",
        "web-framework",
        "express",
        "sailsjs",
        "sails.js",
        "REST",
        "API",
        "orm",
        "socket.io"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "balderdashy",
            "email": "mike@balderdashdesign.com"
        },
        {
            "name": "particlebanana",
            "email": "particlebanana@gmail.com"
        },
        {
            "name": "sgress454",
            "email": "scott@balderdash.co"
        },
        {
            "name": "mikermcneil",
            "email": "michael.r.mcneil@gmail.com"
        }
    ],
    "name": "sails",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/balderdashy/sails.git"
    },
    "scripts": {
        "preinstall": "node ./lib/preinstall_npmcheck.js",
        "prepublish": "npm prune",
        "test": "mocha -b"
    },
    "version": "0.12.13"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module sails](#apidoc.module.sails)
1.  [function <span class="apidocSignatureSpan">sails.</span>Sails ()](#apidoc.element.sails.Sails)
1.  [function <span class="apidocSignatureSpan">sails.</span>after (events, fn)](#apidoc.element.sails.after)
1.  [function <span class="apidocSignatureSpan">sails.</span>all ()](#apidoc.element.sails.all)
1.  [function <span class="apidocSignatureSpan">sails.</span>delete ()](#apidoc.element.sails.delete)
1.  [function <span class="apidocSignatureSpan">sails.</span>emit (evName)](#apidoc.element.sails.emit)
1.  [function <span class="apidocSignatureSpan">sails.</span>exposeGlobals ()](#apidoc.element.sails.exposeGlobals)
1.  [function <span class="apidocSignatureSpan">sails.</span>get ()](#apidoc.element.sails.get)
1.  [function <span class="apidocSignatureSpan">sails.</span>getBaseurl ()](#apidoc.element.sails.getBaseurl)
1.  [function <span class="apidocSignatureSpan">sails.</span>getHost ()](#apidoc.element.sails.getHost)
1.  [function <span class="apidocSignatureSpan">sails.</span>initialize ()](#apidoc.element.sails.initialize)
1.  [function <span class="apidocSignatureSpan">sails.</span>inspect ()](#apidoc.element.sails.inspect)
1.  [function <span class="apidocSignatureSpan">sails.</span>isLocalSailsValid ()](#apidoc.element.sails.isLocalSailsValid)
1.  [function <span class="apidocSignatureSpan">sails.</span>isSailsAppSync ()](#apidoc.element.sails.isSailsAppSync)
1.  [function <span class="apidocSignatureSpan">sails.</span>lift ()](#apidoc.element.sails.lift)
1.  [function <span class="apidocSignatureSpan">sails.</span>load ()](#apidoc.element.sails.load)
1.  [function <span class="apidocSignatureSpan">sails.</span>log ()](#apidoc.element.sails.log)
1.  [function <span class="apidocSignatureSpan">sails.</span>lower ()](#apidoc.element.sails.lower)
1.  [function <span class="apidocSignatureSpan">sails.</span>post ()](#apidoc.element.sails.post)
1.  [function <span class="apidocSignatureSpan">sails.</span>put ()](#apidoc.element.sails.put)
1.  [function <span class="apidocSignatureSpan">sails.</span>request ()](#apidoc.element.sails.request)
1.  [function <span class="apidocSignatureSpan">sails.</span>router._privateRouter (req, res, next)](#apidoc.element.sails.router._privateRouter)
1.  [function <span class="apidocSignatureSpan">sails.</span>runBootstrap ()](#apidoc.element.sails.runBootstrap)
1.  [function <span class="apidocSignatureSpan">sails.</span>toJSON ()](#apidoc.element.sails.toJSON)
1.  number <span class="apidocSignatureSpan">sails.</span>_eventsCount
1.  number <span class="apidocSignatureSpan">sails.</span>_maxListeners
1.  object <span class="apidocSignatureSpan">sails.</span>_events
1.  object <span class="apidocSignatureSpan">sails.</span>childProcesses
1.  object <span class="apidocSignatureSpan">sails.</span>domain
1.  object <span class="apidocSignatureSpan">sails.</span>router
1.  object <span class="apidocSignatureSpan">sails.</span>router.defaultHandlers
1.  object <span class="apidocSignatureSpan">sails.</span>warmEvents

#### [module sails.Sails](#apidoc.module.sails.Sails)
1.  [function <span class="apidocSignatureSpan">sails.</span>Sails ()](#apidoc.element.sails.Sails.Sails)
1.  [function <span class="apidocSignatureSpan">sails.Sails.</span>isLocalSailsValid ()](#apidoc.element.sails.Sails.isLocalSailsValid)
1.  [function <span class="apidocSignatureSpan">sails.Sails.</span>isSailsAppSync ()](#apidoc.element.sails.Sails.isSailsAppSync)

#### [module sails.log](#apidoc.module.sails.log)
1.  [function <span class="apidocSignatureSpan">sails.</span>log ()](#apidoc.element.sails.log.log)
1.  [function <span class="apidocSignatureSpan">sails.log.</span>blank ()](#apidoc.element.sails.log.blank)
1.  [function <span class="apidocSignatureSpan">sails.log.</span>crit ()](#apidoc.element.sails.log.crit)
1.  [function <span class="apidocSignatureSpan">sails.log.</span>debug ()](#apidoc.element.sails.log.debug)
1.  [function <span class="apidocSignatureSpan">sails.log.</span>error ()](#apidoc.element.sails.log.error)
1.  [function <span class="apidocSignatureSpan">sails.log.</span>info ()](#apidoc.element.sails.log.info)
1.  [function <span class="apidocSignatureSpan">sails.log.</span>silly ()](#apidoc.element.sails.log.silly)
1.  [function <span class="apidocSignatureSpan">sails.log.</span>verbose ()](#apidoc.element.sails.log.verbose)
1.  [function <span class="apidocSignatureSpan">sails.log.</span>warn ()](#apidoc.element.sails.log.warn)

#### [module sails.router](#apidoc.module.sails.router)
1.  [function <span class="apidocSignatureSpan">sails.router.</span>_privateRouter (req, res, next)](#apidoc.element.sails.router._privateRouter)
1.  [function <span class="apidocSignatureSpan">sails.router.</span>bind ()](#apidoc.element.sails.router.bind)
1.  [function <span class="apidocSignatureSpan">sails.router.</span>flush ()](#apidoc.element.sails.router.flush)
1.  [function <span class="apidocSignatureSpan">sails.router.</span>load ()](#apidoc.element.sails.router.load)
1.  [function <span class="apidocSignatureSpan">sails.router.</span>reset ()](#apidoc.element.sails.router.reset)
1.  [function <span class="apidocSignatureSpan">sails.router.</span>route ()](#apidoc.element.sails.router.route)
1.  [function <span class="apidocSignatureSpan">sails.router.</span>unbind ()](#apidoc.element.sails.router.unbind)
1.  object <span class="apidocSignatureSpan">sails.router.</span>defaultHandlers
1.  object <span class="apidocSignatureSpan">sails.router.</span>sails

#### [module sails.router._privateRouter](#apidoc.module.sails.router._privateRouter)
1.  boolean <span class="apidocSignatureSpan">sails.router._privateRouter.</span>_usedRouter
1.  [function <span class="apidocSignatureSpan">sails.router.</span>_privateRouter (req, res, next)](#apidoc.element.sails.router._privateRouter._privateRouter)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>acl (path)](#apidoc.element.sails.router._privateRouter.acl)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>addListener (type, listener)](#apidoc.element.sails.router._privateRouter.addListener)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>all (path)](#apidoc.element.sails.router._privateRouter.all)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>bind (path)](#apidoc.element.sails.router._privateRouter.bind)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>checkout (path)](#apidoc.element.sails.router._privateRouter.checkout)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>configure (arg0, arg1)](#apidoc.element.sails.router._privateRouter.configure)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>connect (path)](#apidoc.element.sails.router._privateRouter.connect)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>copy (path)](#apidoc.element.sails.router._privateRouter.copy)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>defaultConfiguration ()](#apidoc.element.sails.router._privateRouter.defaultConfiguration)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>del (arg0)](#apidoc.element.sails.router._privateRouter.del)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>delete (path)](#apidoc.element.sails.router._privateRouter.delete)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>disable (setting)](#apidoc.element.sails.router._privateRouter.disable)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>disabled (setting)](#apidoc.element.sails.router._privateRouter.disabled)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>emit (type)](#apidoc.element.sails.router._privateRouter.emit)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>enable (setting)](#apidoc.element.sails.router._privateRouter.enable)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>enabled (setting)](#apidoc.element.sails.router._privateRouter.enabled)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>engine (ext, fn)](#apidoc.element.sails.router._privateRouter.engine)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>eventNames ()](#apidoc.element.sails.router._privateRouter.eventNames)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>get (path)](#apidoc.element.sails.router._privateRouter.get)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>getMaxListeners ()](#apidoc.element.sails.router._privateRouter.getMaxListeners)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>handle (req, res, out)](#apidoc.element.sails.router._privateRouter.handle)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>head (path)](#apidoc.element.sails.router._privateRouter.head)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>init ()](#apidoc.element.sails.router._privateRouter.init)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>link (path)](#apidoc.element.sails.router._privateRouter.link)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>listen ()](#apidoc.element.sails.router._privateRouter.listen)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>listenerCount (type)](#apidoc.element.sails.router._privateRouter.listenerCount)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>listeners (type)](#apidoc.element.sails.router._privateRouter.listeners)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>locals (obj)](#apidoc.element.sails.router._privateRouter.locals)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>lock (path)](#apidoc.element.sails.router._privateRouter.lock)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>m-search (path)](#apidoc.element.sails.router._privateRouter.m-search)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>merge (path)](#apidoc.element.sails.router._privateRouter.merge)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>mkactivity (path)](#apidoc.element.sails.router._privateRouter.mkactivity)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>mkcalendar (path)](#apidoc.element.sails.router._privateRouter.mkcalendar)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>mkcol (path)](#apidoc.element.sails.router._privateRouter.mkcol)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>move (path)](#apidoc.element.sails.router._privateRouter.move)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>notify (path)](#apidoc.element.sails.router._privateRouter.notify)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>on (type, listener)](#apidoc.element.sails.router._privateRouter.on)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>once (type, listener)](#apidoc.element.sails.router._privateRouter.once)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>options (path)](#apidoc.element.sails.router._privateRouter.options)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>param (name, fn)](#apidoc.element.sails.router._privateRouter.param)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>patch (path)](#apidoc.element.sails.router._privateRouter.patch)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>path ()](#apidoc.element.sails.router._privateRouter.path)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>post (path)](#apidoc.element.sails.router._privateRouter.post)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>prependListener (type, listener)](#apidoc.element.sails.router._privateRouter.prependListener)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>prependOnceListener (type, listener)](#apidoc.element.sails.router._privateRouter.prependOnceListener)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>propfind (path)](#apidoc.element.sails.router._privateRouter.propfind)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>proppatch (path)](#apidoc.element.sails.router._privateRouter.proppatch)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>purge (path)](#apidoc.element.sails.router._privateRouter.purge)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>put (path)](#apidoc.element.sails.router._privateRouter.put)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>rebind (path)](#apidoc.element.sails.router._privateRouter.rebind)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>removeAllListeners (type)](#apidoc.element.sails.router._privateRouter.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>removeListener (type, listener)](#apidoc.element.sails.router._privateRouter.removeListener)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>render (name, options, fn)](#apidoc.element.sails.router._privateRouter.render)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>report (path)](#apidoc.element.sails.router._privateRouter.report)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>router (req, res, next)](#apidoc.element.sails.router._privateRouter.router)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>search (path)](#apidoc.element.sails.router._privateRouter.search)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>set (setting, val)](#apidoc.element.sails.router._privateRouter.set)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>setMaxListeners (n)](#apidoc.element.sails.router._privateRouter.setMaxListeners)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>subscribe (path)](#apidoc.element.sails.router._privateRouter.subscribe)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>trace (path)](#apidoc.element.sails.router._privateRouter.trace)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>unbind (path)](#apidoc.element.sails.router._privateRouter.unbind)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>unlink (path)](#apidoc.element.sails.router._privateRouter.unlink)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>unlock (path)](#apidoc.element.sails.router._privateRouter.unlock)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>unsubscribe (path)](#apidoc.element.sails.router._privateRouter.unsubscribe)
1.  [function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>use (route, fn)](#apidoc.element.sails.router._privateRouter.use)
1.  number <span class="apidocSignatureSpan">sails.router._privateRouter.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">sails.router._privateRouter.</span>_events
1.  object <span class="apidocSignatureSpan">sails.router._privateRouter.</span>_router
1.  object <span class="apidocSignatureSpan">sails.router._privateRouter.</span>cache
1.  object <span class="apidocSignatureSpan">sails.router._privateRouter.</span>engines
1.  object <span class="apidocSignatureSpan">sails.router._privateRouter.</span>request
1.  object <span class="apidocSignatureSpan">sails.router._privateRouter.</span>response
1.  object <span class="apidocSignatureSpan">sails.router._privateRouter.</span>routes
1.  object <span class="apidocSignatureSpan">sails.router._privateRouter.</span>settings
1.  object <span class="apidocSignatureSpan">sails.router._privateRouter.</span>stack
1.  string <span class="apidocSignatureSpan">sails.router._privateRouter.</span>route
1.  undefined <span class="apidocSignatureSpan">sails.router._privateRouter.</span>domain

#### [module sails.router.defaultHandlers](#apidoc.module.sails.router.defaultHandlers)
1.  [function <span class="apidocSignatureSpan">sails.router.defaultHandlers.</span>404 (req, res)](#apidoc.element.sails.router.defaultHandlers.404)
1.  [function <span class="apidocSignatureSpan">sails.router.defaultHandlers.</span>500 (err, req, res)](#apidoc.element.sails.router.defaultHandlers.500)



# <a name="apidoc.module.sails"></a>[module sails](#apidoc.module.sails)

#### <a name="apidoc.element.sails.Sails"></a>[function <span class="apidocSignatureSpan">sails.</span>Sails ()](#apidoc.element.sails.Sails)
- description and source-code
```javascript
function SailsFactory() {
  return new Sails();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.after"></a>[function <span class="apidocSignatureSpan">sails.</span>after (events, fn)](#apidoc.element.sails.after)
- description and source-code
```javascript
after = function (events, fn) {

  // Support a single event or an array of events
  if (!_.isArray(events)) {
    events = [events];
  }

  // Convert named event dependencies into an array
  // of async-compatible functions.
  var dependencies = _.reduce(events,
    function(dependencies, event) {

      var handlerFn = function(cb) {
        if (emitter.warmEvents[event]) {
          cb();
        } else {
          emitter.once(event, cb);
        }
      };
      dependencies.push(handlerFn);
      return dependencies;
    }, []);

  // When all events have fired, call 'fn'
  // (all arguments passed to 'emit()' calls are discarded)
  async.parallel(dependencies, function(err) {
    if (err) sails.log.error(err);
    return fn();
  });

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.all"></a>[function <span class="apidocSignatureSpan">sails.</span>all ()](#apidoc.element.sails.all)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.delete"></a>[function <span class="apidocSignatureSpan">sails.</span>delete ()](#apidoc.element.sails.delete)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.emit"></a>[function <span class="apidocSignatureSpan">sails.</span>emit (evName)](#apidoc.element.sails.emit)
- description and source-code
```javascript
emit = function (evName) {
  var args = Array.prototype.slice.call(arguments, 0);
  emitter.warmEvents[evName] = true;
  _emit.apply(emitter, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.exposeGlobals"></a>[function <span class="apidocSignatureSpan">sails.</span>exposeGlobals ()](#apidoc.element.sails.exposeGlobals)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.get"></a>[function <span class="apidocSignatureSpan">sails.</span>get ()](#apidoc.element.sails.get)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.getBaseurl"></a>[function <span class="apidocSignatureSpan">sails.</span>getBaseurl ()](#apidoc.element.sails.getBaseurl)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.getHost"></a>[function <span class="apidocSignatureSpan">sails.</span>getHost ()](#apidoc.element.sails.getHost)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.initialize"></a>[function <span class="apidocSignatureSpan">sails.</span>initialize ()](#apidoc.element.sails.initialize)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.inspect"></a>[function <span class="apidocSignatureSpan">sails.</span>inspect ()](#apidoc.element.sails.inspect)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.isLocalSailsValid"></a>[function <span class="apidocSignatureSpan">sails.</span>isLocalSailsValid ()](#apidoc.element.sails.isLocalSailsValid)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.isSailsAppSync"></a>[function <span class="apidocSignatureSpan">sails.</span>isSailsAppSync ()](#apidoc.element.sails.isSailsAppSync)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.lift"></a>[function <span class="apidocSignatureSpan">sails.</span>lift ()](#apidoc.element.sails.lift)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.load"></a>[function <span class="apidocSignatureSpan">sails.</span>load ()](#apidoc.element.sails.load)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.log"></a>[function <span class="apidocSignatureSpan">sails.</span>log ()](#apidoc.element.sails.log)
- description and source-code
```javascript
function _writeLogToConsole() {

  // Check 'options.level' against logAt
  // to see whether to write the log.
  // ( silly = 0 | silent = highest )
  var lvlMap = options.logLevels;
  var configuredLvl = options.level;
  if (lvlMap[logAt] < lvlMap[configuredLvl]) { return; }


  var args = Array.prototype.slice.call(arguments);

  /////////////////////////////////////////////////////////////////
  // For backwards-compatibility:
  // (options.inspect should always be true going forward)
  //
  // Note that prefixes and other options will not work with
  // 'inspect===false'.  New features will also not support
  // inspect:false.
  //
  // If 'options.inspect' is disabled, just call the log fn normally
  if (!options.inspect) {
    return logFn.apply(logFn, args);
  }
  /////////////////////////////////////////////////////////////////

  // For reference on the following impl, see:
  // https://github.com/defunctzombie/node-util/blob/master/util.js#L22

  // Combine the arguments passed into the log fn
  var pieces = [];
  _.each(args, function(arg) {

    // Your everyday JavaScript errors
    if (_.isError(arg) && arg.stack && !arg.inspect) {
      pieces.push(arg.stack);
    }
    // Non-strings
    // (miscellaneous arrays, dictionaries, mysterious objects, etc)
    else if (!_.isString(arg)) {
      if (options.inspectOptions) {
        pieces.push(util.inspect(arg, options.inspectOptions));
      }
      else { pieces.push(util.inspect(arg)); }
      return;
    }
    // Strings
    else {
      pieces.push(arg);
    }

  });

  // Compose 'str' of all the arguments
  // (include the appropriate prefix if specified)
  var prefixStr = (options.prefixes && options.prefixes[logAt]) || '';
  var str = prefixStr + util.format.apply(util, pieces);

  // Call log fn
  return logFn.apply(logFn, [str]);
}
```
- example usage
```shell
...
 if (!satisfiesVersion(version, requiredNpmVersion)) exitWithMessage([
   'Your current npm version (' + version + ') is not supported:',
   'Sails requires at least version ' + project.engines.npm,
   '',
   'Try uploading npm before installing Sails.'
 ]);

 console.log('Sails.js Installation: Checking npm-version successful');

 // Exit process with success.
 process.exit(0);
}

/**
* Exit proccess with a given error beautifully.
...
```

#### <a name="apidoc.element.sails.lower"></a>[function <span class="apidocSignatureSpan">sails.</span>lower ()](#apidoc.element.sails.lower)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.post"></a>[function <span class="apidocSignatureSpan">sails.</span>post ()](#apidoc.element.sails.post)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.put"></a>[function <span class="apidocSignatureSpan">sails.</span>put ()](#apidoc.element.sails.put)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.request"></a>[function <span class="apidocSignatureSpan">sails.</span>request ()](#apidoc.element.sails.request)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter"></a>[function <span class="apidocSignatureSpan">sails.</span>router._privateRouter (req, res, next)](#apidoc.element.sails.router._privateRouter)
- description and source-code
```javascript
function app(req, res, next){ app.handle(req, res, next); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.runBootstrap"></a>[function <span class="apidocSignatureSpan">sails.</span>runBootstrap ()](#apidoc.element.sails.runBootstrap)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.toJSON"></a>[function <span class="apidocSignatureSpan">sails.</span>toJSON ()](#apidoc.element.sails.toJSON)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sails.Sails"></a>[module sails.Sails](#apidoc.module.sails.Sails)

#### <a name="apidoc.element.sails.Sails.Sails"></a>[function <span class="apidocSignatureSpan">sails.</span>Sails ()](#apidoc.element.sails.Sails.Sails)
- description and source-code
```javascript
function SailsFactory() {
  return new Sails();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.Sails.isLocalSailsValid"></a>[function <span class="apidocSignatureSpan">sails.Sails.</span>isLocalSailsValid ()](#apidoc.element.sails.Sails.isLocalSailsValid)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.Sails.isSailsAppSync"></a>[function <span class="apidocSignatureSpan">sails.Sails.</span>isSailsAppSync ()](#apidoc.element.sails.Sails.isSailsAppSync)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sails.log"></a>[module sails.log](#apidoc.module.sails.log)

#### <a name="apidoc.element.sails.log.log"></a>[function <span class="apidocSignatureSpan">sails.</span>log ()](#apidoc.element.sails.log.log)
- description and source-code
```javascript
function _writeLogToConsole() {

  // Check 'options.level' against logAt
  // to see whether to write the log.
  // ( silly = 0 | silent = highest )
  var lvlMap = options.logLevels;
  var configuredLvl = options.level;
  if (lvlMap[logAt] < lvlMap[configuredLvl]) { return; }


  var args = Array.prototype.slice.call(arguments);

  /////////////////////////////////////////////////////////////////
  // For backwards-compatibility:
  // (options.inspect should always be true going forward)
  //
  // Note that prefixes and other options will not work with
  // 'inspect===false'.  New features will also not support
  // inspect:false.
  //
  // If 'options.inspect' is disabled, just call the log fn normally
  if (!options.inspect) {
    return logFn.apply(logFn, args);
  }
  /////////////////////////////////////////////////////////////////

  // For reference on the following impl, see:
  // https://github.com/defunctzombie/node-util/blob/master/util.js#L22

  // Combine the arguments passed into the log fn
  var pieces = [];
  _.each(args, function(arg) {

    // Your everyday JavaScript errors
    if (_.isError(arg) && arg.stack && !arg.inspect) {
      pieces.push(arg.stack);
    }
    // Non-strings
    // (miscellaneous arrays, dictionaries, mysterious objects, etc)
    else if (!_.isString(arg)) {
      if (options.inspectOptions) {
        pieces.push(util.inspect(arg, options.inspectOptions));
      }
      else { pieces.push(util.inspect(arg)); }
      return;
    }
    // Strings
    else {
      pieces.push(arg);
    }

  });

  // Compose 'str' of all the arguments
  // (include the appropriate prefix if specified)
  var prefixStr = (options.prefixes && options.prefixes[logAt]) || '';
  var str = prefixStr + util.format.apply(util, pieces);

  // Call log fn
  return logFn.apply(logFn, [str]);
}
```
- example usage
```shell
...
 if (!satisfiesVersion(version, requiredNpmVersion)) exitWithMessage([
   'Your current npm version (' + version + ') is not supported:',
   'Sails requires at least version ' + project.engines.npm,
   '',
   'Try uploading npm before installing Sails.'
 ]);

 console.log('Sails.js Installation: Checking npm-version successful');

 // Exit process with success.
 process.exit(0);
}

/**
* Exit proccess with a given error beautifully.
...
```

#### <a name="apidoc.element.sails.log.blank"></a>[function <span class="apidocSignatureSpan">sails.log.</span>blank ()](#apidoc.element.sails.log.blank)
- description and source-code
```javascript
function _writeLogToConsole() {

  // Check 'options.level' against logAt
  // to see whether to write the log.
  // ( silly = 0 | silent = highest )
  var lvlMap = options.logLevels;
  var configuredLvl = options.level;
  if (lvlMap[logAt] < lvlMap[configuredLvl]) { return; }


  var args = Array.prototype.slice.call(arguments);

  /////////////////////////////////////////////////////////////////
  // For backwards-compatibility:
  // (options.inspect should always be true going forward)
  //
  // Note that prefixes and other options will not work with
  // 'inspect===false'.  New features will also not support
  // inspect:false.
  //
  // If 'options.inspect' is disabled, just call the log fn normally
  if (!options.inspect) {
    return logFn.apply(logFn, args);
  }
  /////////////////////////////////////////////////////////////////

  // For reference on the following impl, see:
  // https://github.com/defunctzombie/node-util/blob/master/util.js#L22

  // Combine the arguments passed into the log fn
  var pieces = [];
  _.each(args, function(arg) {

    // Your everyday JavaScript errors
    if (_.isError(arg) && arg.stack && !arg.inspect) {
      pieces.push(arg.stack);
    }
    // Non-strings
    // (miscellaneous arrays, dictionaries, mysterious objects, etc)
    else if (!_.isString(arg)) {
      if (options.inspectOptions) {
        pieces.push(util.inspect(arg, options.inspectOptions));
      }
      else { pieces.push(util.inspect(arg)); }
      return;
    }
    // Strings
    else {
      pieces.push(arg);
    }

  });

  // Compose 'str' of all the arguments
  // (include the appropriate prefix if specified)
  var prefixStr = (options.prefixes && options.prefixes[logAt]) || '';
  var str = prefixStr + util.format.apply(util, pieces);

  // Call log fn
  return logFn.apply(logFn, [str]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.log.crit"></a>[function <span class="apidocSignatureSpan">sails.log.</span>crit ()](#apidoc.element.sails.log.crit)
- description and source-code
```javascript
function _writeLogToConsole() {

  // Check 'options.level' against logAt
  // to see whether to write the log.
  // ( silly = 0 | silent = highest )
  var lvlMap = options.logLevels;
  var configuredLvl = options.level;
  if (lvlMap[logAt] < lvlMap[configuredLvl]) { return; }


  var args = Array.prototype.slice.call(arguments);

  /////////////////////////////////////////////////////////////////
  // For backwards-compatibility:
  // (options.inspect should always be true going forward)
  //
  // Note that prefixes and other options will not work with
  // 'inspect===false'.  New features will also not support
  // inspect:false.
  //
  // If 'options.inspect' is disabled, just call the log fn normally
  if (!options.inspect) {
    return logFn.apply(logFn, args);
  }
  /////////////////////////////////////////////////////////////////

  // For reference on the following impl, see:
  // https://github.com/defunctzombie/node-util/blob/master/util.js#L22

  // Combine the arguments passed into the log fn
  var pieces = [];
  _.each(args, function(arg) {

    // Your everyday JavaScript errors
    if (_.isError(arg) && arg.stack && !arg.inspect) {
      pieces.push(arg.stack);
    }
    // Non-strings
    // (miscellaneous arrays, dictionaries, mysterious objects, etc)
    else if (!_.isString(arg)) {
      if (options.inspectOptions) {
        pieces.push(util.inspect(arg, options.inspectOptions));
      }
      else { pieces.push(util.inspect(arg)); }
      return;
    }
    // Strings
    else {
      pieces.push(arg);
    }

  });

  // Compose 'str' of all the arguments
  // (include the appropriate prefix if specified)
  var prefixStr = (options.prefixes && options.prefixes[logAt]) || '';
  var str = prefixStr + util.format.apply(util, pieces);

  // Call log fn
  return logFn.apply(logFn, [str]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.log.debug"></a>[function <span class="apidocSignatureSpan">sails.log.</span>debug ()](#apidoc.element.sails.log.debug)
- description and source-code
```javascript
function _writeLogToConsole() {

  // Check 'options.level' against logAt
  // to see whether to write the log.
  // ( silly = 0 | silent = highest )
  var lvlMap = options.logLevels;
  var configuredLvl = options.level;
  if (lvlMap[logAt] < lvlMap[configuredLvl]) { return; }


  var args = Array.prototype.slice.call(arguments);

  /////////////////////////////////////////////////////////////////
  // For backwards-compatibility:
  // (options.inspect should always be true going forward)
  //
  // Note that prefixes and other options will not work with
  // 'inspect===false'.  New features will also not support
  // inspect:false.
  //
  // If 'options.inspect' is disabled, just call the log fn normally
  if (!options.inspect) {
    return logFn.apply(logFn, args);
  }
  /////////////////////////////////////////////////////////////////

  // For reference on the following impl, see:
  // https://github.com/defunctzombie/node-util/blob/master/util.js#L22

  // Combine the arguments passed into the log fn
  var pieces = [];
  _.each(args, function(arg) {

    // Your everyday JavaScript errors
    if (_.isError(arg) && arg.stack && !arg.inspect) {
      pieces.push(arg.stack);
    }
    // Non-strings
    // (miscellaneous arrays, dictionaries, mysterious objects, etc)
    else if (!_.isString(arg)) {
      if (options.inspectOptions) {
        pieces.push(util.inspect(arg, options.inspectOptions));
      }
      else { pieces.push(util.inspect(arg)); }
      return;
    }
    // Strings
    else {
      pieces.push(arg);
    }

  });

  // Compose 'str' of all the arguments
  // (include the appropriate prefix if specified)
  var prefixStr = (options.prefixes && options.prefixes[logAt]) || '';
  var str = prefixStr + util.format.apply(util, pieces);

  // Call log fn
  return logFn.apply(logFn, [str]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.log.error"></a>[function <span class="apidocSignatureSpan">sails.log.</span>error ()](#apidoc.element.sails.log.error)
- description and source-code
```javascript
function _writeLogToConsole() {

  // Check 'options.level' against logAt
  // to see whether to write the log.
  // ( silly = 0 | silent = highest )
  var lvlMap = options.logLevels;
  var configuredLvl = options.level;
  if (lvlMap[logAt] < lvlMap[configuredLvl]) { return; }


  var args = Array.prototype.slice.call(arguments);

  /////////////////////////////////////////////////////////////////
  // For backwards-compatibility:
  // (options.inspect should always be true going forward)
  //
  // Note that prefixes and other options will not work with
  // 'inspect===false'.  New features will also not support
  // inspect:false.
  //
  // If 'options.inspect' is disabled, just call the log fn normally
  if (!options.inspect) {
    return logFn.apply(logFn, args);
  }
  /////////////////////////////////////////////////////////////////

  // For reference on the following impl, see:
  // https://github.com/defunctzombie/node-util/blob/master/util.js#L22

  // Combine the arguments passed into the log fn
  var pieces = [];
  _.each(args, function(arg) {

    // Your everyday JavaScript errors
    if (_.isError(arg) && arg.stack && !arg.inspect) {
      pieces.push(arg.stack);
    }
    // Non-strings
    // (miscellaneous arrays, dictionaries, mysterious objects, etc)
    else if (!_.isString(arg)) {
      if (options.inspectOptions) {
        pieces.push(util.inspect(arg, options.inspectOptions));
      }
      else { pieces.push(util.inspect(arg)); }
      return;
    }
    // Strings
    else {
      pieces.push(arg);
    }

  });

  // Compose 'str' of all the arguments
  // (include the appropriate prefix if specified)
  var prefixStr = (options.prefixes && options.prefixes[logAt]) || '';
  var str = prefixStr + util.format.apply(util, pieces);

  // Call log fn
  return logFn.apply(logFn, [str]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.log.info"></a>[function <span class="apidocSignatureSpan">sails.log.</span>info ()](#apidoc.element.sails.log.info)
- description and source-code
```javascript
function _writeLogToConsole() {

  // Check 'options.level' against logAt
  // to see whether to write the log.
  // ( silly = 0 | silent = highest )
  var lvlMap = options.logLevels;
  var configuredLvl = options.level;
  if (lvlMap[logAt] < lvlMap[configuredLvl]) { return; }


  var args = Array.prototype.slice.call(arguments);

  /////////////////////////////////////////////////////////////////
  // For backwards-compatibility:
  // (options.inspect should always be true going forward)
  //
  // Note that prefixes and other options will not work with
  // 'inspect===false'.  New features will also not support
  // inspect:false.
  //
  // If 'options.inspect' is disabled, just call the log fn normally
  if (!options.inspect) {
    return logFn.apply(logFn, args);
  }
  /////////////////////////////////////////////////////////////////

  // For reference on the following impl, see:
  // https://github.com/defunctzombie/node-util/blob/master/util.js#L22

  // Combine the arguments passed into the log fn
  var pieces = [];
  _.each(args, function(arg) {

    // Your everyday JavaScript errors
    if (_.isError(arg) && arg.stack && !arg.inspect) {
      pieces.push(arg.stack);
    }
    // Non-strings
    // (miscellaneous arrays, dictionaries, mysterious objects, etc)
    else if (!_.isString(arg)) {
      if (options.inspectOptions) {
        pieces.push(util.inspect(arg, options.inspectOptions));
      }
      else { pieces.push(util.inspect(arg)); }
      return;
    }
    // Strings
    else {
      pieces.push(arg);
    }

  });

  // Compose 'str' of all the arguments
  // (include the appropriate prefix if specified)
  var prefixStr = (options.prefixes && options.prefixes[logAt]) || '';
  var str = prefixStr + util.format.apply(util, pieces);

  // Call log fn
  return logFn.apply(logFn, [str]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.log.silly"></a>[function <span class="apidocSignatureSpan">sails.log.</span>silly ()](#apidoc.element.sails.log.silly)
- description and source-code
```javascript
function _writeLogToConsole() {

  // Check 'options.level' against logAt
  // to see whether to write the log.
  // ( silly = 0 | silent = highest )
  var lvlMap = options.logLevels;
  var configuredLvl = options.level;
  if (lvlMap[logAt] < lvlMap[configuredLvl]) { return; }


  var args = Array.prototype.slice.call(arguments);

  /////////////////////////////////////////////////////////////////
  // For backwards-compatibility:
  // (options.inspect should always be true going forward)
  //
  // Note that prefixes and other options will not work with
  // 'inspect===false'.  New features will also not support
  // inspect:false.
  //
  // If 'options.inspect' is disabled, just call the log fn normally
  if (!options.inspect) {
    return logFn.apply(logFn, args);
  }
  /////////////////////////////////////////////////////////////////

  // For reference on the following impl, see:
  // https://github.com/defunctzombie/node-util/blob/master/util.js#L22

  // Combine the arguments passed into the log fn
  var pieces = [];
  _.each(args, function(arg) {

    // Your everyday JavaScript errors
    if (_.isError(arg) && arg.stack && !arg.inspect) {
      pieces.push(arg.stack);
    }
    // Non-strings
    // (miscellaneous arrays, dictionaries, mysterious objects, etc)
    else if (!_.isString(arg)) {
      if (options.inspectOptions) {
        pieces.push(util.inspect(arg, options.inspectOptions));
      }
      else { pieces.push(util.inspect(arg)); }
      return;
    }
    // Strings
    else {
      pieces.push(arg);
    }

  });

  // Compose 'str' of all the arguments
  // (include the appropriate prefix if specified)
  var prefixStr = (options.prefixes && options.prefixes[logAt]) || '';
  var str = prefixStr + util.format.apply(util, pieces);

  // Call log fn
  return logFn.apply(logFn, [str]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.log.verbose"></a>[function <span class="apidocSignatureSpan">sails.log.</span>verbose ()](#apidoc.element.sails.log.verbose)
- description and source-code
```javascript
function _writeLogToConsole() {

  // Check 'options.level' against logAt
  // to see whether to write the log.
  // ( silly = 0 | silent = highest )
  var lvlMap = options.logLevels;
  var configuredLvl = options.level;
  if (lvlMap[logAt] < lvlMap[configuredLvl]) { return; }


  var args = Array.prototype.slice.call(arguments);

  /////////////////////////////////////////////////////////////////
  // For backwards-compatibility:
  // (options.inspect should always be true going forward)
  //
  // Note that prefixes and other options will not work with
  // 'inspect===false'.  New features will also not support
  // inspect:false.
  //
  // If 'options.inspect' is disabled, just call the log fn normally
  if (!options.inspect) {
    return logFn.apply(logFn, args);
  }
  /////////////////////////////////////////////////////////////////

  // For reference on the following impl, see:
  // https://github.com/defunctzombie/node-util/blob/master/util.js#L22

  // Combine the arguments passed into the log fn
  var pieces = [];
  _.each(args, function(arg) {

    // Your everyday JavaScript errors
    if (_.isError(arg) && arg.stack && !arg.inspect) {
      pieces.push(arg.stack);
    }
    // Non-strings
    // (miscellaneous arrays, dictionaries, mysterious objects, etc)
    else if (!_.isString(arg)) {
      if (options.inspectOptions) {
        pieces.push(util.inspect(arg, options.inspectOptions));
      }
      else { pieces.push(util.inspect(arg)); }
      return;
    }
    // Strings
    else {
      pieces.push(arg);
    }

  });

  // Compose 'str' of all the arguments
  // (include the appropriate prefix if specified)
  var prefixStr = (options.prefixes && options.prefixes[logAt]) || '';
  var str = prefixStr + util.format.apply(util, pieces);

  // Call log fn
  return logFn.apply(logFn, [str]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.log.warn"></a>[function <span class="apidocSignatureSpan">sails.log.</span>warn ()](#apidoc.element.sails.log.warn)
- description and source-code
```javascript
function _writeLogToConsole() {

  // Check 'options.level' against logAt
  // to see whether to write the log.
  // ( silly = 0 | silent = highest )
  var lvlMap = options.logLevels;
  var configuredLvl = options.level;
  if (lvlMap[logAt] < lvlMap[configuredLvl]) { return; }


  var args = Array.prototype.slice.call(arguments);

  /////////////////////////////////////////////////////////////////
  // For backwards-compatibility:
  // (options.inspect should always be true going forward)
  //
  // Note that prefixes and other options will not work with
  // 'inspect===false'.  New features will also not support
  // inspect:false.
  //
  // If 'options.inspect' is disabled, just call the log fn normally
  if (!options.inspect) {
    return logFn.apply(logFn, args);
  }
  /////////////////////////////////////////////////////////////////

  // For reference on the following impl, see:
  // https://github.com/defunctzombie/node-util/blob/master/util.js#L22

  // Combine the arguments passed into the log fn
  var pieces = [];
  _.each(args, function(arg) {

    // Your everyday JavaScript errors
    if (_.isError(arg) && arg.stack && !arg.inspect) {
      pieces.push(arg.stack);
    }
    // Non-strings
    // (miscellaneous arrays, dictionaries, mysterious objects, etc)
    else if (!_.isString(arg)) {
      if (options.inspectOptions) {
        pieces.push(util.inspect(arg, options.inspectOptions));
      }
      else { pieces.push(util.inspect(arg)); }
      return;
    }
    // Strings
    else {
      pieces.push(arg);
    }

  });

  // Compose 'str' of all the arguments
  // (include the appropriate prefix if specified)
  var prefixStr = (options.prefixes && options.prefixes[logAt]) || '';
  var str = prefixStr + util.format.apply(util, pieces);

  // Call log fn
  return logFn.apply(logFn, [str]);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sails.router"></a>[module sails.router](#apidoc.module.sails.router)

#### <a name="apidoc.element.sails.router._privateRouter"></a>[function <span class="apidocSignatureSpan">sails.router.</span>_privateRouter (req, res, next)](#apidoc.element.sails.router._privateRouter)
- description and source-code
```javascript
function app(req, res, next){ app.handle(req, res, next); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router.bind"></a>[function <span class="apidocSignatureSpan">sails.router.</span>bind ()](#apidoc.element.sails.router.bind)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router.flush"></a>[function <span class="apidocSignatureSpan">sails.router.</span>flush ()](#apidoc.element.sails.router.flush)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router.load"></a>[function <span class="apidocSignatureSpan">sails.router.</span>load ()](#apidoc.element.sails.router.load)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router.reset"></a>[function <span class="apidocSignatureSpan">sails.router.</span>reset ()](#apidoc.element.sails.router.reset)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router.route"></a>[function <span class="apidocSignatureSpan">sails.router.</span>route ()](#apidoc.element.sails.router.route)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router.unbind"></a>[function <span class="apidocSignatureSpan">sails.router.</span>unbind ()](#apidoc.element.sails.router.unbind)
- description and source-code
```javascript
function wrapper() {
  var fn = (this && this !== root && this instanceof wrapper) ? Ctor : func;
  return fn.apply(thisArg, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sails.router._privateRouter"></a>[module sails.router._privateRouter](#apidoc.module.sails.router._privateRouter)

#### <a name="apidoc.element.sails.router._privateRouter._privateRouter"></a>[function <span class="apidocSignatureSpan">sails.router.</span>_privateRouter (req, res, next)](#apidoc.element.sails.router._privateRouter._privateRouter)
- description and source-code
```javascript
function app(req, res, next){ app.handle(req, res, next); }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.acl"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>acl (path)](#apidoc.element.sails.router._privateRouter.acl)
- description and source-code
```javascript
acl = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.addListener"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>addListener (type, listener)](#apidoc.element.sails.router._privateRouter.addListener)
- description and source-code
```javascript
function addListener(type, listener) {
  return _addListener(this, type, listener, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.all"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>all (path)](#apidoc.element.sails.router._privateRouter.all)
- description and source-code
```javascript
all = function (path){
  var args = arguments;
  methods.forEach(function(method){
    app[method].apply(this, args);
  }, this);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.bind"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>bind (path)](#apidoc.element.sails.router._privateRouter.bind)
- description and source-code
```javascript
bind = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.checkout"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>checkout (path)](#apidoc.element.sails.router._privateRouter.checkout)
- description and source-code
```javascript
checkout = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.configure"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>configure (arg0, arg1)](#apidoc.element.sails.router._privateRouter.configure)
- description and source-code
```javascript
configure = function (arg0, arg1) {
"use strict"
log.call(deprecate, message, site)
return fn.apply(this, arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.connect"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>connect (path)](#apidoc.element.sails.router._privateRouter.connect)
- description and source-code
```javascript
connect = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.copy"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>copy (path)](#apidoc.element.sails.router._privateRouter.copy)
- description and source-code
```javascript
copy = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.defaultConfiguration"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>defaultConfiguration ()](#apidoc.element.sails.router._privateRouter.defaultConfiguration)
- description and source-code
```javascript
defaultConfiguration = function (){
  // default settings
  this.enable('x-powered-by');
  this.set('etag', 'weak');
  var env = process.env.NODE_ENV || 'development';
  this.set('env', env);
  this.set('subdomain offset', 2);
  this.set('trust proxy', false);

  // trust proxy inherit back-compat
  Object.defineProperty(this.settings, trustProxyDefaultSymbol, {
    configurable: true,
    value: true
  });

  debug('booting in %s mode', env);

  // implicit middleware
  this.use(connect.query());
  this.use(middleware.init(this));

  this.on('mount', function onmount(parent) {
    // inherit trust proxy
    if (this.settings[trustProxyDefaultSymbol] === true
      && typeof parent.settings['trust proxy fn'] === 'function') {
      delete this.settings['trust proxy'];
      delete this.settings['trust proxy fn'];
    }

    // inherit protos
    this.request.__proto__ = parent.request;
    this.response.__proto__ = parent.response;
    this.engines.__proto__ = parent.engines;
    this.settings.__proto__ = parent.settings;
  });

  // router
  this._router = new Router(this);
  this.routes = this._router.map;
  this.__defineGetter__('router', function(){
    this._usedRouter = true;
    this._router.caseSensitive = this.enabled('case sensitive routing');
    this._router.strict = this.enabled('strict routing');
    return this._router.middleware;
  });

  // setup locals
  this.locals = locals(this);

  // default locals
  this.locals.settings = this.settings;

  // default configuration
  this.set('view', View);
  this.set('views', process.cwd() + '/views');
  this.set('jsonp callback name', 'callback');

  if (env === 'development') {
    this.set('json spaces', 2);
  }

  if (env === 'production') {
    this.enable('view cache');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.del"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>del (arg0)](#apidoc.element.sails.router._privateRouter.del)
- description and source-code
```javascript
del = function (arg0) {
"use strict"
log.call(deprecate, message, site)
return fn.apply(this, arguments)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.delete"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>delete (path)](#apidoc.element.sails.router._privateRouter.delete)
- description and source-code
```javascript
delete = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.disable"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>disable (setting)](#apidoc.element.sails.router._privateRouter.disable)
- description and source-code
```javascript
disable = function (setting){
  return this.set(setting, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.disabled"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>disabled (setting)](#apidoc.element.sails.router._privateRouter.disabled)
- description and source-code
```javascript
disabled = function (setting){
  return !this.set(setting);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.emit"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>emit (type)](#apidoc.element.sails.router._privateRouter.emit)
- description and source-code
```javascript
function emit(type) {
  var er, handler, len, args, i, events, domain;
  var needDomainExit = false;
  var doError = (type === 'error');

  events = this._events;
  if (events)
    doError = (doError && events.error == null);
  else if (!doError)
    return false;

  domain = this.domain;

  // If there is no 'error' event listener then throw.
  if (doError) {
    er = arguments[1];
    if (domain) {
      if (!er)
        er = new Error('Uncaught, unspecified "error" event');
      er.domainEmitter = this;
      er.domain = domain;
      er.domainThrown = false;
      domain.emit('error', er);
    } else if (er instanceof Error) {
      throw er; // Unhandled 'error' event
    } else {
      // At least give some kind of context to the user
      var err = new Error('Uncaught, unspecified "error" event. (' + er + ')');
      err.context = er;
      throw err;
    }
    return false;
  }

  handler = events[type];

  if (!handler)
    return false;

  if (domain && this !== process) {
    domain.enter();
    needDomainExit = true;
  }

  var isFn = typeof handler === 'function';
  len = arguments.length;
  switch (len) {
    // fast cases
    case 1:
      emitNone(handler, isFn, this);
      break;
    case 2:
      emitOne(handler, isFn, this, arguments[1]);
      break;
    case 3:
      emitTwo(handler, isFn, this, arguments[1], arguments[2]);
      break;
    case 4:
      emitThree(handler, isFn, this, arguments[1], arguments[2], arguments[3]);
      break;
    // slower
    default:
      args = new Array(len - 1);
      for (i = 1; i < len; i++)
        args[i - 1] = arguments[i];
      emitMany(handler, isFn, this, args);
  }

  if (needDomainExit)
    domain.exit();

  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.enable"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>enable (setting)](#apidoc.element.sails.router._privateRouter.enable)
- description and source-code
```javascript
enable = function (setting){
  return this.set(setting, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.enabled"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>enabled (setting)](#apidoc.element.sails.router._privateRouter.enabled)
- description and source-code
```javascript
enabled = function (setting){
  return !!this.set(setting);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.engine"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>engine (ext, fn)](#apidoc.element.sails.router._privateRouter.engine)
- description and source-code
```javascript
engine = function (ext, fn){
  if ('function' != typeof fn) throw new Error('callback function required');
  if ('.' != ext[0]) ext = '.' + ext;
  this.engines[ext] = fn;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.eventNames"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>eventNames ()](#apidoc.element.sails.router._privateRouter.eventNames)
- description and source-code
```javascript
function eventNames() {
  return this._eventsCount > 0 ? Reflect.ownKeys(this._events) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.get"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>get (path)](#apidoc.element.sails.router._privateRouter.get)
- description and source-code
```javascript
get = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.getMaxListeners"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>getMaxListeners ()](#apidoc.element.sails.router._privateRouter.getMaxListeners)
- description and source-code
```javascript
function getMaxListeners() {
  return $getMaxListeners(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.handle"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>handle (req, res, out)](#apidoc.element.sails.router._privateRouter.handle)
- description and source-code
```javascript
handle = function (req, res, out) {
  var stack = this.stack
    , searchIndex = req.url.indexOf('?')
    , pathlength = searchIndex !== -1 ? searchIndex : req.url.length
    , fqdn = req.url[0] !== '/' && 1 + req.url.substr(0, pathlength).indexOf('://')
    , protohost = fqdn ? req.url.substr(0, req.url.indexOf('/', 2 + fqdn)) : ''
    , removed = ''
    , slashAdded = false
    , index = 0;

  // final function handler
  var done = out || finalhandler(req, res, {
    env: env,
    onerror: logerror
  });

  function next(err) {
    var layer, path, c;

    if (slashAdded) {
      req.url = req.url.substr(1);
      slashAdded = false;
    }

    req.url = protohost + removed + req.url.substr(protohost.length);
    req.originalUrl = req.originalUrl || req.url;
    removed = '';

    // next callback
    layer = stack[index++];

    // all done
    if (!layer) {
      defer(done, err);
      return;
    }

    try {
      path = parseUrl(req).pathname;
      if (undefined == path) path = '/';

      // skip this layer if the route doesn't match.
      if (0 != path.toLowerCase().indexOf(layer.route.toLowerCase())) return next(err);

      c = path[layer.route.length];
      if (c && '/' != c && '.' != c) return next(err);

      // Call the layer handler
      // Trim off the part of the url that matches the route
      removed = layer.route;
      req.url = protohost + req.url.substr(protohost.length + removed.length);

      // Ensure leading slash
      if (!fqdn && '/' != req.url[0]) {
        req.url = '/' + req.url;
        slashAdded = true;
      }

      debug('%s %s : %s', layer.handle.name || 'anonymous', layer.route, req.originalUrl);
      var arity = layer.handle.length;
      if (err) {
        if (arity === 4) {
          layer.handle(err, req, res, next);
        } else {
          next(err);
        }
      } else if (arity < 4) {
        layer.handle(req, res, next);
      } else {
        next();
      }
    } catch (e) {
      next(e);
    }
  }
  next();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.head"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>head (path)](#apidoc.element.sails.router._privateRouter.head)
- description and source-code
```javascript
head = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.init"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>init ()](#apidoc.element.sails.router._privateRouter.init)
- description and source-code
```javascript
init = function (){
  this.cache = {};
  this.settings = {};
  this.engines = {};
  this.defaultConfiguration();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.link"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>link (path)](#apidoc.element.sails.router._privateRouter.link)
- description and source-code
```javascript
link = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.listen"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>listen ()](#apidoc.element.sails.router._privateRouter.listen)
- description and source-code
```javascript
listen = function (){
  var server = http.createServer(this);
  return server.listen.apply(server, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.listenerCount"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>listenerCount (type)](#apidoc.element.sails.router._privateRouter.listenerCount)
- description and source-code
```javascript
function listenerCount(type) {
  const events = this._events;

  if (events) {
    const evlistener = events[type];

    if (typeof evlistener === 'function') {
      return 1;
    } else if (evlistener) {
      return evlistener.length;
    }
  }

  return 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.listeners"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>listeners (type)](#apidoc.element.sails.router._privateRouter.listeners)
- description and source-code
```javascript
function listeners(type) {
  var evlistener;
  var ret;
  var events = this._events;

  if (!events)
    ret = [];
  else {
    evlistener = events[type];
    if (!evlistener)
      ret = [];
    else if (typeof evlistener === 'function')
      ret = [evlistener];
    else
      ret = arrayClone(evlistener, evlistener.length);
  }

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.locals"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>locals (obj)](#apidoc.element.sails.router._privateRouter.locals)
- description and source-code
```javascript
function locals(obj){
  for (var key in obj) locals[key] = obj[key];
  return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.lock"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>lock (path)](#apidoc.element.sails.router._privateRouter.lock)
- description and source-code
```javascript
lock = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.m-search"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>m-search (path)](#apidoc.element.sails.router._privateRouter.m-search)
- description and source-code
```javascript
m-search = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.merge"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>merge (path)](#apidoc.element.sails.router._privateRouter.merge)
- description and source-code
```javascript
merge = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.mkactivity"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>mkactivity (path)](#apidoc.element.sails.router._privateRouter.mkactivity)
- description and source-code
```javascript
mkactivity = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.mkcalendar"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>mkcalendar (path)](#apidoc.element.sails.router._privateRouter.mkcalendar)
- description and source-code
```javascript
mkcalendar = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.mkcol"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>mkcol (path)](#apidoc.element.sails.router._privateRouter.mkcol)
- description and source-code
```javascript
mkcol = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.move"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>move (path)](#apidoc.element.sails.router._privateRouter.move)
- description and source-code
```javascript
move = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.notify"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>notify (path)](#apidoc.element.sails.router._privateRouter.notify)
- description and source-code
```javascript
notify = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.on"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>on (type, listener)](#apidoc.element.sails.router._privateRouter.on)
- description and source-code
```javascript
function addListener(type, listener) {
  return _addListener(this, type, listener, false);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.once"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>once (type, listener)](#apidoc.element.sails.router._privateRouter.once)
- description and source-code
```javascript
function once(type, listener) {
  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');
  this.on(type, _onceWrap(this, type, listener));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.options"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>options (path)](#apidoc.element.sails.router._privateRouter.options)
- description and source-code
```javascript
options = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.param"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>param (name, fn)](#apidoc.element.sails.router._privateRouter.param)
- description and source-code
```javascript
param = function (name, fn){
  var self = this
    , fns = [].slice.call(arguments, 1);

  // array
  if (Array.isArray(name)) {
    name.forEach(function(name){
      fns.forEach(function(fn){
        self.param(name, fn);
      });
    });
  // param logic
  } else if ('function' == typeof name) {
    this._router.param(name);
  // single
  } else {
    if (':' == name[0]) name = name.substr(1);
    fns.forEach(function(fn){
      self._router.param(name, fn);
    });
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.patch"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>patch (path)](#apidoc.element.sails.router._privateRouter.patch)
- description and source-code
```javascript
patch = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.path"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>path ()](#apidoc.element.sails.router._privateRouter.path)
- description and source-code
```javascript
path = function (){
  return this.parent
    ? this.parent.path() + this.route
    : '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.post"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>post (path)](#apidoc.element.sails.router._privateRouter.post)
- description and source-code
```javascript
post = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.prependListener"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>prependListener (type, listener)](#apidoc.element.sails.router._privateRouter.prependListener)
- description and source-code
```javascript
function prependListener(type, listener) {
  return _addListener(this, type, listener, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.prependOnceListener"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>prependOnceListener (type, listener)](#apidoc.element.sails.router._privateRouter.prependOnceListener)
- description and source-code
```javascript
function prependOnceListener(type, listener) {
  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');
  this.prependListener(type, _onceWrap(this, type, listener));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.propfind"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>propfind (path)](#apidoc.element.sails.router._privateRouter.propfind)
- description and source-code
```javascript
propfind = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.proppatch"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>proppatch (path)](#apidoc.element.sails.router._privateRouter.proppatch)
- description and source-code
```javascript
proppatch = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.purge"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>purge (path)](#apidoc.element.sails.router._privateRouter.purge)
- description and source-code
```javascript
purge = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.put"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>put (path)](#apidoc.element.sails.router._privateRouter.put)
- description and source-code
```javascript
put = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.rebind"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>rebind (path)](#apidoc.element.sails.router._privateRouter.rebind)
- description and source-code
```javascript
rebind = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.removeAllListeners"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>removeAllListeners (type)](#apidoc.element.sails.router._privateRouter.removeAllListeners)
- description and source-code
```javascript
function removeAllListeners(type) {
  var listeners, events;

  events = this._events;
  if (!events)
    return this;

  // not listening for removeListener, no need to emit
  if (!events.removeListener) {
    if (arguments.length === 0) {
      this._events = new EventHandlers();
      this._eventsCount = 0;
    } else if (events[type]) {
      if (--this._eventsCount === 0)
        this._events = new EventHandlers();
      else
        delete events[type];
    }
    return this;
  }

  // emit removeListener for all listeners on all events
  if (arguments.length === 0) {
    var keys = Object.keys(events);
    for (var i = 0, key; i < keys.length; ++i) {
      key = keys[i];
      if (key === 'removeListener') continue;
      this.removeAllListeners(key);
    }
    this.removeAllListeners('removeListener');
    this._events = new EventHandlers();
    this._eventsCount = 0;
    return this;
  }

  listeners = events[type];

  if (typeof listeners === 'function') {
    this.removeListener(type, listeners);
  } else if (listeners) {
    // LIFO order
    do {
      this.removeListener(type, listeners[listeners.length - 1]);
    } while (listeners[0]);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.removeListener"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>removeListener (type, listener)](#apidoc.element.sails.router._privateRouter.removeListener)
- description and source-code
```javascript
function removeListener(type, listener) {
  var list, events, position, i, originalListener;

  if (typeof listener !== 'function')
    throw new TypeError('"listener" argument must be a function');

  events = this._events;
  if (!events)
    return this;

  list = events[type];
  if (!list)
    return this;

  if (list === listener || list.listener === listener) {
    if (--this._eventsCount === 0)
      this._events = new EventHandlers();
    else {
      delete events[type];
      if (events.removeListener)
        this.emit('removeListener', type, list.listener || listener);
    }
  } else if (typeof list !== 'function') {
    position = -1;

    for (i = list.length; i-- > 0;) {
      if (list[i] === listener || list[i].listener === listener) {
        originalListener = list[i].listener;
        position = i;
        break;
      }
    }

    if (position < 0)
      return this;

    if (list.length === 1) {
      list[0] = undefined;
      if (--this._eventsCount === 0) {
        this._events = new EventHandlers();
        return this;
      } else {
        delete events[type];
      }
    } else {
      spliceOne(list, position);
    }

    if (events.removeListener)
      this.emit('removeListener', type, originalListener || listener);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.render"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>render (name, options, fn)](#apidoc.element.sails.router._privateRouter.render)
- description and source-code
```javascript
render = function (name, options, fn){
  var opts = {}
    , cache = this.cache
    , engines = this.engines
    , view;

  // support callback function as second arg
  if ('function' == typeof options) {
    fn = options, options = {};
  }

  // merge app.locals
  merge(opts, this.locals);

  // merge options._locals
  if (options._locals) {
    merge(opts, options._locals);
  }

  // merge options
  merge(opts, options);

  // set .cache unless explicitly provided
  opts.cache = null == opts.cache
    ? this.enabled('view cache')
    : opts.cache;

  // primed cache
  if (opts.cache) view = cache[name];

  // view
  if (!view) {
    view = new (this.get('view'))(name, {
      defaultEngine: this.get('view engine'),
      root: this.get('views'),
      engines: engines
    });

    if (!view.path) {
      var err = new Error('Failed to lookup view "' + name + '" in views directory "' + view.root + '"');
      err.view = view;
      return fn(err);
    }

    // prime the cache
    if (opts.cache) cache[name] = view;
  }

  // render
  try {
    view.render(opts, fn);
  } catch (err) {
    fn(err);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.report"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>report (path)](#apidoc.element.sails.router._privateRouter.report)
- description and source-code
```javascript
report = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.router"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>router (req, res, next)](#apidoc.element.sails.router._privateRouter.router)
- description and source-code
```javascript
function router(req, res, next){
  self._dispatch(req, res, next);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.search"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>search (path)](#apidoc.element.sails.router._privateRouter.search)
- description and source-code
```javascript
search = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.set"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>set (setting, val)](#apidoc.element.sails.router._privateRouter.set)
- description and source-code
```javascript
set = function (setting, val){
  if (arguments.length === 1) {
    // app.get(setting)
    return this.settings[setting];
  }

  // set value
  this.settings[setting] = val;

  // trigger matched settings
  switch (setting) {
    case 'etag':
      debug('compile etag %s', val);
      this.set('etag fn', compileETag(val));
      break;
    case 'trust proxy':
      debug('compile trust proxy %s', val);
      this.set('trust proxy fn', compileTrust(val));

      // trust proxy inherit back-compat
      Object.defineProperty(this.settings, trustProxyDefaultSymbol, {
        configurable: true,
        value: false
      });

      break;
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.setMaxListeners"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>setMaxListeners (n)](#apidoc.element.sails.router._privateRouter.setMaxListeners)
- description and source-code
```javascript
function setMaxListeners(n) {
  if (typeof n !== 'number' || n < 0 || isNaN(n))
    throw new TypeError('"n" argument must be a positive number');
  this._maxListeners = n;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.subscribe"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>subscribe (path)](#apidoc.element.sails.router._privateRouter.subscribe)
- description and source-code
```javascript
subscribe = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.trace"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>trace (path)](#apidoc.element.sails.router._privateRouter.trace)
- description and source-code
```javascript
trace = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.unbind"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>unbind (path)](#apidoc.element.sails.router._privateRouter.unbind)
- description and source-code
```javascript
unbind = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.unlink"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>unlink (path)](#apidoc.element.sails.router._privateRouter.unlink)
- description and source-code
```javascript
unlink = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.unlock"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>unlock (path)](#apidoc.element.sails.router._privateRouter.unlock)
- description and source-code
```javascript
unlock = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.unsubscribe"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>unsubscribe (path)](#apidoc.element.sails.router._privateRouter.unsubscribe)
- description and source-code
```javascript
unsubscribe = function (path){
  if ('get' == method && 1 == arguments.length) return this.set(path);

  // if no router attached yet, attach the router
  if (!this._usedRouter) this.use(this.router);

  // setup route
  this._router[method].apply(this._router, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router._privateRouter.use"></a>[function <span class="apidocSignatureSpan">sails.router._privateRouter.</span>use (route, fn)](#apidoc.element.sails.router._privateRouter.use)
- description and source-code
```javascript
use = function (route, fn){
  var app;

  // default route to '/'
  if ('string' != typeof route) fn = route, route = '/';

  // express app
  if (fn.handle && fn.set) app = fn;

  // restore .app property on req and res
  if (app) {
    app.route = route;
    fn = function(req, res, next) {
      var orig = req.app;
      app.handle(req, res, function(err){
        req.__proto__ = orig.request;
        res.__proto__ = orig.response;
        next(err);
      });
    };
  }

  connect.proto.use.call(this, route, fn);

  // mounted an app
  if (app) {
    app.parent = this;
    app.emit('mount', this);
  }

  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.sails.router.defaultHandlers"></a>[module sails.router.defaultHandlers](#apidoc.module.sails.router.defaultHandlers)

#### <a name="apidoc.element.sails.router.defaultHandlers.404"></a>[function <span class="apidocSignatureSpan">sails.router.defaultHandlers.</span>404 (req, res)](#apidoc.element.sails.router.defaultHandlers.404)
- description and source-code
```javascript
404 = function (req, res) {

  // Use 'notFound' handler if it exists
  try {
    if (typeof res.notFound === 'function') {
      return res.notFound();
    }
  } catch (e) {}

  // Catch-all:
  // Log a message and try to use 'res.send' to respond.
  try {
    sails.log.verbose('A request (%s) did not match any routes, and no 'res.notFound' handler is configured.', req.url);
    res.send(404);
    return;
  }

  // Serious error occurred-- unable to send response.
  //
  // Note that in the future, we could also emit an 'abort' message on the request object
  // in this case-- then if an attached server is managing this request, it could monitor
  // for 'abort' events and manage its private resources (e.g. TCP sockets) accordingly.
  // However, such contingencies should really handled by the underlying HTTP hook, so
  // this might not actually make sense.
  catch (e) {
    sails.log.error('An unmatched route was encountered in a request...');
    sails.log.error('But no response could be sent because an error occurred:');
    sails.log.error(e);
    return;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.sails.router.defaultHandlers.500"></a>[function <span class="apidocSignatureSpan">sails.router.defaultHandlers.</span>500 (err, req, res)](#apidoc.element.sails.router.defaultHandlers.500)
- description and source-code
```javascript
500 = function (err, req, res) {

  // console.log('* * * FIRED DEFAULT HANDLER (500) * * *');
  // console.log('args:',arguments);
  // console.log('* * * </FIRED_DEFAULT_HANDLER_500> * * *');
  // console.log();

  // First, check for special built-in errors from Express.
  // We don't necessarily want to treat any error that is thrown with
  // a 'status' property of 400 as if it were intentional.  So we also check
  // the error message.  In Express 5, hopefully this can be improved a bit
  // further.
  if (_.isError(err)) {
    var msgMatches = err.message.match(/^Failed to decode param \'([^']+)\'/);
    if (err.status === 400 && msgMatches) {
      sails.log.verbose('Bad request: Could not decode the requested URL ('+req.path+')');
      // Note for future: The problematic URL section is: 'msgMatches[1]'
      return res.send(400, 'Bad request: Could not decode requested URL.');
    }
  }//>-

  // Next, try to use 'res.negotiate()', if it exists and is valid.
  try {

    if (typeof res.negotiate === 'function') {
      return res.negotiate(err);
    }//>-

  } catch (e) { /* ignore any unexpected error encountered when attempting to respond w/ res.negotiate(). */ }

  // Catch-all:
  // Log a message and try to use 'res.send' to respond.
  try {

    sails.log.error('Server Error:');
    sails.log.error(err);
    if (process.env.NODE_ENV === 'production') { return res.send(500); }
    return res.send(500, err);

  } catch (errorSendingResponse) {

    // Serious error occurred-- unable to send response.
    //
    // Note that in the future, we could also emit an 'abort' message on the request object
    // in this case-- then if an attached server is managing this request, it could monitor
    // for 'abort' events and manage its private resources (e.g. TCP sockets) accordingly.
    // However, such contingencies should really handled by the underlying HTTP hook, so
    // this might not actually make sense.
    sails.log.error('But no response could be sent because another error occurred:');
    sails.log.error(errorSendingResponse);

  }//</catch>
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
