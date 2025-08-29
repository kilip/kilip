```go
// main about me package
package main

import (
	"fmt"
	"universe/earth"
)

// ShowToTheWorld print to the world about me
func ShowToTheWorld(aboutMe earth.Programmer){
	fmt.Printf("Hello World: %+v", aboutMe)
}

// main show to the world about me
func main (){
    aboutMe := earth.Geek{
        Name: "Anthonius",
		Hobby: "coding, piano, movies",
        Language: earth.LanguageLevel{
            NativeTongue: "go, php, typescript",
			Limited: "c/c++, python",
			InBrewing: "rust",
        },
		Occupation: "Freelancer",
		Framework: "too many framework i can working with :-)",
		Email: "me at itstoni dot com"
		Website: "https://itstoni.com",
		Logs: "https://kilip.github.io/coding-logs"
    }

    ShowToTheWorld(aboutMe)
}
```
