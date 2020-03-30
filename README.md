# CyberChef

CyberChef is a "Swiss Army Knife" data analysis tool that allows users to quickly process data with "recipes" without having to write a single purpose script. Recipes are composed of a series of operations, with tools for encoding and decoding, encryption, parsing, logic, compression and decompression, media handling, forensics, and more.

You can find more at it's [GitHub repository](https://github.com/gchq/cyberchef). This is a port of CyberChef to get it to run on [Sandstorm](https://sandstorm.io/).

## Working with this port

In order to build or fork this port, you must have `vagrant-spk` installed. First, clone the repository with 

```bash
git clone --recurse-submodules https://github.com/zdb999/cyberchef-sandstorm
```

Then run:

```bash
vagrant-spk vm up
vagrant-spk dev
```

## Contributing

Please report any issues or concerns in the GitHub issues. While this should be a relatively low-maintenance port, pull requests are welcome.

## License

Like the original CyberChef, this is licensed un the Apache 2.0 license.