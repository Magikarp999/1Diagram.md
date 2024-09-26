# 1Diagram.md

## Losing Weight

```
flowchart TD
    A[Start] --> B{Need to lose weight?}
    B -->|Yes| C[burn more calories than you consume]
    C --> D[Review Progress]
    D --> B
    B ---->|No| E[End]
```