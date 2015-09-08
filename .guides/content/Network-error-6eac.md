Sometimes a file is displayed in red in the network panel. It means that it was not found at the given url by the browser. This is useful if something that is supposed to load doesn't display in your page. You can identify some errors like this...

## This image doesn't load

As you can see on the page. There is a "broken image" icon in (1). It means that an `img` tag was found but that the image referenced by the `src` attribute was not found.

In (2) we can see that the line is red and it has a Status code of 404 which means : "Not Found" (3)

![](.guides/img/network-error/this-image-doesn-t-load.png)

## Going back to the elements panel

If we inspect the HTML of our page in the Elements panel, we see that the src of our image is `img/thisimagedoesntexist.jpg` which obviously doesn't exist.

![](.guides/img/network-error/going-back-to-the-elements-panel.png)

## Modify it

If we modify it to an image that exist : `panda.jpg`

![][3]

[3]: .guides/img/network-error/modify-it.png

## Result

We can see in our page that now the image is loaded !

![][4]

[4]: .guides/img/network-error/result.png

## Back to network panel

If we go back to the network panel, we can see one more line : `panda.jpg`.

As soon as we changed the src of our image in the Elements panel, the browser tried to load it again, this time with success.

![][5]

[5]: .guides/img/network-error/back-to-network-panel.png

## Try it ! 
This time open <a href="introduction/error.html" target="_blank">this file</a> in another browser tab, it has an error with an image that doesn't exist as above, see how it's displayed in the network panel. Try to replace it by an existing picture as explained.