# Web-Design-Challenge

<p>I have some very basic web-design background, so this was a fun challenge to get back into it. Here was my process for putting it all together:</p>
1. I started out with the index.html page and got all my basic components in place - head, navbar, main content section, and a footer (with a link to my github). I used this as my template for all other pages.
2. The navigation took a lot of tweaking to get it looking and acting like I wanted it. I started with the base code for navbar from Bootstrap, and then modified it with the links to the pages that I wanted and the dropdown. I needed to look at the bootstrap gid documentation and some of the flex options in order to get the links over to the right side where I wanted them. Once it all looked right made the adjustments to the nav code for each page to show which link is currently 'active' and then tested to make sure everything worked as expected.
3. Next I began putting in my content. I resized my visuals to make small thumbnails to help the main page load quickly. I adjusted the summary language to fit my data set, and for each plot description I used what I had written for the WeatherPy project.
4. For the comparisons page I used the Bootstrap grid to set up a two row by two column grid. I set up each plot in a box and linked to the page with more info on each one.
5. I used the recommended technique for the data table - using the pandas to_html method to generate my table code (in the csv_to_html notebook). Once I had my html table I used the Bootstrap responsive tables resources to clean up the formatting and display options.
6. Finally I put in place some media queries to make changes as the page is resized. I used 990px as the break point since that's what I used for when the navbar changes to the small-screen format. I adjust the colors on the navbar and the dropdown background.