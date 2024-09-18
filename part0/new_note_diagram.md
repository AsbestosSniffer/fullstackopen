```mermaid
sequenceDiagram
	participant browser
	participant server
	
	browser->>server: POST form data: {note: "test1"}
	activate server
	server-->>browser: HTML document with URL redirect
	deactivate server
```
