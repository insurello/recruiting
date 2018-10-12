# Post feedback on timeline

Create an elm app hooked up to app.insurello.se backend [(api)](https://github.com/insurello/app.insurello.se/tree/master/api)
where you can add some feedback to a case. A person should be able to in a form select one of these options about the case:
"Resultatet av ärendet är över mina förväntningar", "Jag är nöjd med resultatet" or "Jag är missnöjd med resultatet".
If the last one is selected, the form should show a textfield where the user has to input a text about why they are
not happy with the result.

This app has to be able to send this request to the back end but does no need to be able to represent any existing
timelines in any way.

## Tips
* Create a new elm file in the elm source root for app.insurello.se repository `app/src/` - this way your app can make
use of all existing functions which we want you to start getting familliar with
* There are a lot of helper functions for creating forms in `app/src/Html/Insurello/`
* Solving this problem involves: schemas, committing events on the changelog, back end and front end.
* Ask for help when needed or write you questions down to get help later
