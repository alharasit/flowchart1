```mermaid
flowchart TD
  A["User requests access to CMMS/AMS"] --> B["Verify role & required access level"]
  B --> C{"Approved?"}
  C -- "No" --> D["Reject & notify requester"]
  C -- "Yes" --> E["Grant access & assign privileges"]
  E --> F["Monitor data usage & logs"]
  F --> G["Quarterly access review"]
  G --> H["Revoke / update rights as needed"]
