![[Ring Topology.jpg]]

**Positives**:
- Predictable access (for example, token passing)
- It's fair, every node will get a turn

**Negatives**:
- One break can stop the loop making some machines unable to access some down the line
- Adding/removing nodes can interrupt the ring bringing the network down momentarily 

**Use cases**:
- Legacy Token Ring; metro/transport rings (SONET/SDH).

**To add redundancy, add a second ring going the other way**
![[Dual Ring Topology.jpg]]
This way if there is a fault the network isn't halted and it also helps with having more efficient package transfers