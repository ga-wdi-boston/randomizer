# randomizer
Take in a text file, randomize the line order, and optionally group the lines

## Usage

```txt
Usage: randomize <file> ... [options]

Specific options:
    -g, --groups N                   Group lines into N groups
    -h, --help                       Prints this help
    -v, --version                    Show version
```

## Example

```txt
❯ ./randomize example.txt
grapes
strawberries
milk
eggs
bananas
bread
oranges
cereal
```

```txt
❯ ./randomize example.txt --groups 3
bananas
oranges
eggs

milk
cereal
grapes

bread
strawberries
```
