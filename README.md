# Cooking Recipes
This web app is used to quickly look throught many food choices and their recipe.

The application also comes with a feature that allows the user to save their favorite meal recipes. The recipes are very straight forward and they are all imported from an API that can be found in [here](https://github.com/public-apis/public-apis).

Here is a quick look at the application.
[devinscookingrecipe](https://devinscookingrecipe.netlify.app/)

<img width="1327" alt="Screen Shot 2021-12-03 at 10 38 34 PM" src="https://user-images.githubusercontent.com/66978846/144695593-f2bc9679-5cb3-4680-a025-e036f0d37c9b.png">


## How to Use
A random recipe will be loaded for the user to look at once they enter the application. To look at a recipe first add it to favorites and then click on it. to remove simply press the X.

The heart ![image](https://user-images.githubusercontent.com/66978846/144542913-ac8726c8-ba8d-4024-9180-85fcf676a7d4.png) means you can favorite a meal and it will save it to the favorites box, and don't worry even if you accidentally refresh the page it will still be there

Click the search icon ![image](https://user-images.githubusercontent.com/66978846/144542606-f2fb1916-2a24-46c1-bd20-b9c09c2a757a.png) if you wish to look at all the recipes.

## Project Goals 
1. To learn how to use APIs and deploy it to a custom website.
2. An API is an application connected to the internet that sends data to the server, we retrieve the data so the users can interact with it. To learn how to utilize APIs with JavaScript click here [JavaScript Fetch API](https://www.javascripttutorial.net/javascript-fetch-api/).
3. Use HTML and CSS to create the contents of the page, and the design of the page.
4. Finally once you validated your HTML and CSS make your source code ready for deployment.
5. To deploy it I used https://www.netlify.com/, it is completely free. First sign up for an account and then
   * Connect to Git provider 
   * Pick a repository 
   * Customize your build options and deploy
6. If everything went accordingly to plan your site should be published and your site should be live ✨

## How to set a custom domain
If you are on netlify, go to your site overview  <img width="120" alt="Screen Shot 2021-12-03 at 10 18 06 PM" src="https://user-images.githubusercontent.com/66978846/144695050-703a5318-45b4-45ad-bdc3-8df73e2a535e.png">  and add a name that is available, ending in the domain .netlify.app.

<img width="703" alt="Screen Shot 2021-12-03 at 10 22 51 PM" src="https://user-images.githubusercontent.com/66978846/144695179-50f026b1-7175-466b-b0f1-193923d78062.png">

To choose a domain ending in .com which is a top-level domain, you would have to pay 16$ each year.

You could also choose to view your deployment logs to see that the configuration files worked by clicking deployment details. This is how it should look like

<img width="1190" alt="Screen Shot 2021-12-03 at 10 50 27 PM" src="https://user-images.githubusercontent.com/66978846/144695873-cec1cbf7-7672-4d04-98e5-fdd222d9bab1.png">
10:34:28 PM: Build ready to start
10:34:30 PM: build-image version: 8925038cf853b22d6397cdcb9904ac88b66bb383 (focal)
10:34:30 PM: build-image tag: v4.5.0
10:34:30 PM: buildbot version: f344a535fc9e872014eaaa404a4e12d2d8b86d78
10:34:30 PM: Fetching cached dependencies
10:34:31 PM: Starting to download cache of 28.7KB
10:34:31 PM: Finished downloading cache in 103.655962ms
10:34:31 PM: Starting to extract cache
10:34:31 PM: Finished extracting cache in 6.717793ms
10:34:31 PM: Finished fetching cache in 110.689748ms
10:34:31 PM: Starting to prepare the repo for build
10:34:31 PM: Preparing Git Reference refs/heads/main
10:34:31 PM: Parsing package.json dependencies
10:34:32 PM: No build steps found, continuing to publishing
10:34:32 PM: Starting to deploy site from '/'
10:34:32 PM: Creating deploy tree 
10:34:32 PM: Creating deploy upload records
10:34:32 PM: 1 new files to upload
10:34:32 PM: 0 new functions to upload
10:34:32 PM: Starting post processing
10:34:32 PM: Post processing - HTML
10:34:33 PM: Post processing - header rules
10:34:33 PM: Post processing - redirect rules
10:34:33 PM: Finished processing build request in 2.240008246s
10:34:33 PM: Post processing done
10:34:33 PM: Site is live ✨
 
