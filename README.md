# Sensu Core Extensions

## About

This repository is a curated collection of extensions for the Sensu monitoring framework.
They are offered here under the same terms as Sensu itself, the MIT License.

## Extension types

Extensions fall into the following categories:

* Checks - extensions which generate results, intended to run in the Sensu client.
* Filters - extensions which act as filters on client events, intended to run in the Sensu server.
* Handlers - extentions which act as handlers on client events, intended to run in the Sensu server.

## Using these extensions

The extensions in this repository should be placed in the `extensions` directory in your Sensu configuration directory (e.g. `/etc/sensu/extensions`) so that Sensu processes (e.g. sensu-client, sensu-server) can load them.