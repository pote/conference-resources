## Too Many Models! Data Structures in the Ruby World.

With the rise of Ruby on Rails as the flagship web framework of the Ruby world far too many of us have been dragged into the comfort zone that is modeling our data structures the ActiveRecord way. It's just too damn convenient! With a simple command I can have all the basic files required for my logic to work, and that means little work and no thinking.

This is all fun and games until you realize that your application is a mess, your database is polluted with unnecessary tables and you have to struggle to figure out where a particular piece of business logic should go because your models are not clear enough in their separation of concerns. These are all symptoms to a problem in your data modelling.

So how do we go about this? What is a model really? What is the problem we are really trying to solve with ActiveRecord (or your ORM of choice)? When should we apply it and when should we stick to a plain old ruby object? Speaking of which: What is the deal with all this PORO talk popping up everywhere? What are some clear, minimalistic patterns we can apply to our rails application to have coherent data structures that accurately represent the reality of your application and basically stay out of your way when implementing new stuff?

All these questions and more should be answered in this Zoolander-themed talk!

Talk duration: ~25 minutes + questions.
