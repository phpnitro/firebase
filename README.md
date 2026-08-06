# phpnitro/firebase

Client REST Firebase Auth + Cloud Functions, sans SDK Firebase.

Fait partie de [PhpNitro](https://github.com/phpnitro/phpnitro) — un framework PHP qui compile vers de vraies apps Android natives (moteur de rendu Canvas, pas de WebView).

## Installation

```bash
composer require phpnitro/firebase
```

## Usage

```php
use Engine\Firebase\FirebaseAuth;

$result = FirebaseAuth::signIn($webApiKey, $email, $password);
```

## Licence

MIT
