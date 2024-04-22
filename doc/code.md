# Code Example

## Code Example 1

??? example "Example 1"

    ```bash title="run command"
    $ go run src/example_code1.go
    Nice example
    ```
    ```go
    --8<-- "src/example_code1.go"
    ```

## Code Example 2

??? example "Example 2"

    ```go
    package main

    func main() {
        type FuncType func(int, int) int
        var mapFunc = map[string]FuncType{}
    }
    ```
