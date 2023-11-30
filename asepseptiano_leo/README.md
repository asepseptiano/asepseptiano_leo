# asepseptiano_leo.aleo

```
program multiply_numbers.aleo {
    // Function to multiply two numbers.
    transition multiply_numbers(number1: u32, number2: u32) -> u32 {
        return number1 * number2;
    }
}

```
```
leo run multiply_numbers 3u32 5u32
```
