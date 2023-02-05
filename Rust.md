## Parse command line input to variable
- ``io::stdin().read_line(&mut **[Variable]**).unwrap();``

## Clear output buffer
- ``io::stdout().flush().unwrap();``
- Use after ``print!``
- Requires ``std::io::{stdout, Write}``

## Return types
- ``fn something() -> u32``
- "->" points to return type for function
