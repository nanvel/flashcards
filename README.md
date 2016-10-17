# Flash Cards JS template

See [flashcardsjs](https://github.com/nanvel/flashcardsjs).

An example: [Learn japanese kana](https://nanvel.github.io/kanalearn/).

## How to create your own flashcards app

Clone this repository:
```bash
git clone https://github.com/nanvel/flashcards.git
cd flashcards
```

Update `index.html`, set a questions list, for example:
```csv
あ,a
a,あ
い,i
i,い
```

You can put it inside the `questions` div:
```html
<div id="questions" style="display: none">
あ,a
a,あ
い,i
i,い
</div>
```
or in a separate file:
```html
<div id="questions" data-url="questions.csv" style="display: none"></div>
```

Create a `gh-pages` branch:
```bash
git commit
git push origin master
git branch gh-pages
git checkout gh-pages
git push origin gh-pages
```

Open the app on GitHub pages:
```
open https://<username>.github.io/flashcards/
```
