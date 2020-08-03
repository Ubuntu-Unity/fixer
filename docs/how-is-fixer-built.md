# How is `fixer` built

Fixer is a BASH script, which has a configuration file, `/etc/fixer.conf`, and fetches fixes from a server using `curl`.

## Dependencies
* bash - As this is a BASH script
* coreutils - For standard utilities
* curl - To fetch fixes from the server

## How to build
`fixer` is a BASH script, and thus doesn't need to be built/compiled.
