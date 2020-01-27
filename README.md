### 1. Create a bin directory

```
cd bin
mkdir bin
```

### 2. Export bin directory to PATH

```
export PATH=$PATH:/Users/<username>/bin
```

### 3. Create a script and make it executable

```
cd bin
touch example-script

'example-script'

#!/bin/bash
echo "This is an example script"

chmod u+x example-script
```
