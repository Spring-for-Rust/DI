# dependency-inversion

## Requirements 

- Inject dependencies on 
  - struct  

### Examples

Struct 
```rust
struct ExampleService {
  #[autowired]
  example_repository: ExampleRepository
}
```

