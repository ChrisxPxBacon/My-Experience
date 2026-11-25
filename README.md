# My Experience

A simple personal blog made of plain web pages. There is nothing to install and nothing to set up. Each page is one file, and you change the site by changing the words in those files.

## What is in here

| File | What it is |
| --- | --- |
| `index.html` | The home page: a short welcome and the list of posts. |
| `about.html` | The About page. |
| `style.css` | The look of the whole site: colors, fonts, spacing. Every page uses it. |
| `posts/sample-post.html` | A sample post that shows what a post can contain. Replace or delete it whenever you like. |
| `posts/post-template.html` | A blank post. You copy this each time you write something new. |

## How to add a post

You can do all of this on github.com, in your web browser.

**Part one: make the post**

1. Open the `posts` folder and click `post-template.html`.
2. Click the copy button near the top right of the file (two overlapping squares, labeled "Copy raw file").
3. Go back to the `posts` folder. Click **Add file**, then **Create new file**.
4. Name the file. Use lowercase letters, hyphens instead of spaces, and end with `.html`. For example: `sunday-roast-chicken.html`.
5. Click in the big empty box and paste.
6. Make the four changes marked `CHANGE 1 of 4` through `CHANGE 4 of 4`: the tab title, the one-sentence description, the date, topic, and title, and then your writing. The bottom of the file has a section called BUILDING BLOCKS with lines you can copy for headings, quotes, lists, questionnaire questions, and photos.
7. Click the green **Commit changes** button, then **Commit changes** again. That saves it.

**Part two: add it to the home page**

1. Go back to the top folder and click `index.html`, then click the pencil icon to edit it.
2. Find the block that begins with `START OF ONE POST` and ends with `END OF ONE POST`. Copy the whole block.
3. Paste it directly above the first block in the list, so the newest post is on top.
4. In your new block, change the date, the topic, the title, and the one-sentence description. Then change the file name in `posts/sample-post.html` to the name you chose, for example `posts/sunday-roast-chicken.html`.
5. Click **Commit changes**, then **Commit changes** again.

The new post appears on the live site a minute or two later.

## How to replace the sample post

Open `posts/sample-post.html`, click the pencil icon, and change the words. If you would rather remove it, open the file, click the three dots at the top right, and choose **Delete file**. Then edit `index.html` and delete its block from the list of posts.

## How to add a photo to a post

1. Open the `posts` folder. Click **Add file**, then **Upload files**, and choose the photo from your computer or phone. Give photos simple names with no spaces, such as `roast-chicken.jpg`.
2. In your post, on its own line where you want the photo, add this, using your photo's name and a few words describing it:

   `<img src="roast-chicken.jpg" alt="A roast chicken in a cast iron pan">`

The description is read aloud to people who cannot see the photo.

## How to change the About page or the welcome

Open `about.html` or `index.html`, click the pencil icon, and change the words between `<p>` and `</p>`. Leave the `<p>` and `</p>` in place. They mark where a paragraph starts and stops.

## How to change the colors

Open `style.css`. The colors are listed at the very top, each with a note saying what it is for. Change a color code and the whole site changes.

## How to put the site online, free

This is done once.

1. On the repository page, click **Settings**.
2. In the left-hand menu, click **Pages**.
3. Under **Source**, choose **Deploy from a branch**.
4. Under **Branch**, choose **main** and **/ (root)**, then click **Save**.

After a minute or two the site is live at:

https://chrisxpxbacon.github.io/My-Experience/

## Two things worth knowing

Keep the angle brackets. Pieces like `<p>` and `</p>` come in pairs, one to open and one to close. If a page suddenly looks wrong, a missing bracket or closing piece is almost always why.

Nothing is ever lost. GitHub keeps every earlier version of every file. Open a file and click **History** to see them.
