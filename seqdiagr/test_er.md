```mermaid
erDiagram
  Product {
  	type name PK "Comment"
  }
  Customer {
  	type name PK "Comment"
  }
  Product ||-o| Customer : ""
```