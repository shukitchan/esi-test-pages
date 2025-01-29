# esi-test-pages
Test Pages for testing ESI implementations

Basic idea is to create multiple test pages in this repo and expose them through a service like Netlify so we can also append changes to the response header as well.
We will use query parameters from the request to alter the response headers through Netlify before it is handled by target ESI implementation we want to test.
