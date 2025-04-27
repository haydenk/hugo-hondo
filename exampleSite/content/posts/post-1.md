+++
title = 'Post 1'
date = 2023-01-15T09:00:00-07:00
draft = false
tags = ['red']
+++

Tempor proident minim aliquip reprehenderit dolor et ad anim Lorem duis sint eiusmod. Labore ut ea duis dolor. Incididunt consectetur proident qui occaecat incididunt do nisi Lorem. Tempor do laborum elit laboris excepteur eiusmod do. Eiusmod nisi excepteur ut amet pariatur adipisicing Lorem.

Occaecat nulla excepteur dolore excepteur duis eiusmod ullamco officia anim in voluptate ea occaecat officia. Cillum sint esse velit ea officia minim fugiat. Elit ea esse id aliquip pariatur cupidatat id duis minim incididunt ea ea. Anim ut duis sunt nisi. Culpa cillum sit voluptate voluptate eiusmod dolor. Enim nisi Lorem ipsum irure est excepteur voluptate eu in enim nisi. Nostrud ipsum Lorem anim sint labore consequat do.


Python Code
```python
# /path/to/file.py

def hello() -> str:
    return "Hello"
```

Go Code
```go
package main

import "fmt"

func main() {
    for i := 0; i < 3; i++ {
        fmt.Println("Value of i:", i)
    }
}
```

package.json
```json
{
  "scripts": {
    "build:css:compile": "sass ./app/assets/stylesheets/application.bootstrap.scss:./app/assets/builds/application.css ./app/assets/stylesheets/shopify.scss:./app/assets/builds/shopify.css --no-source-map --load-path=node_modules",
    "build:css:prefix": "postcss ./app/assets/builds/*.css --use=autoprefixer --dir=./app/assets/builds",
    "build:css": "bun run build:css:compile && bun run build:css:prefix",
    "watch:css": "nodemon --watch ./app/assets/stylesheets/ --ext scss --exec \"bun run build:css\"",
    "build": "bun bun.config.js"
  },
}
```