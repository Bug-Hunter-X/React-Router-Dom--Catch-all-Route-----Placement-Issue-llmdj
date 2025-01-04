# React Router Dom: Catch-all Route '*' Placement Issue

This repository demonstrates a common error in React Router Dom v6 related to the placement of the catch-all route (`*`). When the catch-all route is not placed last within the `<Routes>`, it can prevent other routes from matching correctly.  This leads to unexpected 404 errors.

The `App.js` file contains the buggy code.  The solution is shown in `AppSolution.js`.