# strappy revisited

I initially built [strappy](https://github.com/trexlerlibrary/strappy) as a temporary solution when it was discovered that WorldShare ILL didn't initially have a book strap generator. It was a simple PHP app that we hosted on our Library's server.

This port is an attempt to make strappy as simple to implement as possible. The idea is to be able to fork this repo to your own institution, edit the `strap_body.md` file to contain your institution's ILL policies, drag the generated bookmarklet to your bookmarks bar (see **TODO** below), and be good to go. 

## TODO ##
* [ ] bookmarklet generator (see [https://github.com/TrexlerLibrary/strappy/blob/master/strappy.js](the original strappy's bookmarklet code) for a rough idea)
* [ ] refactor out jQuery to cut down on number of dependencies
* [ ] better readme / instructions
* [ ] options for ILS other than WorldShare
