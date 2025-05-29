# Network

## Network security

`BEST PRACTICE:` Place `ZERO-TRUST` in all networks, including internal “secure” networks. 

!> Use TLS everywhere for all application communication channels with everyone and everything.

It is a best practice to operate under the zero-trust networking model where you assume
that the network is always untrusted. Treat the internal data center network with the same
level of suspicion that you treat the internet. 

It is tempting to assume that there is no need to encrypt communications between the
application backend and its database because the traffic is on a “trusted” internal network.
Resist the temptation to trust the data center network for the following reasons.

• `Configuration errors:` security configuration errors on the network are possible
especially in large corporate networks with hundreds and thousands of applications.

• `Disgruntled insider:` a company insider with legitimate network access might choose to
attack the application.

• `Compromised application:` The “internal” corporate network has many applications on
it, some are internal applications built by the enterprise, some are COTS applications
purchased fam a variety of vendors. If a single applications on the internal network is
comprised, then the whole network is compromised.

## 