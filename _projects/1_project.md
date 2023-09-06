---
layout: page
title: Shared/KV Store
description: 
img: 
importance: 1
category: 
related_publications: 
---

• Implemented a sharded key/value store in Java, leveraging paxos as described in Robbert van Renesse’s paper
“Paxos Made Moderately Complex”, with modifications to designate nodes as replicas, leaders, and acceptors.

• Improved system efficiency by implementing key optimizations such as message batching, integration of the Raft
protocol, timers for handling message failures, and efficient sharding techniques.