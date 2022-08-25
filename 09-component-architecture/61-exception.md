# best practice #1

- catch exception only if you have something to do
  - if not, just throw error to central exception handling mechanisms
    - write error to log by framework
  - good to catch
    - rollback transaction
    - retry
    - wrap the exception
      - to hide detail and pass error to another layer

# best practice #2

- catch specific exception
  - SQLException for database error
- if you catch general error, the error type can be different than you expect

# best practice #3

- use try / catch to smallest chunk of code
