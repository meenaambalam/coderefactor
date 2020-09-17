# coderefactor

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

Details of the changes performed:
---------------------------------

HTML refactoring:
-----------------

1) Used header, main, aside and footer semantic tags instead of their equivalent div tags.

2) changed span to be an id insteaf of a class.

3) Simplied list items to have same class name instead of having different class names for each list item.

4) fixed the broken header link

5) changed the "main" div tags to have the same name

6) added alt attribute for all the img elements

CSS refactoring:
-----------------

1) changed the reference to symentic tags to match with respecitve html changes

2) changed the class to id references to match with respective html changes

3) changed the id to class references to match witht he respective html changes and removed redundant styling.


## Review

* The URL of the deployed application -  https://meenaambalam.github.io/coderefactor/

* The URL of the GitHub repository - https://github.com/meenaambalam/coderefactor
