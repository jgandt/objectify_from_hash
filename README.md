Gemified and Improved at: [jgandt/ostend](https://github.com/jgandt/ostend)

Using this as a mix in we are able to maintain a meaningful class structure while exposing the hash keys as viable and visable methods.
I had a lot more I wanted to do in my FileCopyTask, and I didn't feel that the objectification logic was correctly placed in my class. 

The really neat part about this is that you could extend an individual instance of an object and objectify it in place.
You could do all sorts of other crazy things with definition of reader/writer/accessor permissions in the objectify call.

This may be entirely useless and silly but I think it is a slightly better option than returning an object of the class Hashit/ObjectifyFromHash

OpenStruct is a viable alternative. However, I was unable to find a way to use the Plain class as a mixin.

Thoughts? Comments? Need more of the code around what I'm doing? Is their an easier, clearer way (ActiveModel if working in rails)?

.jpg
