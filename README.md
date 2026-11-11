# Elo

Elo finds products to buy from stores in your country. Ask Claude for what you want, with any
budget, size, brand or features, and Elo returns up to twenty matching products, each with its
current price, the store and a link to buy it. It marks the best match, a lower-priced pick and
a higher-end pick.

## What is in the plugin

- **Connector**: Elo's MCP server at `https://mcp.elo.ad/mcp`, with the `search_products` and `search_several` tools.
- **Skill** `find-products`: tells Claude when to search and how to present the results.

## Use it

Connect the Elo connector from the plugin's Connectors tab, then ask:

- "Find waterproof hiking boots for women under $150."
- "Gift ideas for a 10 year old who likes science, under $40."
- "Show me cheaper options."
- Attach a photo of an outfit: "Where can I buy what is in this photo?"

Elo only searches products. It does not book hotels, flights or restaurants, find services, or
answer how-to questions.

## Account and data

Elo needs no account and no sign-in. It shows no ads. It receives the shopping request Claude
sends and the country to search in, never the rest of the conversation.
Privacy policy: https://elo.ad/privacy. Support: contact@elo.ad.
