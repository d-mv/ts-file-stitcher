# Transport stream files stitcher

Stitch together chunks of media streams

Minimal info required to start:

```bash
pnpm run start -s "file path to source folder"
```

Available options:

`-s` - source folder with *.ts files
`-t` - _optional_ target folder for output file; default - same as source
`-f` - _optional_ file name; default - 'output.ts'
`-o` - _optional_ overwrite target file if exists; default - crash on file present