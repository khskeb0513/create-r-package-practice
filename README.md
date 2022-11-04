# create-r-package-practice

Imitate `sum()` function.

## Usage

```{r}
library(addnumbers)
add_func(1, 2, 3) # result: 6
```

## Installation

```{r}
library(devtools) # devtools required
install_github('khskeb0513/create-r-package-practice')
```

## API

### function: `add_func( ...: numeric[] )`

add multiple numbers from parameters
