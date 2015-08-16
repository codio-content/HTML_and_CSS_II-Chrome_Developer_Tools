## Overview

The network panel allows us to see everything that's loaded by the browser through the network.

Here are some interesting parts of it.

1. Filter box : Filter files by name (We will see more underneath).
1. Filter bar : Filter files by type (We will see more underneath).
1. The list of files loaded files along with many information, from left to right :
  1. The file name.
  1. The HTTP method used to get it (Most of the time : GET). If you want to know more about HTTP request methods, [see here](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol#Request_methods).
  1. The Status code (200 = OK, 304 = Not modified, meaning it was taken from the cache instead of the network, 404 = Not found, ...) If you want to know more about Status code, [see here](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes).
  1. The Document Type.
  1. The Initiator : Here we see that the last 4 documents where loaded from index.html.
  1. The size of the document.
  1. The time take to load.
  1. And the "Timeline" (We will see more underneath).

![](.guides/img/network-panel/overview.png)

## Filter box

In the filter box you can enter any text and it will display only the files that match this text in their name.

Here we entered "pand" and the only file left is "panda.jpg".

![](.guides/img/network-panel/filter-box.png)

## Filter bar

You can click on any of the buttons, to only display files of this type.

Here we clicked on "Images" and as a result, only the images are displayed in the list.

![](.guides/img/network-panel/filter-bar.png)

## Timeline details

The timeline gives us an overview of what took time while loading the file.

Here you can see :

1. Stalled : It means the connection was "stalled" for 252ms before starting to work.
1. DNS lookup : It returns an internet IP address based on the domain name.
1. Initial connection : The time to initiate the connection to the server.
1. SSL : Time to setup SSL security on the connection.
1. Request sent : Time to send the request to the server.
1. Waiting (TTFB) : Waiting time for the server to answer.
1. Content Download : Time to actually download the content from the server

You can click on the little "explanation" blue link at the bottom of the timeline details if you want to know more.

![](.guides/img/network-panel/timeline-details.png)


## Right clicking on a file in the list

It gives us many interesting actions, here are some that we frequently use :

1. It will open the file in the "Sources" Panel in order to see its content.
1. It will open the file in a new browse tab so we can inspect it.
1. It will copy the link address if we need to use it.


![](.guides/img/network-panel/right-clicking-on-a-file-in-the-list.png)


## Try it ! 
Go back to the other browser tab we opened to play with the developer tools (or <a href="introduction/index.html" target="_blank">open it again</a> if you closed it) and try seeing the time it takes for your browser to load the different parts of this webpage. If there is nothing in the network tab, just reload the page.