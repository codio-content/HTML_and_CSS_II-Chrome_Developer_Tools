# Bridging the gap between the source code and the final result

One of the big difficulties that people face when they start web development or software development in general is that they have to "blindly manipulate symbols". What it means is that development is an abstract and indirect activity. When you are drawing on paper, if you want to draw a table, you put a pen on  paper and draw lines and then write down the content into the cells. Where you place the pen is where the lines appear (direct manipulation). If you want to do a table in html, you have to manipulate symbols in a code editor, like `<table>` , `<tr>` and `<td>` tags, imagine inside your brain what the correct structure should be, then write it down in the correct order in the text editor. When you are done, you go to the preview window and hit the refresh button. What you manipulate (the code, symbols) is not what you produce (the web page, a table). You never know for sure what the output will be. You are blindly manipulating symbols in a code editor and then in another view, you see the result, with a delay. If something goes wrong, you have to guess based on the wrong visual result you have in the preview window, where is the problem in your code. Sometimes the preview window just doesn't display anything and then you  really have to guess where the problem is. You are really blindly manipulating symbols.

This is a very difficult process that involves modeling inside your mind the structure needed for the final result you want to achieve. It involves going back and forth between the code and the end result, bridging the gap between those two inside your mind.

# Developer tools

In order to make this process easier, developer have tools available. For example : In the code editor you have colored syntax highlighting, so you can directly see if something is wrong with the structure of your html and try to correct it. In Codio, we have the code just above the preview window, so the round-trips between code and result are easy. Nevertheless when something is wrong in your result, you still have to guess what's wrong in the code.

# Chrome developer tools

Chrome developer tools (and equivalents in other browsers$$1) try to make this process much more easy, by visually interacting with the code and directly seeing the link with the end result. You can inspect the code in realtime and see what code is linked to what part of the result. You can change the html and css and see the result instantly. Have a look at the following video for a quick preview of how powerful these tools are!

<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'><iframe src='https://player.vimeo.com/video/136277273' frameborder='0' webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe></div>


Don't worry about the details for now. We will see how to use the developer tools in details in the next sections.

---
1 : Firebug in firefox, Developer tools in Internet Explorer, and Safari.
