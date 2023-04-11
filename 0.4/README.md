```mermaid
sequenceDiagram
      Browser->>+Server: Get https://studies.cs.helsinki.fi/exampleapp/notes
    Server-->>-Browser: HTML document
    Browser->>+Server: Get https://studies.cs.helsinki.fi/exampleapp/main.css
      Server-->>-Browser: The css file
    Browser->>+Server: Get https://studies.cs.helsinki.fi/exampleapp/main.js
       Server-->>-Browser: The JavaScript file
    Browser->>+Server: Get https://studies.cs.helsinki.fi/exampleapp/data.json
       Server-->>-Browser: New JSON data to render