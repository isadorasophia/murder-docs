<p align="center">
<img width="450" src="media/logo-8x-1.png" alt="Murder logo">
</p>

<h1 align="center">Murder Engine Documentation!</h1>

Welcome to the Murder Engine documentation source repository. This is our attempt to try to make the documentation process a little bit easier and reactive to [Murder](https://github.com/isadorasophia/murder) changes.

## 🍡 Updating .md files
We use [dotnet2md](https://github.com/isadorasophia/dotnet2md) to convert the C# metadata and XML documentation to markdown. So far, this is **Windows only**. The only reason is that I did not have the time yet to port the script to other machines.

Anyway, you just need to run:
1. Publish **Murder** with debug binaries
2. Run **dotnet2md** using your publish path, e.g.:
```ps1
.\tools\dotnet2md.ps1 -xmlPath <path-to-Murder-src>\bin\Release\net8.0\publish
```

## 🍭 Updating .html files
We use [mdbook](https://github.com/rust-lang/mdBook) for converting the markdown files to html. We also have a script for that.

1. After updating the .md files, run:
```ps1
.\tools\publish.ps1
```

If you want to test the changes _locally_, run:
```ps1
.\tools\publish.ps1 -action deploy
```
