# Fill and Stroke Colors

```mermaid
flowchart TB
subgraph a
    direction TB
    lightgray:::lightgray
    lavender:::lavender
    aliceblue:::aliceblue
end
subgraph b
    direction TB
    lightcyan:::lightcyan
    honeydew:::honeydew
    lightyellow:::lightyellow
end
subgraph c
    direction TB
    cornsilk:::cornsilk
    bisque:::bisque
    mistyrose:::mistyrose
end
a -.- b -.- c
%% Styles
    classDef aliceblue fill:aliceblue,stroke:black,stroke-width:1px
    classDef bisque fill:bisque,stroke:black,stroke-width:1px
    classDef cornsilk fill:cornsilk,stroke:black,stroke-width:1px
    classDef honeydew fill:honeydew,stroke:black,stroke-width:1px
    classDef lavender fill:lavender,stroke:black,stroke-width:1px
    classDef lightcyan fill:lightcyan,stroke:black,stroke-width:1px
    classDef lightgray fill:lightgray,stroke:black,stroke-width:1px
    classDef lightyellow fill:lightyellow,stroke:black,stroke-width:1px
    classDef mistyrose fill:mistyrose,stroke:black,stroke-width:1px
```

---

```mermaid
flowchart TB
subgraph a
    direction TB
    gray:::gray
    yellow:::yellow
    gold:::gold
    orange:::orange
    orangeDark:::orangeDark
end
subgraph b
    direction TB
    salmon:::salmon
    pink:::pink
    red:::red
    magenta:::magenta
    violet:::violet
end
subgraph c
    direction TB
    blue:::blue
    cyan:::cyan
    lime:::lime
    green:::green
    olive:::olive
end
subgraph d
    direction TB
    sienna:::sienna
    brown:::brown
    chocolate:::chocolate
    redBrown:::redBrown
    black:::black
end
a -.- b -.- c -.- d
%% Styles
    classDef black stroke:black,stroke-width:10px
    classDef blue stroke:blue,stroke-width:10px
    classDef brown stroke:saddlebrown,stroke-width:10px
    classDef chocolate stroke:chocolate,stroke-width:10px
    classDef cyan stroke:cyan,stroke-width:10px
    classDef gold stroke:gold,stroke-width:10px
    classDef gray stroke:gray,stroke-width:10px
    classDef green stroke:green,stroke-width:10px
    classDef lime stroke:lime,stroke-width:10px
    classDef magenta stroke:magenta,stroke-width:10px
    classDef olive stroke:olive,stroke-width:10px
    classDef orange stroke:orange,stroke-width:10px
    classDef orangeDark stroke:#FF5C00,stroke-width:10px
    classDef pink stroke:pink,stroke-width:10px
    classDef red stroke:red,stroke-width:10px
    classDef redBrown stroke:brown,stroke-width:10px
    classDef salmon stroke:salmon,stroke-width:10px
    classDef sienna stroke:sienna,stroke-width:10px
    classDef violet stroke:violet,stroke-width:10px
    classDef yellow stroke:yellow,stroke-width:10px
```

---

```mermaid
flowchart TB
subgraph a
    direction TB
    1((1st)):::one
    2((2nd)):::two
    3((3th)):::three
end
subgraph b
    direction TB
    4((4th)):::four
    5((5th)):::five
    6((6th)):::six
end
subgraph c
    direction TB
    7((7th)):::seven
    8((8th)):::eight
    9((9th)):::nine
end
a -.- b -.- c
%% Styles
    classDef one fill:#F4E1E4,stroke:#000000,stroke-width:1px
    classDef two fill:#FFCB33,stroke:#000000,stroke-width:1px
    classDef three fill:#FCDAD7,stroke:#000000,stroke-width:1px
    classDef four fill:#C3F7F7,stroke:#000000,stroke-width:1px
    classDef five fill:#8FB7DC,stroke:#000000,stroke-width:1px
    classDef six fill:#B69592,stroke:#000000,stroke-width:1px
    classDef seven fill:#FF8888,stroke:#000000,stroke-width:1px
    classDef eight fill:#88FF88,stroke:#000000,stroke-width:1px
    classDef nine fill:#8888FF,stroke:#000000,stroke-width:1px
```

---