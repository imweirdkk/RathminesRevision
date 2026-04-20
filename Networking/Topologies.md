# Choosing the right design

**Cost:** Consider the budget for the cables, hardware, labour, and long-term maintenance cost

**Scalability:** The design needs to allow future growth without it being too challenging to adapt

**Reliability:** The chose topology must match the organisation's tolerance for network downtime

**Supportability:** Troubleshooting, and maintenance should be practical for the IT staff

## Physical

- How things are *actually connected*: where cables, wireless APs and devices sit and how they link together

## Logical

- How data *moves*: the path frames/packets take at Layer 2/3 (who talks to whom, and in what order)

## Comparison of basic topologies

| Type                                   | Cost     | Scalability | Fault Tolerance               | Performace      |
| -------------------------------------- | -------- | ----------- | ----------------------------- | --------------- |
| [[Bus Topology\|Bus]]                  | Low      | Low         | Low                           | Low/Medium      |
| [[Ring Topology\|Ring]]                | Medium   | Low/Medium  | Medium (with dual ring)       | Predictable     |
| [[Star Topology\|Star]]                | Medium   | High        | Medium (add redundancy)       | High (switched) |
| [[Mesh Topology\|Mesh]]                | High     | Medium      | High                          | High            |
| [[Tree (Hierarchical) Topology\|Tree]] | Medium   | High        | Medium/High (with redundancy) | High            |
| [[Hybrid Topology\|Hybrid]]            | Variable | High        | High (if well designed)       | High            |
