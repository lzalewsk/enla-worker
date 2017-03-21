# enla-worker
Docker worker for ENLA system.

## Input/output configuration
Use `conf.toml` file format for input/output configuration (for notation details check [toml](https://github.com/toml-lang/toml) specs, Release v0.4.0).

Valid `conf.toml` file must be mounted from your persistent storage to docker's `/conf` directory.

## Reference links
This project is based on ODIS (https://github.com/lzalewsk/odis-worker)
