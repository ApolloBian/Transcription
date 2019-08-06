[![Build Status](https://travis-ci.org/ApolloBian/Transcription.svg?branch=master)](https://travis-ci.org/ApolloBian/Transcription)

This repo is dedicated to my girlfriend :heart:, in order to help her practice typing :D.

## Install
##### manually
```
git clone https://github.com/ApolloBian/Transcription.git
cd Transcription
npm install .
node app.js
```

## Roadmap
 - [x] support `^H` for deletion
 - [x] prompt for key position
 - [ ] wrap long lines
 - [ ] add coding mode to enhance copying source code:
    - support auto indention


## Dependecies
- [node.js](https://github.com/nodejs/node) >= 6.4.0
- ... That's it!

## Usage
To get started, copy & past the following line to start a two-minute practice:
```
node app.js -t 120 -i ./data/gre600_filtered.txt
```

##### Options:
- `-h, --help` Show help
- `-t, --time` Given time in seconds to complete the test
- `-i, --input` Path to a wordlist file with new line separated words
- `-V, --verbose` Show settings on start
- `-s, --save` Path to file for saving results

##### Saving results

When called with the `-s, --save` option, results will be written to a file at the given path. Results are appended to the end of a tab-separated file so you can track your progress over time.

## Wordlists
You can use any text files as wordlist.
