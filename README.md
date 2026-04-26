Run `dotnet build` on a solution or a project and observe successful build
Run `dotnet build --no-incremental` and observe failure

Note: Changing `<TargetFrameworks>` to `<TargetFramework>` fixes the issue

`MimeTypes` package (see [here](https://github.com/khellang/MimeTypes)) uses `TextTemplatingFileGenerator` to produce a `.cs`, templates are in `content files`.