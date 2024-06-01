# Experimenting with CLIP
This repo contains some initial experimnents with OpenAI's CLIP model. These are mostly focused on some basic prompt engineering-style tasks.

My end goal is to see if I can coerce CLIP into being an image retrieval engine for receipts. These were chosen as they are a very complex form
of visual data, with small changes in detail often having a large effect on the desired result, and so are a challenging datatype to work with 
(particualrly for purely visual models). 

Ideally, in the end state the user can type in a short natural language prompt and often get back the receipt that they were looking for.
Another approach might be to get the user to specify the criteria they are looking for (eg "total: amount" or "contains: item" or "item cost: amount"),
programmatically constructing a prompt and then using that to obtain the image.

I want to achieve all of this in a purely zero-shot manner
