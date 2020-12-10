# fonts-asset-Raleway
Raleway for composer.

## Install

```bash
composer require oomphinc/composer-installers-extender
composer require fonts-asset/raleway
```

And in `composer.json`:

```json
    "extra": {
        "installer-types": [
            "fonts-asset"
        ],
        "installer-paths": {
            "public/fonts/{$name}": [
                "type:fonts-asset"
            ]
        }
    },
```

## Usage

```html
<link rel="stylesheet" href="/fonts/raleway/raleway.css">
```

## Credit

[Google Fonts](https://fonts.google.com/)