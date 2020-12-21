# Spooncherry

This is a set of personal setup files that [Marie](mailto:m@base0.net) uses to
setup her Linux environment the way that she likes.

As such, it probably won't be a lot of use to anyone else, but if you're
curious, go ahead and take a look.

## Usage

```
./setup
```

## Vim submodules

We use git submodules to store native vim packages.  They should be updated
periodically.  To do so:
```
git submodule update --remote --merge
git commit -m "Updated submodule pins"
```

## License

This code is released under the MIT license, which can be found in LICENSE as well.

