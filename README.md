<a href="https://hapi.dev"><img src="https://raw.githubusercontent.com/hapijs/assets/master/images/family.png" width="180px" align="right" /></a>

# fork of [@hapi/formula](https://github.com/hapijs/formula) with conversion of the library to be usable with Deno

## Deno usage with original files

```
// @deno-types="https://cdn.jsdelivr.net/gh/hapijs/formula@3.0.2/lib/index.d.ts"
import {Parser} from "https://jspm.dev/@hapi/formula@3.0.2";
```

### Deno usage with files copied inside this repository

```
// @deno-types="https://raw.githubusercontent.com/77it/formula/master/lib/index.d.ts"
import {Parser} from "https://raw.githubusercontent.com/77it/formula/master/lib/formula.js";
```

## conversion steps

* converted with https://jspm.org
* that generated https://jspm.dev/@hapi/formula
* that pointed to https://jspm.dev/npm:@hapi/formula@3.0.2!cjs
* that is the file uploaded here (renamed to `formula.js`)


## Useful resources

- [Documentation and API](https://github.com/77it/formula/blob/master/API.md)

## Acknowledgements

Inspired by [**fparse**](https://github.com/bylexus/fparse), copyright 2012-2018 Alexander Schenkel <alex@alexi.ch>
