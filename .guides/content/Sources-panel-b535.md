It allows us to inspect the source code of all the files (html, css, js) of our page.

## An overview

1. You can see the files and folders, separated by domains. Here all our files come from "darwin-explain.codio.io" which is the url of the box hosting this file.
1. The content of "index.html" as received by the server.
1. If you click on style.css you can see its content.

![][1]

The main difference between this panel and the Elements panel is that here it's the raw files as received from the server which are shown. In the Elements panel it's the files as parsed and understood by the browser (they might be different as the browser might not understand some elements or elements might have been added in javascript later and thus will only be seen in the Elements panel, not in the original sources).


[1]: .guides/img/sources-panel/an-overview.png