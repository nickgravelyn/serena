# Changelog

## Unreleased

- Automatic browser refresh is now the default behavior as that's what I personally find most useful. With this the `-w`/`--watch` option has been removed. A new `--no-auto-refresh` option has been added to disable auto-refreshing for cases where people prefer to manually refresh their browsers to see updates.

## 21.3.0 - 2021-03-28

- serena serves static files from a directory on disk
- `-p`/`--port` option to specify the port (default is `3000`)
- `-w`/`--watch` option to automatically refresh browsers when a file in the directory changes
