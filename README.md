# deno_is_ssh

[![tag](https://img.shields.io/github/release/justjavac/deno_is_ssh)](https://github.com/justjavac/deno_is_ssh/releases)
[![Build Status](https://github.com/justjavac/deno_is_ssh/workflows/ci/badge.svg?branch=master)](https://github.com/justjavac/deno_is_ssh/actions)
[![license](https://img.shields.io/github/license/justjavac/deno_is_ssh)](https://github.com/justjavac/deno_is_ssh/blob/master/LICENSE)

Whether the process is running inside SSH.

**Requires the `--allow-env` flag.**

## Usage

```ts
import { isSSH, isSSHSync } from "https://deno.land/x/is_ssh/mod.ts";

await isSSH();
isSSHSync();
```

## License

[deno_is_ssh](https://github.com/justjavac/deno_is_ssh) is released under the MIT License. See the bundled [LICENSE](./LICENSE) file for details.
