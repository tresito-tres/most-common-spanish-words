# The 5,000 most common Spanish words by dictionary form

The 5,000 most common Spanish words, counted by dictionary form: *comía*, *comemos* and *comer* are one word, *comer*. Each word has its rank and an English meaning; 2,257 of them have an example sentence from a real story or news article, with its credit.

In 393 Spanish texts, the 100 most common words make up a median 56% of the words on the page, the 1,000 most common 79% and the 5,000 most common 94%.

Browse the top 1,000 with meanings and examples: https://learntres.com/articles/most-common-spanish-words/

## The file

`most-common-spanish-words.csv` is UTF-8 CSV. Two lines starting with `#` give the title, license and credits; then a header row and 5,000 rows, most common first.

| Column | What it holds |
| --- | --- |
| `rank` | 1 to 5,000, most common first |
| `word` | the dictionary form |
| `meaning` | a short English meaning |
| `meaning_source` | `wiktionary`: adapted from English Wiktionary, shortened; `tres`: Tres's own |
| `example` | an example sentence using the word, or empty |
| `example_from` | the example's author, title and, for an article, site, license and link |

## How it was counted

The ranks come from how often each dictionary form appears in OpenSubtitles 2018, a large collection of film and TV subtitles (word counts from FrequencyWords by Hermit Dave), so the list leans to everyday spoken Spanish. Every word form is grouped under its dictionary form. The shares above come from the Tres reading app's word counter, run on 393 texts (news, classic stories, encyclopedia articles and stories for learners), names and numbers left out.

## License

CC BY-SA 4.0 (`LICENSE`). Credit it as: The most common Spanish words by dictionary form, Tres (https://learntres.com/articles/most-common-spanish-words/), CC BY-SA 4.0.

Word frequencies: Hermit Dave, [FrequencyWords](https://github.com/hermitdave/FrequencyWords) (OpenSubtitles 2018), [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), grouped by dictionary form by Tres. Some meanings adapted from Wiktionary (English Wiktionary contributors, [wiktionary.org](https://en.wiktionary.org/)), shortened by Tres, CC BY-SA 4.0; the rest are Tres’s own. This list and the CSV are shared under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Examples from public-domain stories and from Global Voices and Wikinoticias articles, credited under each one.

The texts the examples come from are listed in `CREDITS.md`.
