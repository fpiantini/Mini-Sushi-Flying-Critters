1. Click on styles.css

2. There you can see what colours are defined for the website. The text colour is `color` and the background is `background-color`. Change the values to colours that you like. For a list of colour names you can use, see dojo.soy/html-colours

3. For the next step you’ll need a picture of a zoo animal that you like. It needs to be saved on your computer. If you don’t have one handy, you can search the internet and download a picture, or even draw one.

4. Click the image icon to the right of the tabs, then **Add Image**, then **Upload**, then **Click To Select Files**.

5. Find the picture file on your computer, select it and click Open. Click **Done**.

6. Now click on the index.html tab, and add the following line of code on a new line after the last `</p>` tag.
    ```html
        <img src="lions-1660044_640.jpg" />
    ```

7. Change “lions.jpg” to the filename of your picture. It must match the file name exactly. The picture should appear on your page when you click Run.

8. Let’s turn it into a link that takes you to a page all about the animal! First, create a new page...

9. Click the plus and type **lion.html** where it says “file name”. Change it to whatever animal you have, but be sure the name ends in **.html** as this is what makes it a **web page**.

10. Add all the following code to the new file:
    ```html
        <!DOCTYPE html>
        <html>
            <head>
                <title>Picture Click</title>
                <link type="text/css" rel="stylesheet" href="styles.css"/>
                <meta charset="utf-8"/>
            </head>
            <body>
                <header>
                </header>
                <main>
                
                </main>
                <footer>
                </footer>
            </body>
        </html>
    ```

11. This is the code for a blank page. To add a paragraph of text, click in the blank space between the` <main></main> `tags and type `<p></p>`

12. Type your text in between the tags, like this:
    ```html
        <p>This page is all about lions!!!!</p>
    ```
    You can add as many paragraphs like this as you want.
    * Can you add pictures too?

13. Go back to index.html. To turn your picture into a link you need to put it in between a pair of `<a></a>` tags, like this:
    ```html
        <a href="lion.html"><img src="lions.jpg" /></a>
    ```
    Change **lion.html** to the name of the new page you created.

14. Now when you click run, you should be able to click on the picture and see the page about that animal.

15. On a new line underneath your image and link code, write some more code to show another picture that links to another new page. Don’t forget to upload a file for your picture!

16. Do as many as you like! What animals are in your zoo?

-{% callout %}To learn how to do more with your website and earn yourself a digital badge, visit dojo.soy/begin-html-sushi and try the Beginner HTML CSS Sushi cards!
-{% endcallout %}


