# heroku-buildpack-cleanup

Remove files that are specified in a .slugcleanup file.

## Usage

    $ heroku buildpacks:add https://github.com/dockspot/heroku-buildpack-cleanup.git

    $ cat .slugcleanup
    gradle*
    node_modules

## License

MIT
