# API practice with Node.js

Small Node.js scripts that call public REST APIs with different HTTP clients (`request`, `axios` and `node-fetch`):

| Script | API |
| --- | --- |
| `index.js` | OpenWeatherMap current weather |
| `nasa.js` | NASA open APIs |
| `book.js` | Open Library subjects |
| `random.js` | Random User generator |
| `axios.js`, `fetch.js` | The same kind of requests with axios and fetch |

## Usage

```bash
npm install
node index.js
```

Each script defines its own `API_KEY` constant near the top; replace it with your own key before running.
