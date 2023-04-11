```mermaid
sequenceDiagram
      Browser->>+Server: Get https://studies.cs.helsinki.fi/exampleapp/spa
    Server-->>-Browser: HTML document, the css file, the JavaScript file
    Browser->>+Server: JSON data
    Server-->>-Browser: New JSON data to render without reloading page
   