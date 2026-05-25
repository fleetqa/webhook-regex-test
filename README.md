# webhook-regex-test

Test repository for Fleet webhook regex pattern matching.

## Structure

- `test-1/` - nginx deployment, 2 replicas
- `test-2/` - nginx deployment, 3 replicas  
- `test-3/` - nginx deployment, 4 replicas

## Test

Modifies `test-1` replicas to trigger webhooks and verifies only the intended GitRepo updates.
