# solar-sys
#Solar System Animation
This HTML and CSS code creates an animation of a simplified solar system, including the sun, earth, and moon. The sun is displayed as a yellow circle with a white box shadow, while the earth and moon are represented by smaller circles orbiting around the sun.

How to Use
HTML Structure: The HTML structure is as follows:

The outer container with a black background is defined by the container class.
The sun is represented by a div element with the sun class.
The earth and moon are also represented by div elements with the earth and moon classes, respectively.
CSS Styles: The CSS code in the <style> block sets the styles for the elements. It positions the sun at a fixed location, creates circular shapes with border-radius, and applies animations for the earth and moon to simulate their orbits.

Animations: The @keyframes rule defines an animation named orbit, which rotates elements 360 degrees to create a continuous orbit effect.

Issue
If the code is only showing a black background in your browser and not displaying the sun, earth, and moon, here are some troubleshooting steps:

File Structure: Ensure that your HTML file and CSS are in the same directory and correctly named (e.g., index.html for the HTML file and styles.css for the CSS file).

CSS Placement: Make sure the CSS code is either embedded within a <style> block in the <head> section of your HTML document or linked to an external CSS file using the <link> tag in the <head>.

Correct Class Names: Verify that the class names in your HTML (<div class="sun"></div>, <div class="earth">, <div class="moon">) match the class names used in your CSS (.sun, .earth, .moon). Class names are case-sensitive.

Syntax Errors: Check for any syntax errors in your CSS code. Missing semicolons, curly braces, or typos can lead to issues.

Browser Cache: Sometimes, your browser may cache CSS files. Try clearing your browser cache or open the webpage in an incognito/private browsing window to ensure you are seeing the latest changes.

Browser Compatibility: Ensure that your browser supports the CSS properties you are using. CSS properties like box-shadow are supported by modern browsers but might not work in very old versions.

If the issue persists after checking these steps, further debugging may be required to identify the specific problem.
