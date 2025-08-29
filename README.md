```go
// main about me package
package main

import (
	"fmt"
	"universe/earth"
)

// main make about me appears to the world
func main() {
    aboutMe := earth.Geek{
        Name: "Anthonius",
		NickName: "toni",
		Hobby: "coding, piano, movies",
        Language: earth.LanguageLevel{
            NativeTongue: "go, php, typescript",
			Limited: "c/c++, python",
			InBrewing: "rust",
        },
		Occupation: "Freelancer",
		Framework: "too many framework i can working with :-)",
		Email: "me at itstoni dot com",
		Website: "https://itstoni.com",
		Logs: "https://kilip.github.io/coding-logs",
		CoolProjects: "please checkout my github pinned repositories.",
    }

    PrintToTheWorld(aboutMe)
}

// PrintToTheWorld ask compiler to print to the world about me
func PrintToTheWorld(aboutMe earth.Geek){
	fmt.Printf("Hello World: %+v", aboutMe)
}
```
