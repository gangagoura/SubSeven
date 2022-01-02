Configure SubSeven Server Service

If no configuration specified or if default configuration is used, server will only listen for incomming connection from local host.

However, you won’t be able to establish a complete session since by default configuration uses public key authentication without any defined authorized keys. Your connection will be rejected.

The following page will describe how to configure your own SubSeven server and understand available options.

The configuration file uses JSON format to describe different supported properties and might evolve between SubSeven Server versions.

Notice that each time you update the configuration file, you will need to restart the SubSeven Server Service to apply the new configuration.

The configuration file is located in the SubSeven Server installation path (in C:\Program Files\SubSeven Server\config.json.

When SubSeven Server is installed for the first time, this file is not present. You will need to create the file manually or use the SubSeven Service Controller to generate and edit this file which is the recommended method.
