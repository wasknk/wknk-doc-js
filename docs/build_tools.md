# Build tools of JS 


## Node Version Manager -- nvm

windows version download
https://github.com/coreybutler/nvm-windows/releases

```bash 
# see what versions and now using in local
nvm list

# downlowd newest 
nvm install node
# use newest
nvm use newest

# download version 
nvm install <version>
# use specific version 
nvm use <version>

# download and use lts
nvm install lts
nvm use lts
```


## ts-node as TypeScript execution environment for practice

```bash
pnpm init
pnpm install -D typescript ts-node @types/node
pnpm tsc --init
pnpm ts-node yourcode.ts
```