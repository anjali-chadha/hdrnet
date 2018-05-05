## Build Process:

Performed a few changes in the tensorflow code to make the build work.
1. Replace "cuda/include/cuda.h" with "cuda.h" if error is thrown for a particular file.
2. For errors related to "nync.h", change the file location to "external/nsync/public/nsync.h"

### Current status:
*py.test test* still failing
