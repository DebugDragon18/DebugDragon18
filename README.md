<h1 align="center">Hi 👋, I'm Rugved Narkar</h1>
<h3 align="center">Code. Learn. Build. Repeat.</h3>


```go
package main

import "fmt"


type Explorer struct {
	Name           string
	Role           string
	PrimaryStack   []string
	LearningFocus  string
	OpenSourceGoal string
	FunFact        string
    Reach me       string
}

func (e Explorer) SayHi() {
	fmt.Println("Hey there 👋")
	fmt.Printf("I'm %s.\n", e.Name)
	fmt.Println("I enjoy building reliable systems and contributing to open source.")
}

func main() {
	me := Explorer{
		Name:           "Rugved Narkar",
		Role:           "Golang Backend Developer",
		PrimaryStack:   []string{"Go", "MongoDB", "REST APIs"},
		LearningFocus:  "Distributed systems fundamentals, backend reliability, and secure API design in Go",
		OpenSourceGoal: "Contribute consistently to Go-based open-source projects and earn a GSoC opportunity by delivering reliable, well-reviewed code",
		FunFact:        "Practices Stoicism and applies its principles to learning, coding, and decision-making",
        Reach me :      "narkarrugved100@gmail.com"

	}

	me.SayHi()
}
