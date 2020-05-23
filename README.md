## Introduction

The code in this repository contains 2 approaches to fetch the JSON data from GitHub users API and render that data inside a React component.

## Approach 1

- Fetch, a Web API available in browsers to fetch network resources.

## Approach 2
- Axios, a `Promise` based `npm` library for browser and node.js.

## How to Run
To run this project on your machine, open your terminal and follow these steps to get the app running.

- Fork this repository by clicking on the Fork button in your GitHub account
- Clone the repo on your machine. Use your own github username in the placeholder below.
    ```sh
    git clone git@github.com:<your-github-username>/access-external-api-react.git
    ```

- Install dependencies
    ```sh
    yarn install
    ```

- Start the app
    ```sh
    yarn start
    ```
- Go to your `src/App.js`. Inside `useEffect()` hook, there are 2 functions     `getGitHubUserWithFetch()` and `getGiHubUserWithAxios()`. Feel free to play with any of these functions, they use `fetch()` and `axios` to get data from the network and render into the React component.
