---
layout: default
shortname: Mermaid
name: Mermaid JS
type: Diagram
category: Documentation
tags: mermaid, javascript, diagram, documentation, architecture
---


<div>
  Here is one mermaid diagram:
  <div class="mermaid">
    graph TD
    A[Client] --> B[Load Balancer]
    B --> C[Server1]
    B --> D[Server2]
  </div>

  And here is another:
  <div class="mermaid">
    graph TD
    A[Client] -->|tcp_123| B(Load Balancer)
    B -->|tcp_456| C[Server1]
    B -->|tcp_456| D[Server2]
  </div>
</div>