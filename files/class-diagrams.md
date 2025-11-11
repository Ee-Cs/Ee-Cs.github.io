(Class Diagram Syntax)[https://mermaid.js.org/syntax/classDiagram.html]

```mermaid
---
title: Class Diagram Example
---
classDiagram
class Aaa {
  +number id
  +string name
  +AaaStatus aaaStatus
  +Bbb[] bbbArr
}

class Bbb {
  +number id
  +number aaaId
  +string name
  +BbbStatus bbbStatus
}

class AaaStatus {
  <<enumeration>>
  🟣 +A1 = "A One"
  🟡 +A2 = "A Two"
}

class BbbStatus {
  <<enumeration>>
  🟣 +B1 = "B One"
  🟡 +B2 = "B Two"
}

Aaa "1" o-- "*" Bbb : bbbArr
AaaStatus <|.. Aaa : aaaStatus
BbbStatus <|.. Bbb : bbbStatus
```
