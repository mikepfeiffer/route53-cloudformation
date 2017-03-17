# AWS CloudFormation Template for Creating Route 53 DNS Record Sets

This sample AWS CloudFormation template accepts two parameters. One for the public Route 53 hosted zone id, and one for the domain name. The use case for this example is for a mail server but can be adapted to support any DNS record type supported by Route 53.

This template creates an A record that resolves to an elastic IP. It also creates an MX record with a priority of 10 which resolves to the A record for the mail server.
