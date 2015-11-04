# material-design-lite-nuget-package
[Material Design Lite (MDL)] (https://github.com/google/material-design-lite) lets you add a Material Design look and feel to your static content websites. It doesn't rely on any JavaScript frameworks or libraries. Optimized for cross-device use, gracefully degrades in older browsers, and offers an experience that is accessible from the get-go.

To install the package, go to package manager console and run the following command -

`PM> Install-Package material-design-lite`

Then you will find all the necessary contents under your project's `Content>mdl-vX.X.X` folder.

Add the following `<link>` and `<script>` elements in your HTML:

    <link rel="stylesheet" href="/Content/mdl-vX.X.X/material.min.css">
    <script src="/Content/mdl-vX.X.X/material.min.js"></script>
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">

