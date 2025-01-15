# neptun

app to help me manage dot files and share them between my machines

## Instalation

```bash
git clone
cd neptun
cargo build --release
```

## Usage

```bash
neptun --help // to see all commands
neptun init // to initialize the neptun folder
neptun add <file> // to add a file to the neptun folder
neptun remove <file> // to remove a file from the neptun folder
neptun list // to list all files in the neptun folder
neptun push  // to push the files to the remote
neptun pull // to pull the files from the remote
```

# Configuration

## Environment variables

- `NEPTUN_REMOTE` - the remote to push and pull the files from
- `NEPTUN_FOLDER` - the folder where the files will be stored
- `NEPTUN_BRANCH` - the branch to push and pull the files from