# Smokeball JavaScript Developer Test

## Overview
This repository contains my solution for the Smokeball JavaScript coding challenge.  
The task was to implement the `getArnieQuotes(urls)` function in `src/get-arnie-quotes.js`.

## How it works
- Uses the provided `httpGet` mock function.
- Maps each URL to a result object:
    - `{ "Arnie Quote": <message> }` when status is 200.
    - `{ "FAILURE": <message> }` otherwise.
- Runs requests in parallel using `Promise.all`.

## How to run
```bash
npm install
npm test
