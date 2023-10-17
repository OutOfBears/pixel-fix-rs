
<div align="center">
	<h1 style="font-size: 6em">pixel-fix-rs</h1>
</div>

<div>&nbsp;</div>

<div align="center">
    <a href="https://github.com/Nexur/pixel-fix-rs/actions"><img src="https://github.com/Nexure/pixel-fix-rs/workflows/CI/badge.svg" alt="Actions status" /></a>
    <a href="https://crates.io/crates/pixel-fix"><img src="https://img.shields.io/crates/v/pixel-fix-rs.svg?label=latest%20release" alt="Latest version" /></a>
</div>

<hr />

**pixel-fix-rs** is a rust port of the popular utility **"Pixelfix"**. This utility is designed to change the colors of completely transparent pixels in an image to match the color of the nearest non-transparent pixel.

### More Information:
- You can find extra information at the original tools respository [here](https://github.com/Corecii/Transparent-Pixel-Fix/blob/master/README.md#more-info)


### Designed to be a quick drag-and-drop tool:
1. Make your images
2. Select them all and drag them on to the pixelfix executable. The pixelfix executable will overwrite the original images with fixed copies.
3. Make sure there were no errors and close the console window
4. Use or upload your images. Your images should now look fine when resized.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started


### Installing from Github
- Download the latest version from [here!](https://github.com/Nexure/pixel-fix-rs/releases/latest)

### Installing from crates

```shell
$ cargo install pixel-fix
```

### Building from source
```shell
$ git clone https://github.com/Nexure/pixel-fix-rs
$ cd pixel-fix-rs
$ cargo install --path .
```

## Usage


```shell
$ pixel-fix-rs [input_files_or_dirs] [-d]
```

- `input_files_or_dirs`: A list of files or directories to convert
- `-d`: Enables debug mode for the file output

### Examples

Running with only a single file
```shell
$ pixel-fix-rs input.png
```

Running with multiple files
```shell
$ pixel-fix-rs input1.png input2.png input3.png
```

Running with a directory
```shell
$ pixel-fix-rs input_directory
```

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature`.
3. Make your changes and commit them with meaningful messages.
4. Push your branch to your fork: `git push origin feature/your-feature`.
5. Create a pull request to the main repository.

## License

This project is licensed under the MIT - see the [LICENSE](LICENSE) file for details.
