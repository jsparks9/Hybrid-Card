# Full-Stack Flashcards
## _App for learning common interview questions_

### Summary and Motivation
In comparison to other platforms, this app has customizations making it ideal for learning commonly-asked interview questions. This app is lightweight, aesthetic, customized, and specific to our technologies. 

### Deployed App Link
<div>
<a href="https://jsparks9.github.io/Hybrid-Card/build/index" target="_blank">https://jsparks9.github.io/Hybrid-Card/build/index (opens in new tab)</a>
</div>

### Screenshots
![React Deck](https://raw.githubusercontent.com/jsparks9/Hybrid-Card/main/imgs/sc1.png)
![Spring Deck](https://raw.githubusercontent.com/jsparks9/Hybrid-Card/main/imgs/sc2.png)


### Features
- Renders HTML tables, lists, and images as a part of the questions and answers
- Allows for multiple decks to be selected
- Randomly selects the next card from the selected decks
- Each deck has a memory that prevents selection of recent cards
- Hides answer before displaying next question
- On page load, randomly sets the deck selection
- @Media CSS enables mobile-friendly rendering

### Design Alternatives and Potential Issues

- There's a lot of room for change in terms of how cards are remembered and randomized
- Rapid click selection in the selection menu might silently fail to load a deck
- Memory-based random selection process has room for optimization

### Technologies 
This app was originally a plain HTML-JS-CSS page and was migrated to ReactJS for further development. It is a single page application (SPA) built in ReactJS using TypeScript. 

### Deployment
After ensuring you have Node Package Manager (NPM) installed, run Bash in the same directory as the package.json and ReadMe files. Then run the following Bash command.
```sh
npm build
```
This will create a build folder containing an index.html file. Paste the contents of the index.html file into an online HTML beautifier and then use notepad's ctrl+h command to find and replace each instance of ="/ with =" so that the / is removed. At this point, the index.html may be opened locally for full app functionality, and so it can also be pushed to GitHub in this form and accessed through GitPages. 
