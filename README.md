# pixel-text-encoder

A C program that converts text files into a pixel grid using $Y'C_BC_R$ colour encoding.

## Project Goals
- Read text files
- Convert text into a binary representation
- Encode data into pixel values
- Represent pixels using $Y'C_BC_R$ colour spaces
- Investigate chroma subsampling and pixel density

## How it works

The program converts the input file into binary data and maps the resulting bits onto a pixel grid.

Each pixel contains $Y'$ (luma), $C_B$ (blue difference chroma) and $C_R$ (red difference chroma). 

[More technical information](docs/technical_doc.md)


## Development Environment

- GitHub
- GitHub Codespaces
- C23
- gcc

## Project Structure

```text
pixel-text-encoder/
|
|--- docs/
|    |---res/
|    |   |___...
|    |
|    |---workd_diary.md
|    |---literature.md
|    |___technical_doc.md
|
|--- input/
|
|--- output/
|
|--- src/
|    |---main.c   
|    |---colour.c   
|    |---colour.
|    |---encoder.c   
|    |---encoder.h
|    |---file_reader.c   
|    |---file_reader.h
|    |---pixel_maker.c   
|____|___pixel_maker.h
```

## Build

<h1><p style = "color: #FF00FF";>REMINDER: when finished</p></h1>

## Documentation

- [Learning Journal](docs/workd_diary.md)
- [Technical Documentation](docs/technical_doc.md)
- [Literature](docs/literature.md)



