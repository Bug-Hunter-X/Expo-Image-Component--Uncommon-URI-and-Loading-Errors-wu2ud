# Expo Image Component: Uncommon URI and Loading Errors

This repository demonstrates a common yet often overlooked issue when using Expo's Image component: improper URI handling and image loading failures.  The `bug.js` file showcases how using incorrect URIs or local file paths directly can cause images to fail to load.  The `bugSolution.js` file provides the correct implementation.

This issue can stem from several sources, including:

- Using relative paths to local images incorrectly
- Network connectivity or permission problems with remote images
- Using a faulty URI, or a source that does not exist
- Incorrect file extensions

By reviewing the code and the solution, developers can understand and avoid these pitfalls and ensure seamless image rendering in their Expo applications.