<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/mark-front-night.svg">
    <img src="assets/mark-front-paper.svg" alt="Vector Humanities mark: Leonardo's rhombicuboctahedron from Pacioli's De divina proportione" width="96">
  </picture>
</p>

<h1 align="center"><i>Vector Humanities Editions</i> &amp; <i>Contingencies</i></h1>
<p align="center">Two open series of books from Vector Humanities<br>
<sub><a href="https://vector-humanities.github.io/books/">vector-humanities.github.io/books</a> · series editor David M. Berry, University of Sussex</sub></p>

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/img/title-dark.png">
    <img src="docs/img/title-light.png" alt="The series page: the Vector Humanities mark, VECTOR HUMANITIES in spaced capitals, and the two series names, Vector Humanities Editions and Contingencies, in italic, joined by a red ampersand" width="860">
  </picture>
</p>

Vector Humanities publishes two series of books. **Vector Humanities Editions** publishes translations, made by the [vector translation](https://github.com/vector-humanities/vector-translation) method, of works not yet available in English or not available in full. **Contingencies** publishes new short works commissioned by the series, in the humanities and in or about the vector medium. Each book is taken on case by case.

Every book is free to read and download under the [Creative Commons Attribution 4.0 International licence](https://creativecommons.org/licenses/by/4.0/), and is published with its workings: the decisions log, the build report from [Vector Book](https://github.com/vector-humanities/vector-book), and the records of the faults found and corrected between text and typesetting. A translation is also published with its literal version.

## The series

<p align="center"><img src="docs/img/series.png" alt="The two series side by side, each with the head of its imprint page: the mark, the series name in italic, and VECTOR HUMANITIES in capitals" width="860"></p>

| Series | Publishes | Imprint page |
|---|---|---|
| *Vector Humanities Editions* | Translations by the vector translation method, each naming its source edition, the scans it works from, and their rights status | "This is a vector translation." The Translator's Note describes how AI agents were used and what the translator decided |
| *Contingencies* | New short works commissioned by the series. Authors keep their copyright, grant the series a non-exclusive right to publish, and release the work under CC BY 4.0 | How AI was used is stated in the preface |

## Books in preparation

<table>
<tr>
<td width="50%" align="center" valign="top">
<img src="docs/img/cover-kuki.png" alt="Cover of The Problem of Contingency: author and title above, the Japanese title 偶然性の問題 in a vertical frame below" width="300"><br><br>
<b>Kuki Shūzō</b><br>
<i>The Problem of Contingency</i><br>
偶然性の問題 (Iwanami Shoten, 1935)<br>
translated by David M. Berry<br>
<sub>Vector Humanities Editions · preliminary edition in preparation</sub>
</td>
<td width="50%" align="center" valign="top">
<img src="docs/img/cover-rang.png" alt="Cover of Historical Psychology of Carnival, Florens Christian Rang" width="300"><br><br>
<b>Florens Christian Rang</b><br>
<i>Historical Psychology of Carnival</i><br>
with <i>Faith, Love and Industriousness: A Letter to Walther Rathenau</i><br>
<i>Die Kreatur</i> 2 (1927/28), translated by David M. Berry<br>
<sub>Vector Humanities Editions · pilot</sub>
</td>
</tr>
</table>

Neither book has yet been accepted into the series. Each will receive an ISBN for each format and a DOI for each version as the last steps before release.

<p align="center"><img src="docs/img/books.png" alt="The catalogue entry for The Problem of Contingency on the series page: cover, author, title, original title, translator, description and bibliographic details" width="860"></p>

## From proposal to publication

1. **Proposal.** A book is proposed from what its working folder already holds: the source edition and its rights, the state of the text, the latest build report, an outline and a sample. The series editor accepts, defers or declines it.
2. **Text.** The translation, or the author's final draft, passes its own checks and is signed off as text. An author or translator other than the series editor first signs a short agreement.
3. **Typesetting.** Vector Book sets the book from the same source files. Faults pass between text and typesetting as numbered returns and checks, each answered and closed.
4. **Book gate.** A clean build report, no open returns or checks, and the translator's or author's sign-off. The series then writes the imprint page.
5. **Identifiers.** An ISBN for each format and a DOI for the version are written into the book, which is rebuilt and checked once more.
6. **Publication.** The book and its workings are published, the DOI is registered, and the book is listed on the series page. A correction is published as a new version with its own DOI.

## How the books are kept

<p align="center"><img src="docs/img/conventions.png" alt="The conventions section of the series page, beside the imprint page of The Problem of Contingency" width="860"></p>

| | |
|---|---|
| **Open access** | Every book is free to read and download under CC BY 4.0. A translation of a public-domain text leaves the original in the public domain; the licence covers the translation and its apparatus |
| **Material from elsewhere** | Material that belongs to someone else, such as an image or a long quotation, is outside the licence unless cleared, and is marked as such on the imprint page |
| **AI disclosure** | Machine drafting is identified as such, on the imprint page and in the Translator's Note or preface |
| **Workings** | Decisions on terms, readings and corrections are logged with their dates and published with the book, with its build report and its return and check files |
| **Versions** | Numbered versions, each with its own DOI, and a further DOI that resolves to the latest. Earlier versions remain available |
| **Corrections** | A reported fault is recorded in the book's return files with what was found, where, and what was changed, and is published in a new version |

## This repository

The series page, served by GitHub Pages at [vector-humanities.github.io/books](https://vector-humanities.github.io/books/). It is a single HTML page with no build step: `index.html` and `assets/`. The images in this README are in `docs/img/`.

<p align="center"><img src="docs/img/phone.png" alt="The series page at phone width" width="300"></p>

## Related

- [Vector Humanities](https://vector-humanities.github.io/): the programme
- [Vector Translation](https://github.com/vector-humanities/vector-translation): the translation method
- [Vector Book](https://github.com/vector-humanities/vector-book): book design and typesetting
