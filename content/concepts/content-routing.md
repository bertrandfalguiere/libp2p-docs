---
title: Content Routing
weight: 5
---

Content Routing is the process of finding [peerID(s)](https://docs.libp2p.io/concepts/peer-id/) of peer(s) providing a specific block identified by a CID (link).
Once we have a PeerID, we do Peer Routing (link) to contact them.

The Distributed Hash Table (DHT) is currently the only officially implemented (link to implementation) way of doing Peer Routing for now. More could be implemented in the future like Delegated Routing (where another node do it for you), trackers, topic-based pubsub, etc.

# DHT lookup

IPFS's DHT(link) is used both for Content Routing (finding peers having a piece of data) and Peer Routing (finding how to contact a peer thanks to its Peer ID). 




Please [refer to this issue](https://github.com/libp2p/docs/issues/23) to track the progress and make suggestions.
