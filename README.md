# Step 1. Pull docker images
`docker pull nicolaw/tiddlywiki`

# Step 2. Start container with volume
`docker run -p 8080:8080 -e "TW_USERNAME=shaoding" -v "$HOME/wikidata:/var/lib/tiddlyiki" --name mywiki nicolaw/tiddlywiki`