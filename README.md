We are using react-pdf which is just a wrapper around PDFjs.
we follow the following documentation :[ https://www.npmjs.com/package/react-pdf ] for integrating the react-pdf in our application. but we are not able to use this package in amex due to  Content Security Policy.

we try to fing out the solution in #one-dev channel in slack 
there response is : 
React-pdf is just a wrapper around PDFjs. Integrating PDFjs in a React application is not trivial. I'd consider:
Exploring whether rendering a PDF inside your application worth the complexity this adds
Looking through other team's implementations.
and
If you have been trying to use this package for a month, maybe it's not the best choice within Amex.
