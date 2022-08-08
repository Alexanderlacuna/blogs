##  Quick intro to rust language

### Genesis

Graydon Hoare developed the rust language while working
at mozilla

What rust is all about?

The rust language is a statically fast language
and can be compared to other  languages like c++

what really differentiate  rust

rust langauge primarily goal is safety with speed
this is achieved by the  strict but helpful compiler  more like



### rust syntax

to define a variable

``` rust
let name = "The rust language"

```

breaking the syntax above seem familiar to other languages
to define a variable we use the key **let** 
the followed by the identifier/variable being name,
*the rust language* being the value

### rust and immutability

all variables defined are immutable by default key feature above rust

hence why code below would fail


```rust
let name  =  "the RusT language";

name = "the rust language";

```

**mut** keyword is used to mark a  variable as mutable

for example 

``` rust

let mut name = "rust";

name = "the Rust"

```

### type inferencing

the rust compiler is so smart if you define a variable
with a value it can automatically inference the type
hence we don't to explicitly define the types in call
cases

To define type on the above
we write

``` rust

let mut name:&str = "rust";

```


### declaring variables with const

const variable live entirely through the program  and are 
always immutable 

to declare const variables we write

``` rust
const NAME:&str = "USERNAME"
```

const type must be explicitly defined





