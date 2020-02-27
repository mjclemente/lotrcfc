# lotrcfc
A CFML wrapper for [The Lord of the Rings API](https://the-one-api.herokuapp.com/documentation).  
One API to rule them all - and this is the wrapper to use them. Just kidding. It's a CFML wrapper for all the Lord of the Rings goodness you need. 

*Feel free to use the issue tracker to report bugs or suggest improvements!*

### Acknowledgements

This project borrows heavily from the API frameworks built by [jcberquist](https://github.com/jcberquist), such as [xero-cfml](https://github.com/jcberquist/xero-cfml) and [aws-cfml](https://github.com/jcberquist/aws-cfml). Because it draws on those projects, it is also licensed under the terms of the MIT license.

## Table of Contents

- [Quick Start](#quick-start)
- [`lotrcfc` Reference Manual](#reference-manual)

## Quick Start
The following is a minimal example of doing something helpful.

```cfc
lotr = new path.to.lotrcfc.lordoftheringsapi( apiKey = 'xxx' );

lotr.listQuotes();
```

## Reference Manual

#### `listBooks()`
List movies.

#### `listMovies()`
List movies.

#### `listQuotes()`
List quotes - there are a *lot* of them.

#### `listCharacters()`
List characters - again, very extensive, with in-depth information.

#### `getBook( required string id )`
Get a book by id. Returns the same information as seen in the list method.

#### `getMovie( required string id )`
Get a movie by id. Returns the same information as seen in the list method.

#### `getQuote( required string id )`
Get a quote by id. Returns the same information as seen in the list method. Includes the ID of the movie and character.

#### `getCharacter( required string id )`
Get a character by id. Returns the same information as seen in the list method.

#### `getChapter( required string id )`
Get a chapter by id. Currently does not include much information.

#### `listChaptersByBook( required string id )`
Lists all chapters in a book. Currently does not include much information.

#### `listQuotesByMovie( required string id )`
Lists all quotes in a movie.

#### `listQuotesByCharacter( required string id )`
Lists all quotes in a character.

---
