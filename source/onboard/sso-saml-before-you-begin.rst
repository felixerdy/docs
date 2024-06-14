:nosearch:

Before you begin
----------------

Before you begin, you need to generate encryption certificates for encrypting the SAML connection.

1. You can use the `Bash script <https://github.com/mattermost/docs/tree/master/source/scripts/generate-certificates>`_ from the ``mattermost/docs`` repository on GitHub, or any other suitable method. See the `generate self-signed certificates <https://github.com/mattermost/docs/blob/master/source/scripts/generate-certificates/gencert.md>`_ documentation for details on generating a self-signed x509v3 certificate for use with multiple URLs / IPs.
2. Save the two files that are generated. They are the private key and the public key. In the System Console, they are referred to as the **Service Provider Private Key** and the **Service Provider Public Certificate** respectively.
