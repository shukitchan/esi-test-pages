# esi-test-pages
Test Pages for testing ESI implementations

* Basic idea is to create multiple test pages in this repo and expose them through a service like Netlify so we can also append changes to the response header as well. The domain exposing these pages is - https://esi-test-pages.netlify.app/
* You can setup your own proxy server with ESI support to route traffic for https://www.example.com/ to these pages under https://esi-test-pages.netlify.app/
* We may use query parameters from the request to alter the response headers through Netlify before it is handled by target ESI implementation we want to test.
