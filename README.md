<div align=center>

# AnimeQuiz

[![NPM](https://img.shields.io/badge/Available%20On-NPM-lightgrey.svg?logo=npm&logoColor=339933&labelColor=white&style=flat-square)](https://npmjs.com/package/anime-quiz)

**AnimeQuiz** is a simple module to generate Anime Quiz with options for answer.

It has over 100 quizzes

</div>

---

## Installation

```sh
npm i anime-quiz

yarn add anime-quiz
```

## Usage Example

### To generate Random quiz

```ts
import { Quiz } from 'anime-quiz' //const { Quiz } = require('anime-quiz')
(() => {
  const { getRandom } = new Quiz()
  console.log(getRandom())
})()
```

## Result

```
{
      id: 84,
      question:
        "What is the name of the stuffed lion in Bleach?",
      options: [
        "Jo",
        "Kon",
        "Chad",
        "Urdiu",
      ],
      answer: "Kon",
}
```

### To generate quiz by id

```ts
import { Quiz } from 'anime-quiz' //const { Quiz } = require('anime-quiz')
(() => {
  const { getQuizById } = new Quiz()
  console.log(getQuizById(34))
})()
```

## Result

```
{
      id: 34,
      question:
        "In the 2011 TV anime series, \"The iDOLM@ster\", what was the name of Iori's stuffed toy bunny?",
      options: ["Usagi", "Bubsy", "Charles", "Kero"],
      answer: "Charles",
}
```
