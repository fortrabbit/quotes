# Fabulous developer quotes

This is a collection of quotes for developers. Motivation about the things that really matter in life: Bugs, release cycles and launch dates. It includes a collection of a few hundred quotes with author, just look at the `quotes.json`.

## How to use it

Do what ever you want with it. Use at own risk. Due to our background quotes are PHPish. Sources have not been researched. We have included this as a subtree in our Dashboard and we print a different quote each day on our Dashboard.

## Examples

> On the Internet, nobody knows you’re a dog.

Peter Steiner

---

> One man’s constant is another man’s variable.

Alan J. Perlis

---

> Code never lies, comments sometimes do.

Ron Jeffries



## Build JSON from PHP

`php -r 'echo json_encode(include("quotes.php"), JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);' > quotes.json`