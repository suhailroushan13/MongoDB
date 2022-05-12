# ![Logo](docs/leaf.svg) MongoDB README

Welcome to MongoDB!
# MongoDB
MongoDB is a source-available cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with optional schemas. MongoDB is developed by MongoDB Inc. and licensed under the Server Side Public License

## Components

  - `mongod` - The database server.
  - `mongos` - Sharding router.
  - `mongo`  - The database shell (uses interactive javascript).

## Utilities

  `install_compass` - Installs MongoDB Compass for your platform.


## Running

  For command line options invoke:

  ```bash
  $ ./mongod --help
  ```

  To run a single server database:

  ```bash
    $ sudo mkdir -p /data/db
    $ ./mongod
    $
    $ # The mongo javascript shell connects to localhost and test database by default:
    $ ./mongo
    > help
  ```

## Installing Compass

  You can install compass using the `install_compass` script packaged with MongoDB:

  ```bash
    $ ./install_compass
  ```

  This will download the appropriate MongoDB Compass package for your platform
  and install it.

## Drivers

  Client drivers for most programming languages are available at
  https://docs.mongodb.com/manual/applications/drivers/. Use the shell
  (`mongo`) for administrative tasks.


## Documentation

  https://docs.mongodb.com/manual/


## Learn MongoDB

  https://university.mongodb.com/

