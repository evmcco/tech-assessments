# Support Engineer Challenge

Welcome! If you are reading this, it's likely because you want to work with us. If you have already applied, then continue on. If not, check out our [careers](https://newstorycharity.org/careers/) page to see our available openings. No software developer opening? Email us anyway!

# Instructions

The goal of this coding challenge is to allow us to see how you approach a technical problem. This challenge is geared more towards a junior or entry level coding ability, specifically with experience in React.

This should take about **2-3 hours** to complete, but please don't spend more than 5 hours on it. If you get to that point, it's likely that this current role might not be a good fit.

Upon completion, a **public** Github URL should be sent to the following:

- [tim@newstorycharity.org](mailto:tim@newstorycharity.org)

> Pro Tip. Read this doc in it's entirety BEFORE you do anything. One of the main things we'll be looking for is someone who can follow directions well.

## The Challenge

You'll be creating a React application that interacts with the XKCD API. 

If you've never heard of XKCD before, it's a fun web comic. You can check it out here - [XKCD Website](https://xkcd.com).

Their website API does not support CORS, so we've built out a proxy for you that can be found here - [XKCD PROXY](https://xkcd.now.sh/). There you will also find the documentation that you need for the API calls you will be making.

The goals are:

1. Create a React Application
2. Create a Home Page that displays the latest comic
3. Create a Search Page that allows you to search & load a specific comic
4. Follow all directions outlined below

## Pre-Requisites

To ensure this runs properly, make sure the following are installed.

- [Git](https://git-scm.com/)
- [Yarn](https://yarnpkg.com/lang/en/)

You'll also need a code editor and terminal, but you know that drill!

## Requirements

First, head over to the [API website](https://xkcd.now.sh/) to get started. Feel free to make some test requests there to get a feeling for how the data will work.

Second, start on your project.

1. Clone this repo. Please use this for your project.
2. Remove the current `git` configuration, and re-init yourself.
    - `rm -rf .git`
    - `git init`
3. Add & Commit your first `Initial Commit` to your own repository
4. Set up the Project
    - We used [Create React App](https://create-react-app.dev/) to set it up.
    - We stripped it down a bit to keep things simpler.
    - You can read their documentation, but here are the basics:
      - To Setup: `yarn install`
      - To Run: `yarn start`
      - Open up [http://localhost:3006](http://localhost:3006) to view the app.
    - All of your programming will be done in the `./src` directory
      - You shouldn't have to edit anything else.
5. Create two pages/components/containers in the app
    - HINT: You'll need some sort of router
    - The URLs should be `http://localhost:3006` and `http://localhost:3006/search`
6. Build out the Home Page
    - The home page should display the latest comic upon load.
7. Build out the Search Page
    - Upon load, the search page just displays an input field
    - When you add a value (1 - 2219) and submit, the corresponding comic will be displayed

# Element Classes

As you build the project, pay close attention to our CSS class name requirements. This will help ensure your app passes our automated tests. It will also allow us to see how well you follow instructions.

## Home Page

There should be a navigation with 2 links, a "Latest" and a "Search" button/link.

> Review the mockup here: [Home Page](https://i.imgur.com/xmzgCzf.png)

#### Classes

- The "Latest" link should have a class of `latest` on the clickable button.
- The "Search" link should have a class of `search` on the clickable button.
- Lastly, the image that will be displayed should have a class of `latestImage` on it.

## Search Page

The navigation will be identical to that on the "Home Page".

> Review the mockup here: [Search Page](https://i.imgur.com/oHvZup1.png)

#### Classes

- The search input should have a class of `searchInput` on the input itself.
- The search button should have a class of `searchSubmit` on the input itself.
- Lastly, the image that will be displayed should have a class of `searchImage` on it.

## Images

All images should have both `title` and `alt` text on them.

- The `alt` text should be pulled from the "title" field in the API response.
- The `title` text should be pulled from the "alt" field in the API response.

_(yes, we know it sounds reversed, but trust us)_

# Working Example

Feel free to take any liberties you'd like with design, but PLEASE NOTE the classes listed above for the elements.

Feel free to have fun, implement your own styles and make it feel like your own.

To help, here is a fully [working example](https://i.imgur.com/0dXELKX.gif).

# Bonus

There is a lot of other data available in the API response, such as "year", "month", "num", etc. Feel free to take that data and show it somewhere on the page.

This isn't required, but feel free to go beyond the requirements. 


