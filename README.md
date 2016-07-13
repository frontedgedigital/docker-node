# Node Docker Image

This is a lightweight Docker image for Node.js application development. It's currently based on Alpine Linux & adds prerequisites for building & running a Node.js application.

We've
- added user `node` (with user id `1000`) as a sudoer, and
- prepended `./node_modules/.bin` to the `PATH` as a convenience so you don't have to type `$(npm bin)/...`.

Enjoy!

--The SciSpike Team, docker@scispike.com
