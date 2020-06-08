wkhtmltopdf
=========

Installs [wkhtmltopdf](https://github.com/wkhtmltopdf/wkhtmltopdf) (precompiled binary) and it's dependencies for Ubuntu/Debian.

Role Variables
--------------

```yaml
wkhtmltopdf_base_url: https://github.com/wkhtmltopdf/wkhtmltopdf/releases/download
wkhtmltopdf_version: "0.12.5" # the version to install
wkhtmltopdf_dependencies:
  - fontconfig

```

License
-------

BSD / MIT
