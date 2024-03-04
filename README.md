# IP History

This is used for logging used IP address and it's only stored to `localStorage` for persistence.

### Installation

Just upload the whole project or just the `index.html` to your web server. This won't work on `file://` protocol since it sends HTTP requests to an API.

### API used

This file sends HTTP GET request to `ipinfo.io/json`. You can change it but you may also need to change how the response is parsed.

Read more at: [https://ipinfo.io/developers]()

### Disclaimer

This page stores your IP address locally to your browser and does not store or transmit this information internally or to external databases.
