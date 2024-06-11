# Magnum Intro Bot
Your task is to create a simple Telegram Bot, that would send user the summary of [Wikipedia](https://en.wikipedia.org/) page.

# Example
__Input-message:__
```
New York
```
__Output-message:__
```
New York
New York is a state in the Northeastern region of the United States. New York is the 27th-most exten..
```
# Requirements
1. Output message should start with the full name of the article, with a hyperlink attached to it (wikipedia url).
2. Bot should have a command __/help__ that will send usage information.
3. Bot should do checks on input and inform user if the input is not text (for example, if user sends audio message, or image).
4. Bot should handle the case if no article was found gracefully.

# Extra tasks
- If article have some images, attach image to bot message.
- Dynamic menu with options, if there are multiple articles present for a particular search term.
- If some words in summary are hyperlinks, make them clickable in the message.
- Let user to pick their prefered language, change it. Article summury should be sent in this language.


# Project Requirements
1. No credentials/secret should be leaked.
3. __At least one__ of extra task should be present in the solution, but more is better.
4. Solution should be presented as a __pull request__ to this repo.
5. Solution should contain README.md with description (__concise__). Contents of this file may be discarded.

# Good luck!
