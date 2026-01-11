
![MAEL](https://github.com/Yobeco/MAEL_Gen/blob/main/readme_assets/Logo-MAEL-120.png "MAEL project logo")

# MAEL Phonofouille

*An application belonging to the [__MAEL project__](https://github.com/Yobeco/MAEL_Project)*

Copyright (c) 2022 Yonnel Bécognée

[![License: Libre Non Commerciale](https://img.shields.io/badge/license-GNU%20GENERAL%20PUBLIC%20LICENSE%20V3-white.svg)](./LICENSE)

[![Python](https://img.shields.io/badge/Python-V3.10%2B-blue?logo=python&logoColor=yellow)](https://www.python.org/)

[![SQLite](https://img.shields.io/badge/SQLite-V3.50.4%2B-003366?logo=sqlite&logoColor=99CCFF)](https://sqlite.org/)

[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-009900.svg)](#contributing) [![Beginner friendly](https://img.shields.io/badge/Beginner%20friendly-FF8000)]()

[![Status: Active](https://img.shields.io/badge/status-active-009900.svg)]()

## :fr: [Français](https://github.com/Yobeco/MAEL_Phonofouille/blob/main/README.fr.md) | :gb: English

![](https://github.com/Yobeco/MAEL_Phonofouille/blob/main/readme_assets/Logo-MAEL-120.png)

## A- Description :eye:

:computer: **Cross-platform desktop application** (Linux, macOS, and Windows) that allows teachers to find words according to highly useful pedagogical criteria such as:

- The presence and position of a sound within a word,  
- The presence and position of letters,  
- The level of word difficulty,  
- The theme,  
- The grammatical category of the word...

The currently implemented **word databases** <img src="https://cdn.simpleicons.org/sqlite/FFFF" width="24" height="24" style="vertical-align: middle;" /> are:

- [MiniLex](https://github.com/Yobeco/MAEL_Phrases/blob/main/readme_assets/Minima%20_Lexical_C1fev25.pdf) developed by AMLA Nord  
- [Lexique 3.83](http://www.lexique.org/) <img src="https://cdn.simpleicons.org/creativecommons/FFFF" width="24" height="24" style="vertical-align: middle;" /> BY NC *(Very comprehensive! And most importantly: includes __phonetic descriptions__)*

**Phonofouille** is already used as-is by teachers, but its real goal is to be implemented in JavaScript <img src="https://cdn.simpleicons.org/javascript/FFFF" width="24" height="24" style="vertical-align: middle;" /> within **MAEL Phrase** in order to help teachers create custom activities for their students.

---

## B- Features :clipboard:

- Database selection.  
- Difficulty level selection.  
- Selection of sounds that must be present and their position.  
- Selection of letters that must be present and their position.  
- Selection of the number of syllables.  
- Gender selection (if relevant).  
- Theme selection.  
- Button to start the search.  
- Button to copy the entire word list.  
- Double-click on a word to copy it.  
- Right-click on the list to reorganize or delete a row.  
- Navigation menu to browse list pages.

---

## C- How to use MAEL Phonofouille? :blush:

Usage is very straightforward:

1. Choose the database.  
1. Choose the word selection criteria (no specific order).  
1. Launch the search.  
1. Copy the entire list or a single word.

---

## D- Operating principle :gear:

*(To help understand the code)*

The various interface widgets generate a [dictionary-type variable](/readme_assets/parsed_data_V6.pdf) containing the criteria that will be used by **SQLite** <img src="https://cdn.simpleicons.org/sqlite/FFFF" width="24" height="24" style="vertical-align: middle;" /> to perform the search. :mag_right:

---

## E- Features to develop :rocket:

- Addition of images associated with words in the database.  
- Addition of corresponding thumbnails in the Phonofouille search engine interface.

Above all, **MAEL Phonofouille** should be ported to JavaScript <img src="https://cdn.simpleicons.org/javascript/FFFF" width="24" height="24" style="vertical-align: middle;" /> within the [**MAEL Phrases**](https://github.com/Yobeco/MAEL_Phrase) platform interface.

### :+1: Offer your help to carry out this port. :smile:

---

## F- Participate in the MAEL project :open_hands:

:ring_buoy: To **get help** using **MAEL Phonofouille** or to **participate in development** :computer:, write to me here:

### :mailbox_with_mail: ***[mael@lvh.edu.ni](mailto:mael@lvh.edu.ni)***

### :star2: Contributors

Many thanks to everyone who will contribute to this project!

| Avatar | Name | GitHub | Role |
|--------|-----|--------|------|
| [<img src="https://github.com/YoBeco.png" width="50" style="border-radius: 50%;">](https://github.com/YoBeco) | Bécognée Yonnel | [@Yobeco](https://github.com/Yobeco) | Maintainer |
| [<img src="https://github.com/Nail-yk.png" width="50" style="border-radius: 50%;">](https://github.com/Nail-yk) | Padawan | [@Nail-yk](https://github.com/Nail-yk) | Documentation translation |
| ... | ... | ... | Developper |
| ... | ... | ... | Illustrator |