# vueli-cli
> CLI tool for vueli

## Installation ##
``` bash
$ npm install -g vueli-cli
```

## Usage ##
Below is an overview about the commands you can use:

### New project ###
For initializing a new project, use the following command:
``` bash
$ vueli new <project-name>
```

### Scaffolding ###
#### Component ####
For scaffolding a component, use the following command:
``` bash
$ vueli make:component <component-name>

# Use -s or --split if you want to use seperate files instead of a single .vue-file.
$ vueli make:component <component-name> -s
```

#### Layout ####
For scaffolding a layout, use the following command:
``` bash
$ vueli make:layout <layout-name>

# Use -s or --split if you want to use seperate files instead of a single .vue-file.
$ vueli make:layout <layout-name> -s
```

#### Mixin ####
For scaffolding a mixin, use the following command:
``` bash
$ vueli make:mixin <mixin-name>
```

#### Page ####
For scaffolding a page, use the following command:
``` bash
$ vueli make:page <page-name>

# Use -s or --split if you want to use seperate files instead of a single .vue-file.
$ vueli make:page <page-name> -s
```

#### Transformer ####
For scaffolding a transformer, use the following command:
``` bash
$ vueli make:transformer <transformer-name>
```

#### Vuex Module ####
For scaffolding a Vuex module, use the following command:
``` bash
$ vueli make:vuex-module <module-name>
```

## License ##

The MIT License (MIT)

Copyright (c) 2016 vueli

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
