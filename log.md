# 100 Days Of Code - Log

### Day 1: 3 January, 2017


**Today's Progress**: Finished my markdown previewer project for the freeCodeCamp Data Visualization Certificate!

**Thoughts:** Working through the Modern React with Redux course this morning really helped me out with this one. Also, it taught me a bunch of ES6! Tomorrow I'll convert my CSS to SASS, upload the project to my website and make a start on the camper leaderboard project.

**Link to work:** [Markdown Previewer App](https://github.com/4xDMG/markdown-previewer)


### Day 2: 4 January, 2017


**Today's Progress**: Learnt a bit of SASS and added it to my Markdown Previewer Project.

**Thoughts:** SASS is pretty cool. Can't wait to use it on a bigger project. Tried to  work out how to deploy my app on to my website but gave up for today.

**Link to work:** [Markdown Previewer App](https://github.com/4xDMG/markdown-previewer)


### Day 3: 5 January, 2017


**Today's Progress**: Deployed Markdown Previewer App but styles are missing. Used create-react-app to make boilerplate for my camper-leaderboard project. Organised what components I will need for leaderboard and started coding them.

**Thoughts:** I think I need to import the css file to get styles working for the Markdown Previewer. I think I have got all the components I need for the leaderboard project and am thinking I should be able to finish it tomorrow.

**Link to work:** [Camper Leaderboard](https://github.com/4xDMG/camper-leaderboard)


### Day 4: 6 January, 2017


**Today's Progress**: Kept working on Camper Leaderboard App.

**Thoughts:** Need to rethink my Camper Leaderboard and work out why I'm getting the bugs I'm getting.

**Link to work:** [Camper Leaderboard](https://github.com/4xDMG/camper-leaderboard)


### Day 5: 8 January, 2017


**Today's Progress**: Did more work on personal portfolio website. Added AJAX contact form from a tutorial.

**Thoughts:** Enjoyed learning a little bit of php and procrastinating on Camper Leaderboard App. Later today I might do a bit more on it.

**Link to work:** [Personal Porfolio](http://www.danieltait.com.au)


### Day 6: 9 January, 2017


**Today's Progress**: Did more work on personal portfolio website. Fixed up all CSS styling issues.

**Thoughts:** Battled with CSS for awhile but managed to get the page to look how I wanted it to look.

**Link to work:** [Personal Porfolio](http://www.danieltait.com.au)


### Day 7: 10 January, 2017


**Today's Progress**: Tried to get my API call working for the camper leaderboard app.

**Thoughts:** Having trouble getting my head around how to do things in ES6. Tried two different methods of making the call and they both didn't work. Will investigate more tomorrow.

**Link to work:** [Camper Leaderboard](https://github.com/4xDMG/camper-leaderboard)


### Day 8: 11 January, 2017


**Today's Progress**: Got API call working and started working on my point_type_selector's functionality.

**Thoughts:** API call was working, I just wasn't referencing the right key in the JSON object. Oops. Started trying to figure out the best way to pass state around the app and where I should put my getData method.

**Link to work:** [Camper Leaderboard](https://github.com/4xDMG/camper-leaderboard)


### Day 9: 12 January, 2017


**Today's Progress**: Worked out how to pass state from App.js to my CamperList component and started work on CamperListItem.

**Thoughts:** Felt good about today. Struggled with how to pass state at the start but got the hang of it after reading some stack overflow. Tomorrow, I'll work on generating my camper_list_items using the .map() method and the PointTypeSelector component.

**Link to work:** [Camper Leaderboard](https://github.com/4xDMG/camper-leaderboard)


### Day 10: 13 January, 2017


**Today's Progress**: Finished CamperListItem component and started doing some basic styling.

**Thoughts:** Another good day. Tomorrow I'll have to stop procrastinating about the PointTypeSelector, finish the styling and update the README.md

**Link to work:** [Camper Leaderboard](https://github.com/4xDMG/camper-leaderboard)


### Day 11: 14 January, 2017


**Today's Progress**: Finished camper leaderboard project and started on recipie box.

**Thoughts:** Achieved all the stuff I set out to do today. Feeling good. Had some trouble working out how to add the SCSS styles to my page after I deployed it on GitHub Pages. Played around with stuff, broke the whole app, cloned it from my repo, played around some more and now it magically works.

**Link to work:** [Camper Leaderboard](https://github.com/4xDMG/camper-leaderboard)


### Day 12: 15 January, 2017


**Today's Progress**: Worked on App and RecipeList components

**Thoughts:** Didn't get alot done today. Having trouble working out why I sometimes get ```Can only update mounted or mouting component``` error when I use ```.setState``` on methods in my class.

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 13: 16 January, 2017


**Today's Progress**: Worked on RecipeList and RecipeListItem components

**Thoughts:** Tried for 10-20 minutes to work out the error from yesterday but gave up temporarily and started moving forward getting the RecipeListItem component working.

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 14: 17 January, 2017


**Today's Progress**: Took a step back and reworked the App and added a new component

**Thoughts:** Gave up on the error for now and decided to focus on making the app fully functional first then I'll worry about local storage and state management when it's all up and running. For some reason my return statement on the IngredientList component isn't being called so the ```<li>``` JSX element isn't displaying.

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 15: 18 January, 2017


**Today's Progress**: Got RecipeList and RecipeListItem components finished for now and got my Add, Edit and Delete buttons ready to work on next time.

**Thoughts:** Hunted around on google trying to find a solution for my ```<li>``` elements not rendering. It seems moving the ```<ul>``` tag to my generateIngredients method fixed it. Happy with today's progress and excited about getting the buttons functioning. Hopefully I will be able to complete this project this week and move onto the Game of Life project!

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 16: 20 January, 2017


**Today's Progress**: Started work on my AddRecipe component.

**Thoughts:** Missed coding yesterday because I went to the BrisJS meetup after work. It was a great night with lots of really smart people. Today I struggled a bit to get a dialog div to display so people could enter new recipes. I think where I went wrong was by trying to get a method inside the component that wasn't the render method to render some jsx. I fixed it by putting the jsx for the dialog in the render method but giving it the class of hidden.

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 17: 21 January, 2017


**Today's Progress**: Continued work on my AddRecipe component.

**Thoughts:** Starting to think I'm going overboard with the amount of componets I'm using after talking to @coymeetsworld on FreeCodeCamps Gitter chat. Tomorrow I might remove some of my button components and just add then to my App class.

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 18: 22 January, 2017


**Today's Progress**: Merged button components into their parent components and worked on EditRecipeForm.

**Thoughts:** Merging components together has made it a lot easier to pass state around. I'll have to be mindful in future of not getting carried away with making everything a component.

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 19: 23 January, 2017


**Today's Progress**: Finished edit recipe form and started working on method in App component to handle the editing of an existing recipe.

**Thoughts:** Hopefully I will be able to finish off the method that edits a recipe and work out any bugs tomorrow which will just leave me with the delete buttons functionality and styling. :)

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 20: 24 January, 2017


**Today's Progress**: Finished edit recipe method and started work on delete recipe method.

**Thoughts:** Achieved my goal from yesterday! Hoping to wrap this project up before the weekend!

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)




### Day 21: 25 January, 2017


**Today's Progress**: Finsihed all features and tried to get localStorage happening.

**Thoughts:** Local storage is confusing me. App won't work when I try and test for localStorage using ```if (localStorage[recipes])```. Get the error recipes is undefined and am thinking to myself well yeah go to the else clause then. Might need some guidance on this one.

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 22: 26 January, 2017


**Today's Progress**: Worked out localStorage issue, set up SCSS and started styling.

**Thoughts:** Forgot the quotes on ```localStorage["recipes"]```. Oops. Feeling good about finishing tomorrow and starting on the Game of Life project :)

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 23: 29 January, 2017


**Today's Progress**: Set up Eslint with React AirBNB rules and started refacoring code to compy with them.

**Thoughts:** Got advice from a fellow camper to use Eslint with airbnb rules to make my code more readable and comply with React conventions. Can't push my code to github using ```git push origin master``` now but don't have time to investigate. Will have to look at it tomorrow.

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 24: 30 January, 2017


**Today's Progress**: Continued refactoring code to comply with React AirBnB rules.

**Thoughts:** Wish I know about linting before I started writing this project. It does make my code look alot nicer though!

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 25: 1 February, 2017


**Today's Progress**: Continued refactoring code to comply with React AirBnB rules.

**Thoughts:** Cleaned up all the low hanging fruit and will now have to battle my way through the bigger mistakes in my RecipeBox.

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)


### Day 26: 4 February, 2017


**Today's Progress**: Reverted RecipeBox project to before I started refactoring and set up boilerplate designed for airbnb rules. Finsihed mario.c program for CS50 course.

**Thoughts:** Had a busy few days so haven't been getting as much done as I would have liked. Tomorrow BrisJS are having another meetup so I probably won't get a chance to code then either.

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box)



### Day 27: 16 February, 2017


**Today's Progress**: Sat and stared blankly at screen while trying to work out how to structure my rebuild of the recipe box project using Redux.

**Thoughts:** After completing a tutorial on React-Redux I thought I had a good handle on how to use Redux. Turns out I was wrong. Will re-assess tomorrow wether or not I need to do more Redux tutorials.

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box-airbnb)



### Day 27: 16 February, 2017


**Today's Progress**: Started working out a little bit (I think) and began work on displaying recipe list using an initial state.

**Thoughts:** Redux is still confusing. I think rebuilding Recipe Box will be a great way to start cementing what I covered in the tutorial into my brain.

**Link to work:** [Recipe Box](https://github.com/4xDMG/recipe-box-airbnb)
