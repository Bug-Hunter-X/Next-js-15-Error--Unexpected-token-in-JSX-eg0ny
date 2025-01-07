# Next.js 15 Unexpected Token Error

This repository demonstrates a common error encountered in Next.js 15 applications where a page component returns a plain string instead of JSX.  This leads to an unexpected token error during rendering.

## Problem

In Next.js 15, page components must return valid JSX. Returning a plain string, as shown in `about.js`, results in a runtime error. 

## Solution

The solution is to ensure that all page components return JSX.  This can be done by wrapping the string in a JSX element.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install`.
4. Run `npm run dev`.
5. Visit `/about` in your browser.  You'll see the error.

## How to Fix

Refer to the `aboutSolution.js` for the corrected code.