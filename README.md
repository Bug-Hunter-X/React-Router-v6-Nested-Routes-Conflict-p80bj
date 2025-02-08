# React Router v6 Nested Route Conflict

This repository demonstrates a common issue encountered when using nested routes in React Router v6.  The problem arises from a route conflict where a more specific path unintentionally overlaps with a more general path, preventing correct rendering and potentially leading to unexpected behavior.

## Problem

The `App.js` file shows an example where two routes, `/about` and `/about/*`, conflict. The wildcard route `'/about/*'` is too broad and matches any URL beginning with `/about`.  This causes the `/about` route to be overshadowed and not function as expected. 

## Solution

The `AppSolution.js` file corrects this by removing the overlapping route or adjusting the routes' hierarchy to avoid conflicts. The provided solution ensures correct routing and prevents the issue.