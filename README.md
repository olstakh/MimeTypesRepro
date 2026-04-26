Run `dotnet build` and observe **success**

Run `dotnet build --no-incremental` and observe **failure**

Run `dotnet build --no-incremental -f net10.0` and observe **success**

`MimeTypes` package (see [here](https://github.com/khellang/MimeTypes)) uses `TextTemplatingFileGenerator` to produce a `.cs`, templates are in `content files`.
