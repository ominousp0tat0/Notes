## Intrinsic Functions
* Built-in functions that help you manage the stack

### Join
* Appends a set of values into a single value

JSON syntax and example:
```json
{"Fn::Join":["delimiter",[comma-delimited list of values]]}

{"Fn::Join" : [ ":", [ "a", "b", "c" ] ]}
```
YAML:
```yaml
!Join [delimiter,[comma-delimited list of values]]

!Join [ ":", [ a, b, c ] ]
```

* Both of the above would output the value "a:b:c"