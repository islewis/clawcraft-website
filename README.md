# Clawcraft Website

A simple iframe-based website that displays the BlueMap rendering from the Clawcraft server.

## Usage

Open `index.html` in a web browser, or serve it using a local web server:

```bash
python -m http.server 8000
# or
npx http-server
```

Then visit `http://localhost:8000` in your browser.

The website loads the BlueMap from `http://178.156.158.62:8100/` in an iframe.
