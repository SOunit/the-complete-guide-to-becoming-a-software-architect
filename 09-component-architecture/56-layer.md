# Layers

- Expose User Interface / API
  - UI - User Interface
  - SI - Service Interface
    - expose API
    - JSON Handling
    - Auth
- Execute Logic
  - Business Logic / BL
    - validation
    - enrichment
    - computations
- Save / Retrieve Data
  - Data Access Layer / DAL
    - connection handle
    - querying / saving data
    - transaction handling

# benefit of layers

- focused code
- modular component

# benefit of module

- if DAL layer is well module / independent
  - easy to change from SQL to NoSQL
  - no effect on other layers

# concept of layers

- code flow
  - access only to next layer
- loose coupled
  - dependency injection
- exception handling
  - layer encapsulate(keep) information to it's layer

# layer vs. tier

- layer

  - one component
  - single process
  - no network
  - share all computer resources

- tier
  - communicate with network / http
  - multiple independent component
