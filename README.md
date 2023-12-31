
<p align="center">
  <a href="" rel="noopener">
 <img width=100px height=100px src="https://www.baiscopelk.com/wp-content/uploads/2017/02/Logo.png" alt="Baiscope"></a>
</p>


<h2 align="center">Sinhala Subtitle Downloader</h2>




## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Authors](#authors)

## 🧐 About <a name = "about"></a>

The unofficial Scrap <a href="https://baiscopelk.com" > [Baiscopelk.com] </a>

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Installing


```sh
yarn add @sl-code-lords/si-subdl
```

or

```sh
npm i @sl-code-lords/si-subdl
```

## 🎈 Usage <a name="usage"></a>

```ts
var {subsearch , subdl }  = require('@sl-code-lords/si-subdl')

```
## search subtitles 
```ts
await subsearch('avengers')
```


```ts
{
  status: true,
  code_creator: { name: 'Thisal Sanujaya', github: '@sanuwaofficial' },
  results: [
    {
      title: 'Ultimate Avengers II (2006) AKA Ultimate Avengers 2: Rise of the Panther Sinhala Subtitles | පෘථිවියේ බලවත්ම වීරයෝ නැවතත්  [සිංහල උපසිරැසි සමග]',
      link: 'https://www.baiscopelk.com/ultimate-avengers-ii-2006-aka-ultimate-avengers-2-rise-of-the-panther-sinhala-subtitles/'
    },
    {
      title: 'Avengers: Endgame (2019) Sinhala Subtitles | මිතුරුතොමෝ දුක සැප දෙකෙහිම පැවති…[සිංහල උපසිරසි සමඟ] (500)',
      link: 'https://www.baiscopelk.com/avengers-endgame-2019-sinhala-subtitles/'
    },
    {
      title: 'Ultimate Avengers (2006) Sinhala Subtitles | ඇවෙන්ජර් ව්‍යාපෘතියේ මූලාරම්භය [සිංහල උපසිරැසි සමඟ]',
      link: 'https://www.baiscopelk.com/ultimate-avengers-2006-sinhala-subtitles/'
    },
    {
      title: 'Avengers: Infinity War (2018) Sinhala Subtitles | නොවෙන් මෙවන් විපතක් කිසිදා….! [සිංහල උපසිරසි සමඟ] (400*)',
      link: 'https://www.baiscopelk.com/avengers-infinity-war-2018-sinhala-subtitles/'
    },
    {
      title: 'Lego Marvel Super Heroes: Avengers Reassembled (2015) with Sinhala Subtitles  |ඇවෙන්ජර්ස්ලාගේ නැවත එක්වීම [සිංහල උපසිරසි සමඟ]',
      link: 'https://www.baiscopelk.com/lego-marvel-super-heroes-avengers-reassembled-2015-with-sinhala-subtitles/'
    },
    ... 15 more items
  ]
}
```
## download subtitles

```ts
await subdl('https://www.baiscopelk.com/ultimate-avengers-ii-2006-aka-ultimate-avengers-2-rise-of-the-panther-sinhala-subtitles/')
```
```ts
{
  status: true,
  code_creator: { name: 'Thisal Sanujaya', github: '@sanuwaofficial' },
  results: {
    title: 'Ultimate Avengers II (2006) AKA Ultimate Avengers 2: Rise of the Panther Sinhala Subtitles | පෘථිවියේ බලවත්ම වීරයෝ නැවතත් [සිංහල උපසිරැසි සමග] ',
    creater: ' යුරාන් ධනුක',
    img: 'https://www.baiscopelk.com/wp-content/uploads/2019/09/Ultimate-Avengers-II-2006.jpg',
    dl_link: 'https://www.baiscopelk.com/Downloads/ultimate-avengers-ii-2006-zip/?tmstv=1688413330'
  }
}
```

## ✍️ Authors <a name = "authors"></a>

- [@sanuwaofficial](https://github.com/sanuwaofficial) - scraped project author

See also the list of [contributors](https://github.com/SL-CODE-LORDS/si-subdl/contributors) who participated in this project.
