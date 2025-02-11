# React Router Dom v6 Catch-All Route Issue

This repository demonstrates a problem with the catch-all route (`/*`) in React Router DOM v6.  The catch-all route is unexpectedly always matching, preventing other routes from being used correctly. The issue occurs when the catch-all route is placed after other, more specific routes.  This example shows the problem and a solution using nested routes.