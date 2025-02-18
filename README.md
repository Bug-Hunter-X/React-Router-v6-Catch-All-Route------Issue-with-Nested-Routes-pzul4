# React Router v6 Catch-All Route `/*` Issue

This repository demonstrates a problem with the catch-all route (`/*`) in React Router v6 when used within nested routes. The catch-all route unexpectedly matches even when a more specific route exists.  The solution demonstrates how to properly handle this scenario.

## Problem

The provided `App.js` shows a basic React Router setup. Despite having a more specific route, the catch-all route (`/*`) is always matched, resulting in the '404 Not Found' component always rendering.

## Solution

The solution (`AppSolution.js`) demonstrates how to correctly use the catch-all route only as a final fallback after other routes are evaluated.