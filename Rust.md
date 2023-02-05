## Parse command line input to variable
- ``io::stdin().read_line(&mut **[Variable]**).unwrap();``

## Clear output buffer
- ``io::stdout().flush().unwrap();``
- Use after ``print!``
- Requires ``std::io::{stdout, Write}``

## Return types
- ``fn something() -> u32``
- "``->``" points to return type for function

## Match case with strings
- use ``.as_str()``
- Example:
```rust
match stringthing.as_str() {
    "a" => println!("0"),
    "b" => println!("1"),
    "c" => println!("2"),
    _ => println!("something else!"),
}
```

## Constant string
- ``const VARIABLE_NAME: &str = "String"``
