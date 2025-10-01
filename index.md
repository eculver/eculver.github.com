### Hello, My Name is Evan

Requisite online identity links (as Go program ➜ Markdown):

```golang
package main

import "fmt"

func main() {
	links := map[string]string{
		"GitHub":   "https://github.com/eculver",
		"LinkedIn": "https://www.linkedin.com/in/eculver",
		"Twitter":  "https://twitter.com/evanculver",
		"Resume":   "https://bit.ly/evan-culver-public-resume",
	}
	for txt, href := range links {
		fmt.Printf("- [%s](%s)\n", txt, href)
	}
}

```
`-->`
- [GitHub](https://github.com/eculver)
- [LinkedIn](https://www.linkedin.com/in/eculver)
- [Twitter](https://twitter.com/evanculver)
- [Resume](https://bit.ly/evan-culver-public-resume)
