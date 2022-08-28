```mermaid
erDiagram

users ||--o{ comments: ""

users {
  string name
  string email
  integer age
}

comments {
  bigint user_id
  string text
  datetime created_at
  datetime updated_at
}



```
