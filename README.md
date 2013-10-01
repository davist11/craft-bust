# Cache Bust Plugin for Craft

Adds a file modified timestamp to front-end resources.

## Usage

```<link href="{{ craft.bust.er('/css/application.css') }}" rel="stylesheet">```

Outputs:

```<link href="/css/application.css?1372022079" rel="stylesheet">```