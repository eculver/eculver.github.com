### Hello, My Name is Evan

This is my GitHub page. It's a placeholder for the time being. Requisite online identity links:

```golang
package main

import "fmt"

func main() {
	links := map[string]string{
		"GitHub":   "https://github.com/eculver",
		"LinkedIn": "https://www.linkedin.com/in/eculver",
		"Twitter":  "https://twitter.com/evanculver",
	}
	for txt, href := range links {
		fmt.Printf("- [%s](%s)\n", txt, href)
	}
}
```
->
- [GitHub](https://github.com/eculver)
- [LinkedIn](https://www.linkedin.com/in/eculver)
- [Twitter](https://twitter.com/evanculver)
