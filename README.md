Task:

Reimplement the Twitter.com feed page as close as possible to the real look and feel. This is what a Twitter feed page looks like: http://cl.ly/image/1E06372z3x34. You will need a Twitter account to do this task because you'll be inspecting the structure of the real Twitter feed to understand how it's done.

The goal of this exercise is to test your front-end skills. Don't worry about the backend at all. You are expected to produce only HTML, CSS and JS files. Do not build a Sinatra application. The resulting file should look as close to the real Twitter feed as possible.

Goal 1. Make sure it looks good on the desktop. As a minimum you should have the header and the list of tweets.

Tip: You don't have to use exactly the same CSS techniques as Twitter developers did. For example the home icon in the header is loaded as a sprite but it may be easier to do it using just an ing tag.

Another tip: play with the page a lot before starting coding it. Notice how the header stays in a  fixed position as you scroll the page. Notice that there's no footer because of infinite scrolling.

Goal 2. Add javascript for infinite scrolling (using dummy data, no server-side at all), expanding the tweet input box on focus and, if you're feeling adventurous, a popup to add a new tweet.

Don't forget the infinite scrolling adds a spinner to show that data is being loaded. Even though you'll be using dummy data, emulate the delay.

Goal 3, Make is responsive. Notice that Twitter has very few responsive features other than resizing the search box and hiding the labels in the navigation bar. 

Iterations

Iteration 1

- Fixed Header
-- Icons loaded as a sprite
- List of tweets
-- Dummy data, 30 larks

Iteration 2

- Infinite scrolling 
-- Dummy data, 300 larks
-- Javascript
- Spinner to show the data is being loaded 
-- emulate the delay

Iteration 3

- Responsive 
-- resizing the search box
-- hide the labels in the navigation bar



