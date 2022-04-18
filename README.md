# COLLECTION-fed3wan
This repository is collection of BSP, required library and application sketch for integration of Catena 4610 to get data from FED3 and transmit over netwrok.

This repo is intended to be built on Linux (Ubuntu 18 or later).

To build:

1. Clone this repository:

    ```bash
    git clone --recursive git@github.com:mcci-catena/COLLECTION-fed3wan.git
    ```

2. If building with a project secure key, get a copy of that key and put it someplace handy; please make sure it's password protected, at least.

3. Build with the following commands:

    - to build with the test-signing key:

      ```bash
      ./build-with-cli --verbose --test
      ```

    - to build with a project-specific key:

      ```bash
      ./build-with-cli --verbose --key={path-to-file}.pem
      ```

   The output shows up in `{slug}/build/{outputname-version-network-region-serial}/ide`.

