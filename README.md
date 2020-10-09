<a href="https://hapi.dev"><img src="https://raw.githubusercontent.com/hapijs/assets/master/images/family.png" width="180px" align="right" /></a>

# fork of [@hapi/formula](https://github.com/sideway</formula) with conversion of the library to be usable with Deno

## Deno usage with original files

```
// @deno-types="https://raw.githubusercontent.com/sideway/formula/master/lib/index.d.ts"
import {Parser} from "https://jspm.dev/@hapi/formula";
```

### Deno usage with files copied inside this repository

```
// @deno-types="https://raw.githubusercontent.com/sideway/formula/master/lib/index.d.ts"
import {Parser} from "https://raw.githubusercontent.com/stefano77it/formula/master/lib/formula-3.0.0.js";
```

## conversion steps

* converted with https://jspm.org
* that generated https://jspm.dev/@hapi/formula
* that pointed to https://jspm.dev/npm:@hapi/formula@3.0.0!cjs
* that is the file uploaded here (renamed to `formula-3.0.0.js`)


## Useful resources

- [Documentation and API](https://github.com/stefano77it/formula/blob/master/API.md)

## Acknowledgements

Inspired by [**fparse**](https://github.com/bylexus/fparse), copyright 2012-2018 Alexander Schenkel <alex@alexi.ch>
