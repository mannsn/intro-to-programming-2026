### Get organized and write some code!
- [ ] In your GitHub repository, if you have not yet merged your pull request from last week, merge your open lesson-10 pull request by going to the "Pull Requests" tab of your repository. Click on your open pull request, then click on the green 'Merge Pull Request" and confirm the merge. This will update your main branch with the work you did on your lesson-10 branch.
- [ ] Open your code editor and, in the terminal, make sure you're on your main branch. If you're still on your lesson-10 branch, you can switch to your main branch by using the git command `git checkout main`.
- [ ] Update your local main branch to include your lesson-10 work by pulling your changes from your GitHub repository main. Use the following git command in your terminal to do this: `git pull origin main`
- [ ] Still in your terminal, create a new local branch to keep track of just the work you'll do for this assignment by running `git checkout -b lesson-11` in the terminal. Doing this also copies the lesson-10 work you merged to main and pulled to your local machine so now all your branches should be identical on your local machine.

### Assignment: Task List / Deliverables


## Open API Project begins

<details>
<summary> Click here to expand your Open API Project assignment instructions </summary>
<br>
An "open source" means that the source code of something is freely available and can be redistributed and modified.  We have identified several options of open source APIs that allow you to use their data without paying for access to that data.  Use one of the following open source APIs to create a site that accesses a minimum of 2 data points. (Example: if using Open-Meteo, the weather API, you could display (1) the temperature and (2) the weather condition).  Take a look at the options below and decide which one(s) interest you the most.
**NOTE:** You have from now until the end of class to have your Open API Project meeting the requirements.  Think about what you want to build and how you want your site to look and then break the work into parts to pace yourself.

### Open Source API options:
 
* [Open-Meteo](https://open-meteo.com/) – a weather API
* [Swapi.Tech](https://www.swapi.tech/) – an API about Star Wars films
* [Marvel](https://developer.marvel.com/) – an API about the Marvel fandom
* [ARTIC](https://api.artic.edu/docs/#introduction) – an art API from the Art Institute of Chicago
* [TheDogAPI](https://thedogapi.com/) or the [TheCatAPI](https://thecatapi.com/) – APIs about (you guessed it!) Dogs or Cats
* [Soccer](https://api-sports.io/documentation/football/v3) - for all the Soccer lovers out there
* DEPRECATED, certificate expired - [SampleAPIs](https://sampleapis.com/api-list/coffee) – an API for coffee lovers

This week, just focus on accomplishing the following:
 - [ ] Familiarize yourself with the documentation of whichever API you decide to use
 - [ ] Create a new repository in GitHub specifically for your open API project and connect it to your local machine (you can look back at lesson 7 coding assignment instructions to refresh your memory if needed)

⚠️ **_NOTE:_** Be sure you are NOT in your portfolio folder when you clone your repository! Doing this will create a sub-repository which is a complicated problem to resolve. ⚠️ 

 - [ ] Create your basics (index.html, index.js, index.css) but don't go too in depth with any of them yet; just be sure your pages link correctly to each other
 - [ ] Repeat the portfolio part of the assignment above for this project to be sure that your fetch is working and that you're getting a response.  You don't need to display any of it yet, but you should at least be able to console.log the response so you can see what data you get back.  
 - [ ] Put a link to your Open API project repository in the readme.md file of your Portfolio project so your reviewer can easily find/look at your Open API project from your portfolio project.  You can add a link to your read me by using the following syntax:
`[My Open API Project](https://github.com/yourUsernameHere/yourname-open-api)` Put the words you want the link to be in hard brackets `[ ]` and the link to the repository in parentheses `( )` 

**_By the end of this assignment, you should have started on your Open API Project (create a repository, built your basics, and wrote the code for your API fetch to test what response you get back.  You should also see your Open API Project listed on your portfolio by the end of this part of the assignment._**
</details>


### Back up to the cloud
Once you've made the above changes to your html file, follow the below instructions to push a copy from your local machine like you did at the end of last assignment. Make sure your code gets copied to GitHub by adding changes to staging, committing the staged changes, and pushing them from your local machine to GitHub:

- [ ] Check the status of the changes you just made (creating a js folder and the index.js file within, linking the index.js to your html file) by running git status in your terminal
- [ ] Stage all your changes for commit by running `git add .` in your terminal
- [ ] Run `git status` again to see how things have changed. You should get a response indicating changes staged for commit.
- [ ] Create a commit message for reference. You can use a different message if you wish. Run `git commit -m "js added, created footer and skills"`
- [ ] Push these changes to your GitHub repository from your local computer by running `git push`

### Submit Assignment
Now let's make sure that lesson branch will be reviewed.

- [ ] Go to your GitHub repository page in your web browser now, and you should see a "lesson-11 has a recent push" notice with a green "Compare & pull request" button. Click that button
- [ ] Feel free to put notes to yourself or notes for your reviewer in the description (be sure you're including any questions to your reviewer in your assignment submission form though!) and click the green "Create pull request" button.
- [ ] Copy the address of your pull request page (should look like https://github.com/yourUsername/name-classname/pull/6) and paste it into your assignment submission form.

## What next?
   - If you are ready to start on the next lesson and have not gotten your review comments back yet, you can go ahead and merge your pull request and continue working.
   - if you are unsure about your work this week, schedule a 1:1 session with a mentor and review your work together before merging.
