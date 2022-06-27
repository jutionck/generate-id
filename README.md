# Generate ID

This package implementation uuid from https://github.com/google/uuid (this is still a simple example).

### Install
```
go get github.com/jutionck/generate-id
```

### Use
```go
import (
	"fmt"
	generateid "github.com/jutionck/generate-id"
)

func main() {
	fmt.Println(generateid.GenerateId())
}
```
