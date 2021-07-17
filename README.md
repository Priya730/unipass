# unipass
Node.js command line password generator

## Usage

Install dependencies

```
npm install
```

Run file

```
node index (options)
```

To create a symlink to run "unipass" from anywhere

```
npm link

# Now you can run
unipass (options)

# To remove symlink
npm unlink
```

## Options

| Short | Long              | Description                     |
| ----- | ----------------- | ------------------------------- |
| -l    | --length <number> | length of password (default: 8) |
| -s    | --save            | save password to passwords.txt  |
| -nn   | --no-numbers      | remove numbers                  |
| -ns   | --no-symbols      | remove symbols                  |
| -h    | --help            | display help for command        |
| -V    | --version         | Show the version                |
