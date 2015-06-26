# Factis store group

This module is a datastore for [Factis](http://factis.io), the modular database system.

The group store allows to group several stores into a single store.

## Installation

Using NPM

    npm install factis-store-group

## Usage

Require the module

    var FactisGroup = require('factis-store-group');

Create a new group by selecting some stores

    var myGroup = new FactisGroup([store1,store2,...,storeN]);

You can also add stores to the group afterwards

    myGroup.addStore(anotherStore);



Check the documentation on [factis.io](http://factis.io)
