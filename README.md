# githubrepo
import (
    "fmt"
)
func main() {
    var x int = 0
    for {
        var y int
        fmt.Printf("Geben Sie eine Zahl zum addieren ein: ", x)
        y, _ = fmt.Scanf("%d", &y)
        x = add(x, y)
        fmt.Println(x)
    }
}
func add(x, y int) int
{
    return x + y
}
