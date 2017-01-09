# duck-face
### what?
I felt like making an image gallery site that recognizes faces and superimposes a duck bill over their noses and mouths.

## why?
because.

## user stories

as a user --
- I want to be redirected to my gallery of duck-faced images when I log in.
- I want to be able to edit the location of my duck-faced images before I save them, in case it looks weird where the app puts it.

### node.js dependencies
<pre><code>npm install --save express ejs express-ejs-layouts
npm install --save morgan body-parser dotenv
npm install --save pg pg-hstore sequelize
npm install --save passport passport-local connect-flash bcrypt express-sessions

npm install -g mocha <!-- already been done -->
npm install --save-dev chai supertest mocha</code></pre>
