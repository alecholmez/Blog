+++
title = "Future Endeavors"
description = "Raw CSS styles for language specific syntax highlighting?"
date = 2017-10-06T15:47:22-04:00
draft = true
tags = [
    "go",
    "golang",
    "templates",
    "development"
]
categories = [
    "Development",
    "golang"
]
menu = [
    "Development"
]
+++

Changing the code syntax highlighting to match Github's was rather difficult with this theme as it has limited highlighting classes, but now this theme looks fantastic.

### Example:

```go
package main

import (
    "net/http"
)

func main() {

    // Create basic HTTP server
    s := http.Server{
        Addr: "0.0.0.0:8080",
        // Wrap our mux router in the middleware stack
        Handler: stack.Wrap(router),
    }

    // Start the server
    s.ListenAndServe()
}
```

Now that I've successfully changed the CSS styles for the language specific code highlighting to match Github's flavor, I feel this theme has become much more appealing. The code is easier to read, yet still loud enough that it draws the attention of the reader/developer. Next step is to integrate comments so I can get the feedback of my readers!

After the comments functionality, I need to organize the blog into categories. Currently everything is posted in chronological order and while that is certainly appealing and intuitive, I feel that not everyone is interested in everything, Ya get me?. Hence the need for logical separation throughout the blog without encroaching on the chronological ordering of the main post listing.
