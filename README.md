# Next.js 15 - Missing return statement in functional component

This repository demonstrates a common error in Next.js 15 applications: forgetting to include a `return` statement in a functional component.  This issue can lead to unexpected behavior or runtime errors.

## Bug Description

When a functional component in the `pages` directory lacks a `return` statement, Next.js 15 may not handle it gracefully, leading to errors. This is especially problematic in applications relying on automatic component hydration.

## Solution

Always ensure that functional components include a `return` statement that specifies the JSX or HTML to be rendered.  The `return` statement must enclose the elements to be rendered by the component.

## Setup

1. Clone the repo
2. Run `npm install`
3. Run `npm run dev`

This will demonstrate the error and the fix.