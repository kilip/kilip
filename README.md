```go
package main

import (
	"fmt"
	"universe/earth"
)

func ShowToTheWorld(person earth.Programmer){
	fmt.Printf("Hello World: %+v", person)
}

// main show to the world about me
func main (){
    aboutMe := earth.Programmer{
        Name: "Anthonius",
        Language: earth.LanguageLevel{
            NativeTongue: "go, php, typescript",
			Limited: "c/c++, python",
			InBrewing: "rust",
        },
		Occupation: "Freelancer",
		Framework: "too many framework i can working with :-) ",
		Email: "me at itsoni dot com"
		Hobby: "coding, piano, movies"

    }

    ShowToTheWorld(aboutMe)
}
```
