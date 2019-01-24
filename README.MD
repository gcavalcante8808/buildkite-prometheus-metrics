buildkite-prometheus
--------------------

A project that illustrate on how to monitor buildkite execution with prometheus.

How to use It
-------------

You need to put the following variables on `.env` file as stated in https://docs.docker.com/compose/env-file/:

 * GRAFANA_ADMIN_PASS: A password to use with grafana.
 * BUILDKITE_TOKEN: The value available on https://buildkite.com/organizations/{your-organization}/agents on reveal token link.

After that, you can start the components with `docker-compose up -d` and access the prometheus in the port 9090 of the localhost.

Author
------

Author: Gabriel Abdalla Cavalcante Silva (gabriel.cavalcante88@gmail.com)

