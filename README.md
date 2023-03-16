# adguard-downtime

Files to import into adguard via Home Assistant as a workaround until switches are available.

## Justification

There is currently (a PR)[https://github.com/home-assistant/core/pull/83505] to enable the ability to utilize the service blocking
functionality of adguard, but it is dependant on upstream library changes and
might take some time to implement. These are to duplicate the services and block
via the `enable_url` service in the integration as it works today.