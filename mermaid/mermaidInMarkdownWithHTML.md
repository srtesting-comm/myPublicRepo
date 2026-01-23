The following are diagrams that are featured in the article ["Cause and Effect Diagrams"](https://rudolfolah.com/cause-and-effect-diagrams/).

### Mindmap

## MCPS: Software Development Project Causes
```mermaid
mindmap
root{{Software Development<br/>Project Problem}}
  (Method)
  (Code)
  (People)
  (Systems)
```

```mermaid
flowchart TD
  A["Start<br/><b>Request</b>"] --> B{"Valid?<br/><span style='font-size:12px'>checks</span>"}
  B -- "Yes<br/><i>OK</i>" --> C["Proceed<br/><span style='color:green'>Success</span>"]
  B -- "No<br/><span style='color:red'>Error</span>" --> D["Show message<br/><u>Try again</u>"]
  D --> A
```

