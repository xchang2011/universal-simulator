universalSimulator

Introduction
============


  1. Get the resources of the mockserver.
  2. Put the idl files to the mock_protocol/body.
  3. Edit the configurations according to your need.
  4. Start the mockserver with the right options. (You can use 'python stub.py -h' to view the help
     information of the options.)


Installation
============

  1. Get the resources of the mockserver.
  2. Put the idl files to the mock_protocol/body.
  3. Edit the configurations according to your need.
  4. Start the mockserver with the right options. (You can use 'python stub.py -h' to view the help
     information of the options.)

Test
===========

You can start a udp server with commands like this:

python stub.py -c udp -s server

You can start a udp client to send data to the server before with commands like this:

python stub.py -c udp -s client
