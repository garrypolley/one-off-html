# One Shot HTML Applications

This repository contains standalone HTML applications that run entirely in the browser.

## Running the Applications

To run these applications properly, you need to serve them via a web server (not just open the files directly in your browser). This is required for features like text-to-speech to work correctly.

### Using Python's Built-in HTTP Server

Navigate to this directory in your terminal and run:

```bash
python -m http.server 9010
```

Then open your browser and go to:
```
http://localhost:9010
```

This will show the index page with links to all available applications.

## Available Applications

- **Test Voices** (`voice-test.html`) - Test browser text-to-speech functionality with different voices