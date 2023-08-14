# Endogenous RPC Relayer and Load Balancer For P2P Network - Substrate

This project is an attempt at implementing an economically incentivized RPC relay and load balancing mechanism among nodes in a p2p network.


## Motivation

RPC endpoints allow nodes to gossip with one another as well as accept external RPC requests. 

The current RPC providers for decentralized networks like blockchains are controlled by centralized entities whose interest does not always align with that of the decentralized network they support.

This protocol describes how RPC requests are handled in a trustless network.


## Project description

The project is composed of 3 three parts.

The first and primary goal is an endogenous load balancer for a trustless p2p network. This point is crucial given that conventional load balancer designs rely on a central party that serves as a reverse proxy to all incoming requests.

The second goal is a fast and tamper-proof relay mechanism for RPC requests.

The third and more open-ended goal is to describe a pluggable incentive system that fits into the network economics.

## Specification (WIP)

- Endogenous load balancer
- Relay mechanism
- Incentive 


## Roadmap (WIP)

Phase 1:

- Preliminary design and implementation for the load balancer.
- Preliminary design and implementation for relay mechanism.
- Preliminary design and implementation for incentive mechanism.

Phase 2:
- Stress testing in substrate chain

Phase 3: 
- Testing on Rococo

## Possible challenges

- The complexity of p2p networking protocols and their implementation.
- Substrate RPC p2p networking implementation.
- Pluggable incentive mechanism research.
- Community acceptance and support.

## Goals of the project (WIP)

- Endogenous RPC request load balancer.
- Tamper-proof RPC request relay mechanism.
- Pluggable incentive system.

## Contributors and Authors 

- [cenwadike](https://github.com/cenwadike)

## Resources (WIP)
- [resource](#/link)

