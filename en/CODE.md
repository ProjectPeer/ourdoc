# General
For every language

## Indentation
Four spaces. Be careful to not use tab it's just four spaces.
```
// Good
block
    block
        block
            block
        ...

// Bad
block
    block
        block
            ...
```

[:arrow_left: back to summary](https://github.com/ProjectPeer/ourdoc/tree/master/en)

## Constants
Must be in UPPERCASE snake_case
```
FOOBAR  // <- this is a constant
FOO_BAR // <- this is a constant
Foo_BAR // <- this isn't a constant
foobar  // <- this isn't a constant
```

[:arrow_left: back to summary](https://github.com/ProjectPeer/ourdoc/tree/master/en)


## Variables
Must be un lowercase camelCase
```
foobar    // <- this is a variable
fooBar    // <- this is a variable
foor_bar  // <- this isn't a variable
Foobar    // <- this isn't a variable
```

[:arrow_left: back to summary](https://github.com/ProjectPeer/ourdoc/tree/master/en)

## Objects
Must be written in CamelCase
```
Foobar  // <- this is an object
FooBar  // <- this is an object
fooBar  // <- this isn't an object
Foo_Bar // <- this isn't an object
```

[:arrow_left: back to summary](https://github.com/ProjectPeer/ourdoc/tree/master/en)

## Functions and Methods
Must be written in lowercase camelCase. The block must be separated with a space.
```
// Bad
function a(){
}

// Good
function a() {
}
```

[:arrow_left: back to summary](https://github.com/ProjectPeer/ourdoc/tree/master/en)

## Assignment and Operations
Operators should always be spaced, except for parentheses.
```
a = 1 // Good
a = b + (1 - 2) // Good
a = b+1 // Bad
```

[:arrow_left: back to summary](https://github.com/ProjectPeer/ourdoc/tree/master/en)

## Blocks and ternary conditions
Inline blocks are allowed and recommended only if they are less than 100 characters (columns). Otherwise, write the conditions in blocks. Ternary conditions apply to this rule.
```
for(;;) sayHi() // Good
a = (isTrue()) ? 'yes' : 'no' // Good

// Good
if(thisFonctionIsReallyReallyLong() && thisIsAnotherReallyLongFunction()) {
  return true
} else {
  return false
}

// Bad, It's too much for an inline
if(thisFonctionIsReallyReallyLong() && thisIsAnotherReallyLongFunction()) return true
else return false

// Good
if(isTrue()) return true
else return false
```

[:arrow_left: back to summary](https://github.com/ProjectPeer/ourdoc/tree/master/en)

## Commentaries
Commentary on a line should not exceed more than 100 characters (columns), Otherwise, a commentary of blocks should be preferred.
```
// short com <- Good
// this is a very very very very very very very very very very very very very very very very very very very very long com <- Bad

/*
 * this is a very very very very very very very very very very
 * very very very very very very very very very very very very
 * very very very long com <- Good
 */
```
Never push commentary code. Code must be deleted.
```
// a = 1 <- must be deleted
```

[:arrow_left: back to summary](https://github.com/ProjectPeer/ourdoc/tree/master/en)
