# W2-S2 Practice - HTML Elements

**GitHub repository:** https://github.com/RinLayheang/frontend-practice.git
**Branch:** `practice_01`

## Exercise 1 - A Blog Post
File: `EX1/index.html`

A blog post about my trip to Angkor Wat. It has:
- an `<h1>` title
- two paragraphs with `<p>`
- a link to the Wikipedia page about Angkor Wat
- an `<h2>` "Conclusion" subheading and a final paragraph
- a `mailto:` link to contact me

## Exercise 2 - Relative paths
File: `EX2/EX2 - Relative paths.docx`

| Source page | Destination page | Hyperlink |
|---|---|---|
| action.html | cinema.html | `<a href="../cinema.html">` |
| home.html | songs.html | `<a href="music/songs.html">` |
| help.html | action.html | `<a href="movies/action_movies/action.html">` |
| cinema.html | help.html | `<a href="../help.html">` |
| action.html | home.html | `<a href="../../home.html">` |
| cinema.html | action.html | `<a href="action_movies/action.html">` |
| songs.html | action.html | `<a href="../movies/action_movies/action.html">` |
| action.html | songs.html | `<a href="../../music/songs.html">` |

## Exercise 3 - A Small Website
Files: `EX3/home.html`, `EX3/about.html`, `EX3/server.html`, `EX3/contact.html`

A small website for "SlideSpace", an online slide editor. There are 4 pages (Home, About us,
Our Services, Contact) and you can go from any page to another with the menu at the top.
Every page has the menu, a title, an image, a list and a paragraph. Images are in `EX3/images`.

## Exercise 4 - Product Information
File: `EX4/index.html`

A product catalog table for CADT Shop with a header row and the columns Product Name, Price,
Quantity and In Stock, with 3 products.

Bonus:
- added an extra column with a small image of each product (`EX4/images`)
- styled the table with a `<style>` tag in the `<head>`
