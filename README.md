# Clamfig

## Features:
- Serialization and deserialization of dataclass objects
  - Compatible with JSON/YAML formats
  - Supports nested dataclasses
  - Serializes the following additional types:
    - bytes
    - Decimal
    - datetime
- Configuration file management using JSON or YAML format

## Future Work
- Add validation for deserialization from unreliable sources
- Expand beyond dataclasses to handle other frameworks that include runtime validation. 
  - Atom (https://github.com/nucleic/atom)
  - Pydantic (https://github.com/samuelcolvin/pydantic)

## Acknowledgements
- Some code inspired by https://github.com/codelv/atom-db
