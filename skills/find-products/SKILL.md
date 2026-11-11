---
name: find-products
description: Use when the user wants to buy something, asks where to buy a product or what is in a photo, wants gift ideas, wants cheaper or different options, or compares the prices of products. Searches stores in the user's country with Elo and returns products with current prices and links.
---

Call Elo's `search_products` tool with one shopping request. Put everything the user said that
narrows the search into the query: the product, the budget, the size, the brand, the features
and who it is for. Pass `country` as a two-letter code when the user names a country or it is
clear from the conversation.

- "Waterproof hiking boots for women under $150"
- "A gift for a 10 year old who likes science, under $40"
- "Wireless noise cancelling headphones for travel"

When the user wants several different things at once, such as the pieces of an outfit or what
a room needs, call `search_several` with two to six things, each with a short label and its own
request. When the user attaches a photo and wants to buy what is in it, name each thing you see
and call `search_several` with them.

Elo returns up to twenty products, each with its current price, the store and a link, and marks
the best match, a lower-priced pick and a higher-end pick. Tell the user which products fit the
request best and why, with the price, the store and the link of each. Do not invent a price or
a link. When the user asks for cheaper or different options, search again with the changed request.

Elo only searches products. Do not use it for hotels, flights, restaurants, services or how-to
questions. It shows no ads and needs no account and no sign-in.
