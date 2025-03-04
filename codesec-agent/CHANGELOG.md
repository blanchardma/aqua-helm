# Changelog

All notable changes to this project will be documented in this file.

_1.2.3
* Connector now supports choosing between outbound, inbound or both for proxy preferences.

_1.2.2_
* Inject authentication (CSPM_URL) and API (AQUA_SERVER_URL) environment variables to deployment objects.
* Fix default value of "aquaServerUrl".

_1.2.1_
* Remove "client_url" from env vars validator.

_1.2.0_
* Add "extraEnv" setting to scanner and connector containers.

_1.1.0_
* Add "replicas" setting to 'scan.replicas' values.

_1.0.9_
First release:
* Added SSL configurations as secrets.
* Cosmetics / docs / other small fixes.
* Removed unneeded providers.
* Add "hostAliases" to support connectivity from minikube -> localhost scenarios.
