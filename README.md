# Web-Design-Challenge
Module 11

Be aware that you must use Bootstrap. This includes using the Bootstrap navbar component for the header on every page, the Bootstrap grid for responsiveness on the comparison page, and the Bootstrap table component for the data page.

Be aware that you must deploy your website to GitHub Pages, and that as a result, the website must work at a live, publicly accessible URL.

Make sure to use a CSS media query that uses Bootstrap and/or @media for the navigation bar.

Make sure that your website works at all window widths.

Feel free to take some liberties with the visual aspects, but keep the core functionality the same as the instructions describe. (For example, keep the comparison visualizations on the comparison page.)

Website Requirements
The overall requirements for your website are as follows:

NOTE
For reference, review the following Screenshots section.

Your website must consist of seven pages.

At the top of every page, your website must have a navigation bar.

Your website must be deployed to GitHub Pages.

Next, we’ll describe these requirements in detail.

Your website must consist of seven pages as follows:

A landing page that contains the following elements:

An explanation of the project.

A link to each visualization page. For these, a sidebar should contain a preview image of each visualization. Clicking an image should take the user to that visualization.

Four visualization pages, stored in the visualizations folder, each with the following elements:

A descriptive title and a heading tag.

The visualization for the selected comparison (latitude vs. max temperature, latitude vs. humidity, latitude vs. cloudiness, or latitude vs. wind speed). The images that these pages display should be stored in the assets/images folder.

A paragraph describing the visualization and its significance.

A comparisons page that does the following:

Contains all the visualizations on the same page so that people can easily compare them.

Uses a Bootstrap grid for the visualizations. This grid must contain two visualizations across a medium or large screen and one visualization across an extra-small or small screen.

A data page that displays a responsive table containing the data that the visualizations use, as follows:

The table must be a Bootstrap table component.

HINT
The data must come from either exporting or converting the CSV file to HTML. To do so, try using a tool that you already know: Pandas. Pandas has a to_html method that generates an HTML table from a Pandas DataFrame. To learn more, see pandas.DataFrame.to_htmlLinks to an external site. in the official Pandas documentation.

Note: Whether you use your own CSV file or the one provided, you should also upload the CSV file you used with your submission. This way your data page can be compared with the CSV file by your grader.

At the top of every page, your website must have a navigation bar that does the following:

Contains the name of the site on the left side of the navigation bar, allowing users to return to the landing page from any page.

Contains a drop-down menu, named Plots, on the right side of the navigation bar that contains a link to each visualization page.

Provides two more text links on the right side: Comparisons, which links to the comparisons page, and Data, which links to the data page.

Is responsive (via media queries). Note that the navigation bar must resemble the one in the screenshots in the Navigation Bar section. In particular, notice the background color change.

Your website must be deployed to GitHub Pages:

As a result, the website must work at a live, publicly accessible URL. Save this URL for your later submission.
Bonus
For extra challenges (but no additional points), you may wish to try any or all of the following:

Use the same requirements but a different dataset to make it your own.

Use the same requirements, but add a Bootstrap theme to customize your website. To do so, you can use a tool like BootswatchLinks to an external site..

Add extra visualizations.

Use meaningful glyphicons next to the links in the navigation bar.

On every visualization page that has an active state, add visualization navigation, as shown in the following images in the Screenshots section.

Screenshots
This section contains screenshots of each page, at various screen widths, that you must create. Keep in mind that these screenshots are intended as a guide. You can meet the requirements without exactly matching your pages to the screenshots.

