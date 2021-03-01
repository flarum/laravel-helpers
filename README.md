# Flarum Laravel Helpers

Some Laravel repos expect certain [Laravel Helpers](https://laravel.com/docs/8.x/helpers) to be available globally.
This package collects some of these helpers for use by extensions.
These helpers should NOT be used directly in Flarum extension code; they are available so that Laravel-based libraries that expect them to exist don't malfunction.

If your extension uses a Laravel library that expects a helper not provided here, please open a [Github Issue](https://github.com/flarum/core/issues) to request that it be considered.

## Currently supported helpers

- `app`
- `event`
- `base_path`
- `storage_path`
- `public_path`
