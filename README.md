# Trellorizer

Greasemonkey script for adding background colors to Trello cards. This is helpful for those using Trello for Kanban-esque purposes who want to see, at a glance, the breakdown of the types of cards and what's blocked. The background color of each card is determined by the color of the label applied to that card.

Tested on:

- Chrome, using the Tampermonkey extension

Special cases:

- It takes only 1 label for the background colors and other will be left so that users can still see access them.

Limitations:

- For cards with more than one label last color will win. Other colors will be left as they were.

[Click here](https://github.com/dholovnia/trellorizer/raw/master/trellorizer.user.js) to install.

![Alt text](https://cloud.githubusercontent.com/assets/2066357/15247217/5653a602-191b-11e6-9c1d-c0e087db2830.png "Trello colorizer demo image")
