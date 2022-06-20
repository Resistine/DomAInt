# GREYCORTEX Research DomAInt

![DomAInt Brain](https://raw.githubusercontent.com/greycortex/DomAInt/rnn/img/brain.png)

GREYCORTEX Research DomAInt is an open extension of Chrome and Firefox browsers, which classifies bad domains without sending your data anywhere. 

It is the first browser add-on based on Artificial Intelligence, created as a toy based on white and black lists of our product Mendel and a 
new platform for sharing cybersecurity information using Artificial Intelligence ThreAInt, which are humorously pre-processed using own alphabets 
and dictionaries and classified by neural networks using TensorFlow.js.

Copyright (C) 2020 GreyCortex s.r.o.
Authors: P3, Sungria, KolouchPetr

## Features

- Get notified when AI model classifies current tab URL as a threat
- View multiple antivirus URL threat scan results using Virustotal API (Work in progress)
- Autoclose dangerous, blacklisted URLs
- Add URLs to whitelist or blacklist

## Options
- Add any or current page to blacklist or whitelist
- Turn off/on URL autoclose
- Redirect to closed site, add it to whitelist (Work in progress)
- Clear items whitelist, blacklist

## Screenshots

### Usage example

![img](https://raw.githubusercontent.com/greycortex/DomAInt/master/img/BrowserExample.png)

### Blacklist and Whitelist usage example

![img](https://raw.githubusercontent.com/greycortex/DomAInt/master/img/ListsExample.png)

## Development 

This extension was created with [Extension CLI](https://oss.mobilefirst.me/extension-cli/)!


### Available Commands

| Commands | Description |
| --- | --- |
| `npm run start` | build extension, watch file changes |
| `npm run build` | generate release version |
| `npm run docs` | generate source code docs |
| `npm run clean` | remove temporary files |
| `npm run test` | run unit tests |
| `npm run sync` | update config files |
| `npm run fix` | fix unsave eval error |

For CLI instructions see [User Guide &rarr;](https://oss.mobilefirst.me/extension-cli/)