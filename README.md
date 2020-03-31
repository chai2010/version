- *赞助 BTC: 1Cbd6oGAUUyBi7X7MaR4np4nTmQZXVgkCW*
- *赞助 ETH: 0x623A3C3a72186A6336C79b18Ac1eD36e1c71A8a6*
- *Go语言付费QQ群: 1055927514*

----

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
