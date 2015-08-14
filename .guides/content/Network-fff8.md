## Overview

The network panel allows us to see everything that's loaded by the browser through the network.

Here are some interesting parts of it.

1. Filter box : Filter files by name (We will see more underneath).
1. Filter bar : Filter files by type (We will see more underneath).
1. The list of files loaded files along with many information, from left to right :
  1. The file name.
  1. The HTTP method used to get it (Most of the time : GET)
  1. The Status code (200 = OK, 304 = Not modified, meaning it was taken from the cache instead of the network, 404 = Not found, ...)
  1. The Document Type
  1. The Initiator : Here we see that the last 4 documents where loaded from index.html
  1. The size of the document
  1. The time take to load
  1. And the "Timeline" (We will see more underneath).

![][1]

[1]: .guides/img/network-panel/overview.png

## Filter box

In the filter box you can enter any text and it will display only the files that match this text in their name.

Here we entered "pand" and the only file left is "panda.jpg"

![][2]

[2]: .guides/img/network-panel/filter-box.png

## Filter bar

You can click on any of the buttons, to only display files of this type.

Here we clicked on "Images" and as a result, only the images are displayed in the list.

![][3]

[3]: .guides/img/network-panel/filter-bar.png

## Timeline details

The timeline gives us an overview of what took time while loading the file.

Here you can see :

1. Stalled : Meaning the connection was "stalled" for 252ms
1. DNS lookup : It returns an internet IP address based on the domain name.
1. Initial connection : The time to initiate the connection to the server.
1. SSL : Time to setup SSL security on the connection.
1. Request sent : Time to send the request to the server.
1. Waiting (TTFB) : Waiting time for the server to answer.
1. Content Download : Time to actually download the content from the server

![][4]

[4]: .guides/img/network-panel/timeline-details.png

## Right clicking on a file in the list

It gives us many interesting actions, here are some that we frequently use :

1. It will open the file in the "Sources" Panel in order to see it's content.
1. It will open the file in a new browse tab so we can inspect it.
1. It will copy the link address if we need to use it.



![][5]

[5]: .guides/img/network-panel/right-clicking-on-a-file-in-the-list.png