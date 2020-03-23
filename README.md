# Flexing @Media

Today, we're going to make a responsive website that uses media queries. For the content, let's make it plain: a grid of 20 boxes. The CSS for each square is already in your `style.css`, though feel free to change it.

Here are the different column layouts we want:

1. When the screen is less than 600px, make 1 column of 20.

2. When the screen is between 600px and 800px, make 2 columns of 10.

3. When the screen is between 800px and 1000px, make 10 columns of 2.

4. When the screen is greater than 1000px, make 20 columns of 1.


### Setting Up

1. Fork and clone this repo.
2. Let's start using HTML snippets! Go to [our html snippets repo](https://github.com/ci-wdi-900/html-snippets) and download or clone the `html.json` file. Now open VS Code, enter the command palette (Command-Shift-P) and find Preferences: Configure User Snippets. Scroll down to and select `html` (or start typing "html"!), then copy and paste the entire contents of your downloaded file into there.
3. Now you can USE that snippet. Create an `index.html` in your forked version of this repo and type "html". Three autocomplete suggestions are for the snippets you just grabbed: an html skeleton, an html skeleton with a `style.css` link, and an html skeleton with the `style.css` link and a `main.js` link. For this one, we don't need any JavaScript, so just choose that second one and you've got your HTML skeleton! (You can find LOTS of snippet collections out there, including just by typing "snippets" in the extension search in your sidebar!
4. Now let's use Emmet to make 20 divs with the "square" class (defined already in our CSS file!) and a number in each one. Type the following code (without backticks) into the body and hit enter: `div.square{$}*20`. Now you've got most of the html you need for this assignment and you can get started! Try to use these tools whenever you can; they'll save you a lot of time.


### Hints

* You can add further container-type divs to the HTML. In fact, you'll probably have to! This way you can rotate rows to columns and back with ease.


### Tools You Should Use

* Media queries with `max-width` and `min-width`.
* `flex-direction`.


### Stretch Goals:

1. Adust the look in some way (up to you!) for portrait vs landscape mode.
2. Use an entirely different thing to query for besides width and orientation! Do something fun with it!
