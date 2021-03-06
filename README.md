# watch-together
Minimal KISS web app to watch movies together.

## Build from Source
In order to compile this project you need [stack](http://haskellstack.org).

```bash
  git clone https://github.com/fmeyer3141/watch-together
  cd watch-together
  stack build
```

## Usage
Once the project has successfully been compiled run:

```bash
  stack exec -- watch-together /path/to/video/file 3000
```

This will start a webserver on port 3000.

Furthermore you can install the resulting binary using `stack install`, which should copy the
binary to `$HOME/.local/bin`, so make sure it is contained in `$PATH`.
