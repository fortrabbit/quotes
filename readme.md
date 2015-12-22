See all the quotes here in the gh-pages branch: http://fortrabbit.github.io/quotes/

# Quotes for developers

People like the quote of the day in our Dashboard. So this is all of them. This is our list of hand-collected quotes for developers. Motivation about the things that really matter in life: Bugs, release cycles and launch dates. It includes a collection of a few hundred quotes with author. Source is the `quotes.json`.

## How to contribute

Fork repo, add changes, pull-request. Please update both: json & php file.

## How to build JSON from PHP

`php -r 'echo json_encode(include("quotes.php"), JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);' > quotes.json`

## TODO

* Make the gh-pages branch use the master source of the JSON file
* Make gh-pages perform better

## License

WTFPL
