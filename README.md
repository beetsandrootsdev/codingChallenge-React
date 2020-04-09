# codingChallenge-React

> Welcome to Beets&Roots Coding Challenge!

## Overview

To complete this challenge, you will need to write a simple [React](https://facebook.github.io/react/) based web app, and and deploy your code as if it were going into production, then send us a link to the hosted repository


## The Challenge

You'll need to build a set of React components to render the app. You'll also need to request a JSON feed, filter that data, and use the relevant fields.

Although this is a basic exercise, we'll be looking for **simple, well-designed, performant, and tested code** in the submission.

Please include a `README` with setup instructions, and any tests or other documentation you created as part of your solution.

Also, add the following info to your `README`:

- How did you decide on the technical and architectural choices used as part of your solution?
- Are there any improvements you could make to your submission?
- What would you do differently if you were allocated more time?

## Functional Details

You will need to build the following 3 pages with React:

- A "Home" page
- A "Europe" page
- A "USA" page
- A "Japan" page

Please create components for each part of the page (eg. header, content, footer, etc).

The pages should also be usable on mobile and tablet devices.

You can assume that you do not have to support legacy browsers without features such as `fetch` or `flexbox`.

### "Home" Page

This will be your `index.html` screen.

You will need to display 3 tiles, which link to "USA" page, "Europe" page and Japan page.

### "USA", "Europe" and "Japan" Pages


For each page you will need to fetch this JSON feed [feed/sample.json](https://github.com/vega/vega/blob/master/docs/data/cars.json), then:

- Display the first 20 `entries`
- Where the entry has a `Horsepower` attribute value <= 200
- Sorted by the `Year` attribute value in ascending order

For each page create a search filter based on  `Year` 

You will also need to handle the loading and error states of fetching the JSON feed:

- "Loading" state
- "Error" state 



