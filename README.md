A python 3 script to pull down a CSV summary of tasks that need marking.

# Required packages:

1. [Canvas API](https://canvasapi.readthedocs.io/en/stable/getting-started.html)

# How to get an API key:

1. Go to [Swinburne Canvas](https://swinburne.instructure.com/) and log in.
2. Click "Account" in the top left.
3. Click "Settings".
4. Click "+ New Access Token".
5. Write anything for the purpose. Leave the expiry blank for no expiry date.
6. Click "Generate Token".
7. Copy the token somewhere safe, if you lose it you will have to generate a new one.

# How to run:

1. Make sure `config.json` is in the same folder as `pull_marking.py`.
2. Replace "your API key goes here" with your generated API key.
3. Run `./pull_marking.py`.
4. Output will be in `marking.csv`. You can use it directly, or import it into your preferred spreadsheet software to sort or filter.