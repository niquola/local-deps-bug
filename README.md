```
clj -Spath
src:
local-deps-bug/a/../b/src
local-deps-bug/a/libs/c/src

# but should be

local-deps-bug/b/libs/c/src

# or

local-deps-bug/../b/libs/c/src
```
