# sample-web-server
テクノロジー（藤原）Node.jsによるサンプルWebサーバ

```
ここに書く
```
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ curl --silent --request GET --url https://api.thecatapi.com/v1/images/search
[{"breeds":[],"categories":[{"id":5,"name":"boxes"}],"id":"5kd","url":"https://cdn2.thecatapi.com/images/5kd.jpg","width":2048,"
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3'
[{"breeds":[],"id":"ck9","url":"https://cdn2.thecatapi.com/images/ck9.jpg","width":500,"height":334},{"breeds":[],"id":"MTY4OTk4OQ","url":"https://cdn2.thecatapi.com/images/MTY4OTk4OQ.jpg","width":640,"height":426},{"breeds":[{"weight":{"imperial":"6 - 14","metric":"3 - 6"},"id":"emau","name":"Egyptian Mau","cfa_url":"http://cfa.org/Breeds/BreedsCJ/EgyptianMau.aspx","vetstreet_url":"http://www.vetstreet.com/cats/egyptian-mau","vcahospitals_url":"https://vcahospitals.com/know-your-pet/cat-breeds/egyptian-mau","temperament":"Agile, Dependent, Gentle, Intelligent, Lively, Loyal, Playful","origin":"Egypt","country_codes":"EG","country_code":"EG","description":"The Egyptian Mau is gentle and reserved. She loves her people and desires attention and affection from them but is wary of others. Early, continuing socialization is essential with this sensitive and sometimes shy cat, especially if you plan to show or travel with her. Otherwise, she can be easily startled by unexpected noises or events.","life_span":"18 - 20","indoor":0,"lap":1,"alt_names":"Pharaoh Cat","adaptability":2,"affection_level":5,"child_friendly":3,"dog_friendly":3,"energy_level":5,"grooming":1,"health_issues":3,"intelligence":4,"shedding_level":3,"social_needs":4,"stranger_friendly":2,"vocalisation":3,"experimental":0,"hairless":0,"natural":1,"rare":0,"rex":0,"suppressed_tail":0,"short_legs":0,"wikipedia_url":"https://en.wikipedia.org/wiki/Egyptian_Mau","hypoallergenic":0}],"id":"BZ59tdOo6","url":"https://cdn2.thecatapi.com/images/BZ59tdOo6.jpg","width":1280,"height":720}]shintabrew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' | jq
-bash: jq: command not found
(23) Failed writing body
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' > thecat.json
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ brew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ brew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ brew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ which jq
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ brew install jp
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ brew link jp
Error: No such keg: /usr/local/Cellar/jp
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ whic jp
-bash: whic: command not found
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ which jq
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ brew install jp
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ brew install jp
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$  cd sample-web-server
-bash: cd: sample-web-server: No such file or directory
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ cd ~/fujiwara
shintaniryouheinoMacBook-Pro:fujiwara shintaniryouhei$ cd sample-web-server
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ brew install jp
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ cd sample-web-server
-bash: cd: sample-web-server: No such file or directory
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ curl --silent --request GET --url https://api.thecatapi.com/v1/images/search
[{"breeds":[],"id":"yZiN5NRA4","url":"https://cdn2.thecatapi.com/images/yZiN5NRA4.jpg","width":220,"height":220}]shintaniryouheinoMacBook-Pro:sample-web-server request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3'
[{"breeds":[],"categories":[{"id":6,"name":"caturday"}],"id":"3b4","url":"https://cdn2.thecatapi.com/images/3b4.jpg","width":640,"height":480},{"breeds":[],"id":"dkd","url":"https://cdn2.thecatapi.com/images/dkd.jpg","width":500,"height":333},{"breeds":[{"weight":{"imperial":"8 - 16","metric":"4 - 7"},"id":"sibe","name":"Siberian","cfa_url":"http://cfa.org/Breeds/BreedsSthruT/Siberian.aspx","vetstreet_url":"http://www.vetstreet.com/cats/siberian","vcahospitals_url":"https://vcahospitals.com/know-your-pet/cat-breeds/siberian","temperament":"Curious, Intelligent, Loyal, Sweet, Agile, Playful, Affectionate","origin":"Russia","country_codes":"RU","country_code":"RU","description":"The Siberians dog like temperament and affection makes the ideal lap cat and will live quite happily indoors. Very agile and powerful, the Siberian cat can easily leap and reach high places, including the tops of refrigerators and even doors. ","life_span":"12 - 15","indoor":0,"lap":1,"alt_names":"Moscow Semi-longhair, HairSiberian Forest Cat","adaptability":5,"affection_level":5,"child_friendly":4,"dog_friendly":5,"energy_level":5,"grooming":2,"health_issues":2,"intelligence":5,"shedding_level":3,"social_needs":4,"stranger_friendly":3,"vocalisation":1,"experimental":0,"hairless":0,"natural":1,"rare":0,"rex":0,"suppressed_tail":0,"short_legs":0,"wikipedia_url":"https://en.wikipedia.org/wiki/Siberian_(cat)","hypoallergenic":1}],"id":"rEcqVVVto","url":"https://cdn2.thecatapi.com/images/rEcqVVVto.jpg","width":1080,"height":1080}]shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ curl --silenrequest GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' | jq
-bash: jq: command not found
(23) Failed writing body
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ brew install jq
Error: The following directories are not writable by your user:
/usr/local/lib/pkgconfig

You should change the ownership of these directories to your user.
  sudo chown -R $(whoami) /usr/local/lib/pkgconfig

And make sure that your user has write permission.
  chmod u+w /usr/local/lib/pkgconfig
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ sudo chown -R $(whoami) /usr/local/lib/pkgconfig
Password:
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ brew install jq
==> Installing dependencies for jq: oniguruma
==> Installing jq dependency: oniguruma
==> Downloading https://homebrew.bintray.com/bottles/oniguruma-6.9.2.mojave.bott
==> Downloading from https://akamai.bintray.com/c6/c613befafe81da48913ebd1a7eb03
######################################################################## 100.0%
==> Pouring oniguruma-6.9.2.mojave.bottle.tar.gz
🍺  /usr/local/Cellar/oniguruma/6.9.2: 17 files, 1.3MB
==> Installing jq
==> Downloading https://homebrew.bintray.com/bottles/jq-1.6.mojave.bottle.1.tar.
==> Downloading from https://akamai.bintray.com/71/71f0e76c5b22e5088426c971d5e79
######################################################################## 100.0%
==> Pouring jq-1.6.mojave.bottle.1.tar.gz
🍺  /usr/local/Cellar/jq/1.6: 18 files, 1MB
==> `brew cleanup` has not been run in 30 days, running now...
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$  curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' | jq
[
  {
    "breeds": [],
    "id": "49u",
    "url": "https://cdn2.thecatapi.com/images/49u.gif",
    "width": 450,
    "height": 272
  },
  {
    "breeds": [],
    "id": "an5",
    "url": "https://cdn2.thecatapi.com/images/an5.jpg",
    "width": 1024,
    "height": 768
  },
  {
    "breeds": [],
    "id": "bkj",
    "url": "https://cdn2.thecatapi.com/images/bkj.jpg",
    "width": 2736,
    "height": 3648
  }
]
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' > thecat.json

shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ 
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' > thecat.json
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ mkdir mywebapi
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ cd mywebapi
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ npm init
-bash: npm: command not found
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ npm init
-bash: npm: command not found
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ npm init
-bash: npm: command not found
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ npm install --save express
-bash: npm: command not found
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ cd sample-web-server
-bash: cd: sample-web-server: No such file or directory
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ cd
shintaniryouheinoMacBook-Pro:~ shintaniryouhei$ cd ~/fujiwara
shintaniryouheinoMacBook-Pro:fujiwara shintaniryouhei$ cd sample-web-server
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ cat ~/.bash_profile
if [ -f ~/.bashrc ]; then
  . ~/.bashrc
fi

# Setting PATH for Python 3.7
# The original version is saved in .bash_profile.pysave
PATH="/Library/Frameworks/Python.framework/Versions/3.7/bin:${PATH}"
export PATH
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ curl -L git.io/nodebrew | perl - setup
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:--     0
  0     0    0     0    0     0      0      0 --:--:--  0:00:02 --:--:--     0
100 24634  100 24634    0     0  10155      0  0:00:02  0:00:02 --:--:-- 10155
Fetching nodebrew...
Installed nodebrew in $HOME/.nodebrew

========================================
Export a path to nodebrew:

export PATH=$HOME/.nodebrew/current/bin:$PATH
========================================
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ export PATH=$HOME/.nodebrew/current/bin:$PATH >> ~/.bashrc
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ source ~/.bashrc
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ nodebrew
nodebrew 1.0.1

Usage:
    nodebrew help                         Show this message
    nodebrew install <version>            Download and install <version> (from binary)
    nodebrew compile <version>            Download and install <version> (from source)
    nodebrew install-binary <version>     Alias of `install` (For backward compatibility)
    nodebrew uninstall <version>          Uninstall <version>
    nodebrew use <version>                Use <version>
    nodebrew list                         List installed versions
    nodebrew ls                           Alias for `list`
    nodebrew ls-remote                    List remote versions
    nodebrew ls-all                       List remote and installed versions
    nodebrew alias <key> <value>          Set alias
    nodebrew unalias <key>                Remove alias
    nodebrew clean <version> | all        Remove source file
    nodebrew selfupdate                   Update nodebrew
    nodebrew migrate-package <version>    Install global NPM packages contained in <version> to current version
    nodebrew exec <version> -- <command>  Execute <command> using specified <version>

Example:
    # install
    nodebrew install v8.9.4

    # use a specific version number
    nodebrew use v8.9.4
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ nodebrew install-binary latest
v12.4.0 is already installed
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ nodebrew ls
v12.4.0

current: v12.4.0
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ nodebrew use latest
use v12.4.0
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ node -v
v12.4.0
shintaniryouheinoMacBook-Pro:sample-web-server shintaniryouhei$ cd mywebapi
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (mywebapi) npm install --save express
Sorry, name can only contain URL-friendly characters.
package name: (mywebapi) 
version: (1.0.0) 
description: 
entry point: (index.js) 
test command: 
git repository: 
keywords: 
author: 
license: (ISC) 
About to write to /Users/shintaniryouhei/Documents/fujiwara/sample-web-server/mywebapi/package.json:

{
  "name": "mywebapi",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
}


Is this OK? (yes) 
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ npm install --save express
npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN mywebapi@1.0.0 No description
npm WARN mywebapi@1.0.0 No repository field.

+ express@4.17.1
added 50 packages from 37 contributors and audited 126 packages in 3.569s
found 0 vulnerabilities

shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ mkdir index.js
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ vi index.js
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ vi index.js
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ vi index.js
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ index.js
-bash: index.js: command not found
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ vi index.js
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ node index.js
Listening on port 3000
^C
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ vi index.js
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ node index.js
Listening on port 3000
^C
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ vi index.js
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ mkdir web
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ cd web
shintaniryouheinoMacBook-Pro:web shintaniryouhei$ vi index.html
shintaniryouheinoMacBook-Pro:web shintaniryouhei$ cd /mywebapi
-bash: cd: /mywebapi: No such file or directory
shintaniryouheinoMacBook-Pro:web shintaniryouhei$ cd ..
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ vi index.js
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ cd web
shintaniryouheinoMacBook-Pro:web shintaniryouhei$ vi index.html
shintaniryouheinoMacBook-Pro:web shintaniryouhei$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/Users/shintaniryouhei/Documents/fujiwara/sample-web-server/mywebapi/web/index.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
shintaniryouheinoMacBook-Pro:web shintaniryouhei$ cd ..
shintaniryouheinoMacBook-Pro:mywebapi shintaniryouhei$ node index.js
Listening on port 3000