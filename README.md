github-forms
============
Using [json-editor/json-editor: JSON Schema Based Editor](https://github.com/json-editor/json-editor)

### Notes
- Buggy (`oneOf`)
    - therefore not to be used for complex UI
- prefer compile-time UI generation

### TODOs
- [ ] submit button should not be created at page initialization
- [ ] Cookies

### Sample input
```json
{
    "repo": "myrepo",
    "key": "mykey",
    "schema": "{\"$schema\": \"http://json-schema.org/draft-04/schema#\", \"type\": \"object\", \"properties\": { \"name\": { \"type\": \"string\" }, \"age\": { \"type\": \"integer\" }, \"role\": { \"type\": \"string\", \"enum\": [ \"student\", \"professor\" ] } }, \"required\": [\"name\",\"age\",\"role\"] }" 
}
```
### Implementations
- [Implementations | JSON Schema](https://json-schema.org/implementations.html)

### Tools
- [Free Online JSON to JSON Schema Converter](https://www.liquid-technologies.com/online-json-to-schema-converter)
- [JSON Editor Online: JSON editor, JSON formatter, query JSON](https://jsoneditoronline.org/)
- [Free Online JSON Escape / Unescape Tool - FreeFormatter.com](https://www.freeformatter.com/json-escape.html)
- [Json-Editor Interactive Playground](https://pmk65.github.io/jedemov2/dist/demo.html)

### Similar projects
- [eclipsesource/jsonforms: Customizable JSON Schema-based forms with React, Angular and Vue support out of the box.](https://github.com/eclipsesource/jsonforms)
- [brutusin/json-forms: JSON Schema to HTML form generator, supporting dynamic subschemas (on the fly resolution). Extensible and customizable library with zero dependencies. Bootstrap add-ons provided](https://github.com/brutusin/json-forms)
- [jsonform/jsonform: Build forms from JSON Schema. Easily template-able. Compatible with Bootstrap 3 out of the box.](https://github.com/jsonform/jsonform)