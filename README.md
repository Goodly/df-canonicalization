# DecidingForce: canonicalization

This repo collects some of the attempts to create canonical accounts of protests during the Occupy movement in the United States. In broad strokes, by gathering metadata about segments of news articles written about events and crowd-sourcing annotations and answers to questions about those same article segments, we generate a large amount of data about news articles and the events they cover. The task then is to devise a way to, based on features of the article segments, group article segments based on the events they cover such that each event has associated to it a number of articles. 

Once we reach this point, our problem flips on its head; we are no longer interested in distinguishing article segments, but in combining article segments. For any given event, if there are a number of article segments associated with it, the event could get covered in many different ways with varying details appearing in each article segment. Once the article segments are grouped, finding a way to merge differing accounts is the aim of the canonicalization.

Read more about the project [here](http://www.goodlylabs.org/research/).