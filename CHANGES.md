# Change Log

# 1.1.0

* Fix publish action protocol parameter handling
* Improve v5 protocol support:
  * Fix exception in `mqtt.Client()` when using v5 protocol, don't pass
  `clean_session` parameter.
  * Add `properties` parameter to sensor `_on_connect()` to support v5 protocol.

# 1.0.1

* Fix handling of protocol parameter from config

# 1.0.0

* Drop Python 2.7 support

# 0.2.2

- Add explicit support for Python 2 and 3

# 0.2.0

- Rename `config.yaml` to `config.schema.yaml` and update to use schema.

# 0.1.0

- First release
