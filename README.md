# 👩‍💻 put-me-on-a-watchlist.py

<img width="822" alt="screen shot 2017-07-13 at 14 45 11" src="https://user-images.githubusercontent.com/6472410/28167489-12c39bfc-67dc-11e7-9637-956a51ad0d87.png">


Dragnet surveillance and other ridiculous bullshit are making it possible for governments and corporations to retrieve anyone's browsing history. This script generates some noise in that data pool by performing a shitload of dubious Google searches, like "how to make a bomb". Leave it running for a while, pollute the browsing history of your IP address. If there's enough noise, your legitimate searches are obscured and your data profile will not be reliable anymore!

## Running the script
You need Python on your system. Then go to the directory where you downloaded the script and type `python put-me-on-a-watchlist.py` in a Terminal or Command Prompt.

## Docker support
Want to pollute your data profile on a Larger Scale? For some reason this script has Docker support. (Thanks [@johanot](https://github.com/johanot)!)
Build the container: `docker build -t put-me-on-a-watchlist .`
Run it: `docker run -t --rm put-me-on-a-watchlist`

Want to test first so you still have time to arrange an escape plan for when the cops show up? You can do a dry-run without network: `docker run -t --rm --net none put-me-on-a-watchlist`

## Can I talk to you about this script?
Sure, tweet [@neufv_txt](https://twitter.com/neufv_txt).
