node-adam
=========

> "And Adam gave names to all cattle, and to the fowl of the air, and to every beast of the field;" Genesis 2:20a

A node.js name generator.

##Installation

```
$ npm install adam
```

##Usage

```javascript
var adam = require('adam'),
  name1 = adam.name(),       // name1 is now a single word, for example: "fox"
  name2 = adam.name(2),      // name2 is now two words combined: "toadbird"
  name3 = adam.name(3, '-'); // name3 is now three words separated by -: "owl-hen-cow"
```

##Methods

###name( [count=1], [delimeter=''] )

Generate a word, or words, separated by `delimeter`. Each word will be unique, until the word list is exhausted.
There are ~45K words in the list, see `lib/words.js`.

##License

###Word List

See `aaREADME.txt` for information about the word lists used in this module, which are modified versions of the
files found in http://www.gutenberg.org/ebooks/3201.

###Source Code

Copyright 2013 David Humphrey <david.humphrey@senecacollege.ca>

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
