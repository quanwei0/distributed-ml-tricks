# Tricks of Distributed Machine Learning

## Optimization Algorithms for ML

- GD
- SGD, SGD with momentum
- variance reduction (SAG, SAGA, SVRG, SARAH)
- adaptive gradient (AdaGrad, RMSProp, AdaDelta, Adam)
- zero-order algorithms

## Communication Topologies

### centralized network
(aka star network, client-server, agent-to-server)

- parallel SGD (FedSGD)
- local SGD (FedAvg)

### decentralized network 
(aka mesh network, peer-to-peer, agent-to-agent)

- decentralized SGD (gossip SGD)
- gradient tracking
- multiple gossip communication

### semi-decentralized network

- periodic global averaging

### hybrid network

## Combinations
