To Generate a random string of 64 characters, run the following command in your terminal:

```bash
node
require("crypto").randomBytes(64).toString("hex");
```
