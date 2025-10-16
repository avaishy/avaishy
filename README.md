We are currently facing challenges integrating the react-pdf library into our React application. This package is essentially a wrapper around PDF.js, and we have been following the official documentation (react-pdf on npm) for implementation.

However, within the Amex environment, we are unable to use this package successfully due to Content Security Policy (CSP) restrictions. Despite multiple attempts over the past month, the integration continues to fail because the underlying PDF.js rendering requires script permissions that are restricted by our CSP configuration.

To find a potential solution, we reached out to the #one-dev Slack channel for guidance. Their response highlighted that:
	•	React-pdf is only a wrapper around PDF.js, and integrating PDF.js directly into a React application is not trivial.
	•	It may be worth reconsidering whether rendering PDFs inside our application justifies the additional complexity.
	•	We should also explore how other internal teams have implemented PDF rendering, or consider alternative approaches.
	•	If this issue has persisted for over a month, react-pdf might not be the most suitable option within the Amex environment.