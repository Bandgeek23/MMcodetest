Description:

For JavaScript:
To pull API and display data:
I utilized the fetch functionality in JavaScript to pull both the select user information and did a secondary fetch to pull the specific titles and bodies per user.

IDs in HTML allowed me to place the specific user information in the specified areas on the page. For the second fetch, since I wasn’t pulling just one title and body and needed all of them on the page, I created nodes to place them in the html.

To display the API data, I created the consts of getUsers and getPosts, which surrounded the specific fetch, and used displayUsers and displayPosts to remove the child item.

For search feature:

To make sure I could pull specific users in the search, I broke up the url using consts and using the routes available in the API to have the search query number correspond to the correct user and that users’ posts.

I also used eventListeners to make the JavaScript pull the search query.

For HTML:

I added some meta data to display some SEO information as well as to allow the page to be mobile friendly. I used IDs throughout the HTML to link to either the CSS or the JavaScript to display the API data.

For CSS:

I kept the CSS fairly minimal as I spent most time on the JavaScript, but added a little to make search button readable and usable and to format the results a little more clearly. I also tried to use percentages and rems where I could for sizing, but did use px sizing for readability.


Time it took to complete: Close to 7 hours

Other info: Initially, my plan was to use a Promise.all to get the API, but was having troubles displaying just select user info, so I just used to fetches. 
