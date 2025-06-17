# Vector search

By now we were using a basic key words search based method. Bat = bat in a cave

Verctor search is work much wider. Bat = image of bat, sound of bat, flying mouse. It works with a semantic search.

Qdrant written in rust.

[schema]

It's important to use correct embeded model for making vectors

It makes sense to choose a model that produces small-to-moderate-sized embeddings (e.g., 512 dimensions), so we don’t overuse resources in our simple setup.

Let’s pick a random question from the course data.
As you remember, we didn’t upload the questions to Qdrant.
