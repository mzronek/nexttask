# Chat Bot

Implement a chat bot as a ***next.js*** web application using the [flow.json](flow.json) file as input data. You can put more or less effort into certain features to show your interests and strengths. Some features can be rudimentary, but every feature should be implemented in the end.

## Features

- [x] Load the [chat bot data](flow.json) asynchronously
- [x] The chat bot flow starts with question id 100
- [x] Use the chosen option‘s nextId to guide the user through the dynamic flow
- [x] All previously entered answers need to be displayed
- [x] If the nextId is false, the flow is terminated and the following message is shown: „Herzlichen Dank für Ihre Angaben“
- [x] Finally the answers are sent combined as a PUT request to [this endpoint](https://virtserver.swaggerhub.com/L8475/task/1.0.1/conversation) (see [OpenAPI specification](https://app.swaggerhub.com/apis-docs/L8475/task/1.0.1) for details)

## Tools & Technology Stack

*   Visual Studio Code
*   Git
*   Typescript 5+ (Strict Mode)
*   React 18+

## Target

ECMAScript 2022+

## Browser compatibility

Latest 3 versions of:

*	Firefox
*	Chrome/Edge
*	Safari

## Delivery

One of the following delivery methods so we can review your code:

*	Git repository + local npm/pnpm/yarn dev/start to run a dev/production build
*	Git repository + VS Code Dev Container
*	Docker via Docker Hub

Good luck and have fun!