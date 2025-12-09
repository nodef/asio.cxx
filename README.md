Asio C++ Library; chriskohlhoff (2003).

Visit https://think-async.com/ or see packaged doc/index.html for API
documentation and a tutorial.


## Installation

Run:
```bash
$ npm i asio.cxx
```

And then include `asio.hpp` as follows:
```cxx
// main.cxx
#include "node_modules/asio.cxx/boost/asio.hpp"

int main() { /* ... */ }
```

And then compile with `clang++` or `g++` as usual.

```bash
$ clang++ main.cxx  # or, use g++
$ g++     main.cxx
```

You may also use a simpler approach:

```cxx
// main.cxx
#include <boost/asio.hpp>

int main() { /* ... */ }
```

If you add the path `node_modules/asio.cxx` to your compiler's include paths.

```bash
$ clang++ -I./node_modules/asio.cxx main.cxx  # or, use g++
$ g++     -I./node_modules/asio.cxx main.cxx
```

<br>
<br>


[![ORG](https://img.shields.io/badge/org-nodef-green?logo=Org)](https://nodef.github.io)
![](https://ga-beacon.deno.dev/G-RC63DPBH3P:SH3Eq-NoQ9mwgYeHWxu7cw/github.com/nodef/asio.cxx)
