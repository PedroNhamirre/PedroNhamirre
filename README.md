<p align="center">Design. Develop. Deploy. </p>



<div align="center">
    <img align="center" height="250" width="375" alt="" src="https://raw.githubusercontent.com/iampavangandhi/iampavangandhi/master/gifs/coder.gif" />
</div>

<p></p>

<div align="center">

<!--
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedronhamirre)
-->
[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=google-chrome&logoColor=white)](https://pedronhamirre.vercel.app/)
</div>

```go
package main

import "fmt"

type Developer struct {
	Name      string
	LinkedIn  string
	Website   string
	Email     string
	SkilledIn []string
}

func main() {
	me := Developer{
		Name:     "Pedro Nhamirre",
		LinkedIn: "https://www.linkedin.com/in/pedronhamirre",
		Website:  "https://www.pedronhamirre.tech",
		Email:    "pedrooliv62@gmail.com",
		SkilledIn: []string{
			"AI",
			"Docker",
			"Git",
			"GitHub",
			"HTML/CSS",
			"Java",
			"JavaScript",
			"Linux",
			"Next.js",
			"Node.js",
			"Python",
			"React",
			"RESTful APIs",
			"Software Architecture",
			"Spring Framework",
			"SQL",
			"TypeScript",
		},
	}

	fmt.Printf("Developer: %s\nStatus: %s\nSkills: %v\n", me.Name, me.Status, me.SkilledIn)
}
```
