# astrx/support

The installation's paths, the resource roots packages register, and atomic file writes.

A component of [AstrX](https://github.com/Vxmdzhb/astrx), the PHP framework for server-rendered sites
that work without JavaScript. It used to live in
[`astrx/framework`](https://github.com/Vxmdzhb/framework); this repository carries its history over.

Depends on: nothing else from AstrX.

AstrX isn't on Packagist and doesn't tag versions: you install from each
repository's `main`, and your `composer.lock` pins the exact commit. Tell
Composer where to find the package and the AstrX packages it depends on:

```json
{
    "minimum-stability": "dev",
    "prefer-stable": true,
    "repositories": [
        { "type": "vcs", "url": "https://github.com/Vxmdzhb/support" }
    ]
}
```

Then:

```sh
composer require astrx/support:dev-main
```

Issues and pull requests are welcome here. [AstrX](https://github.com/Vxmdzhb/astrx) is the site
that puts all the packages together.

## License

Released under the [Do Whatever License](LICENSE), with a code of conduct
in the same spirit: [CODE_OF_CONDUCT](CODE_OF_CONDUCT).
