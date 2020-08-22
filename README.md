# list-builtin-packages

create a map of golang's builtin package paths except internal prefixed packages.

output:

```go
var builtinPackages = map[string]interface{}{
	"archive/tar": struct{}{},
	"archive/zip": struct{}{},
	"bufio": struct{}{},
...
```
