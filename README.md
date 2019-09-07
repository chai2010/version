# get go-app version

```go
package main

import (
	"fmt"

	"github.com/chai2010/version"
)

func main() {
	fmt.Println(version.GetVersion().JSONString())
	fmt.Println(version.GetVersionString())
}
```
