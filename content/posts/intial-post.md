+++
title = "GM Fabric OAuth 2.0"
description = "Easy integration for hard security"
date = 2017-10-06T15:47:22-04:00
draft = true
tags = [
    "go",
    "golang",
    "templates",
    "development",
]
categories = [
    "Development",
    "golang",
]
+++

## Introduction

Changing the code syntax highlighting to match Github's was rather difficult with this theme as it has limited highlighting classes, but now this theme looks fantastic.

```go
package main

import (
    "fmt"
    "net/http"
)

func main() {
    fmt.Println("Hello World!")

    // Create basic http server
    s := http.Server{
        Addr: "0.0.0.0:8080",
        Handler: mux,
    }

    s.ListenAndServe()
}
```
