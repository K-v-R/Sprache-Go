# Sprache-Go
Quellcode auf dem Weg Go zu erlernen
https://play.golang.org/
#####################################

package main

import (
	"fmt"
)

func main() {
	var zahl int
	fünfGrößerVier := 5 > 4

	zahl = 10

	fmt.Println("is it true?", true == !true)
	fmt.Println("5 + 5 = 10", 5+5 == 10)
	fmt.Println("5 + 5 = 10", 5+5 == zahl)
	fmt.Println(fünfGrößerVier)

	if zahl > 10 {
		fmt.Println("Die Zahl ist größer als der Wert 10")
	} else if zahl == 10 {
		fmt.Println("Die Zahl ist exakt 10")
	} else {
		fmt.Println("Die Zahl ist kleiner als 10")
	}

	fmt.Println("----------------")

	if zahl == 10 {
		fmt.Println("ZEHN")
	}

	for zähler := 1; zähler <= 10; zähler++ {
		fmt.Println(zähler)
	}
}
