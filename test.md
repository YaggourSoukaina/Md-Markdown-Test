
# Md-Markdown-Test

`render-md-mermaid` will pick up any Mermaid graph in Markdown files that is defined as:

![rendered image description](test/demo/to/image3.png)
<details>
  <summary>diagram source</summary>
  This details block is collapsed by default when viewed in GitHub. This hides the mermaid graph definition, while the rendered image
  linked above is shown. The details tag has to follow the image tag. (newlines allowed)

```mermaid
graph LR 
    A[Christmas] -->|Get money| B(Go shopping) 
    B --> C{Let me think} 
    C -->|One| D[Laptop] 
    C -->|Two| E[iPhone] 
    C -->|Three| F[fa:fa-car Car]
```   
  
</details>


