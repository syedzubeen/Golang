package main

import (
	"fmt"
)

func treasureChest(from string) {
	for i := 1; i < 4; i++ {
		fmt.Println("Found "+from, "number", i)
	}
}

func main() {

	treasureChest("diamond")

	go treasureChest("ruby")
	
	fmt.Println("Found all the treasures !!")
}
