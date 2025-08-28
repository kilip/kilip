```go
package main

// main show to the world about me
func main (){

    aboutMe := Programmer{
        Name: "Anthonius",
        Language: []string{
            "typescript",
            "go",
            "php",
        },
    }

    fmt.Printf("Hello World %+v", aboutMe)
}
```
