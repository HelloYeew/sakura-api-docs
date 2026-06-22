This repository is part of the [🌸🗡️ Sakura Framework](https://github.com/HelloYeew/sakura) ecosystem.

---

# Sakura Framework API Documentation

This documentation provide an API documentation of [Sakura Framework](https://github.com/HelloYeew/sakura) based on XML comments in the source code for reference. For more detailed guides and tutorials will be coming soon.

## List of Sakura Framework Repositories available

- [Sakura Framework (Core)](https://github.com/HelloYeew/sakura)
- [Sakura Imaging (Image Processing Extension)](https://github.com/HelloYeew/sakura-imaging)
- [Sakura SPIRV](https://github.com/HelloYeew/sakura-spirv)

## Generating Documentation

This documentation is generated using [DocFX](https://dotnet.github.io/docfx/).

To build the documentation, clone the Sakura Framework repository and its extensions. The structure should look like this:

```
.
sakura/
sakura-imaging/
sakura-api-docs/
```

Then, navigate to the `sakura-api-docs` directory and run the following commands:

```
dotnet tool update -g docfx
docfx docfx.json --serve
```