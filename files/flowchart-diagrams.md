[Flowchart Diagram Syntax](https://mermaid.js.org/syntax/flowchart.html)

```mermaid
---
title: Flowchart Diagram Example
---
flowchart LR
  HOME(Home):::orangeBox
  A(Aaaa):::redBox
  B(Bbbb):::greenBox
  C(Cccc):::cyanBox
  D(Dddd):::yellowBox
  E((Eee)):::brownBox
  CLI("Client")
  SRV("External<br>Server")
%% Flows
  subgraph Server
    subgraph "Application"
      HOME --> A
      HOME --> C
      A --> B
      C --> D
      B <.-> E
      D <.-> E	  
    end
  end

  CLI <--> Server <--> SRV
%% Links Definitions
  click HOME "http://www.example.com" _blank
%% Style Definitions
  classDef redBox fill: #ff6666, stroke: #000, stroke-width: 2px
  classDef greenBox fill: #00ff00, stroke: #000, stroke-width: 2px
  classDef cyanBox fill: #00ffff, stroke: #000, stroke-width: 2px
  classDef yellowBox fill: #ffff00, stroke: #000, stroke-width: 2px
  classDef orangeBox  fill: #ffa500,stroke: #000, stroke-width:2px
  classDef brownBox  fill: peru,stroke: #000, stroke-width:2px
```