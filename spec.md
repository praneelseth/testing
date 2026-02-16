# JSON Parser Implementation

## Objective
Build a robust JSON parser from scratch in Python that can parse valid JSON strings and handle errors gracefully.

## Requirements

### Core Functionality
1. **Parse JSON strings** into Python objects (dict, list, str, int, float, bool, None)
2. **Support all JSON data types**:
   - Objects: `{"key": "value"}`
   - Arrays: `[1, 2, 3]`
   - Strings: `"hello"`
   - Numbers: `123`, `45.67`, `-89`, `1.23e-4`
   - Booleans: `true`, `false`
   - Null: `null`
3. **Handle nested structures** (objects within arrays, arrays within objects, etc.)
4. **Handle escaped characters** in strings (`\"`, `\\`, `\n`, `\t`, etc.)
5. **Raise appropriate errors** for invalid JSON

### Implementation Details
- Implement a **Tokenizer** class that breaks JSON string into tokens
- Implement a **Parser** class that builds Python objects from tokens
- Use proper error handling with descriptive error messages
- Follow Python best practices and coding standards

### Test Requirements
- Write comprehensive pytest tests covering:
  - Valid JSON parsing (objects, arrays, primitives)
  - Nested structures
  - Edge cases (empty objects/arrays, whitespace handling)
  - Error cases (invalid syntax, unclosed brackets, etc.)
- All tests must pass

### Deliverables
1. `src/json_parser.py` - Main parser implementation with Tokenizer and Parser classes
2. `tests/test_json_parser.py` - Comprehensive test suite
3. `README.md` - Documentation with usage examples
4. All tests passing

## Success Criteria
- Parser correctly handles all JSON data types
- Nested structures are parsed correctly
- Error handling is robust with clear error messages
- Test coverage is comprehensive (aim for >90%)
- Code is clean, well-documented, and follows Python conventions
