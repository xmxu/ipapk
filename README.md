<!--
 * Author: xuxm
 * Date: 2020-12-09 17:42:16
 * Copyright 2020 xuxm
-->
# ipapk
ipa or apk parser written in golang, aims to extract app information <br />
fork from : [https://github.com/phinexdaz/ipapk](https://github.com/phinexdaz/ipapk) upgrade  to module





[![Build Status](https://travis-ci.org/phinexdaz/ipapk.svg?branch=master)](https://travis-ci.org/phinexdaz/ipapk)

## INSTALL
	$ go get github.com/xmxu/ipapk
  
## USAGE
```go
package main

import (
	"fmt"
	"github.com/xmxu/ipapk"
)

func main() {
	apk, _ := ipapk.NewAppParser("test.apk")
	fmt.Println(apk)
}
```

