# Hello World

We created a sample hello world app on [Hello Murder](https://github.com/isadorasophia/hellomurder). We should cover more on that soon. 

You can take a peek at [IMurderGame](../Murder/IMurderGame.html) on tweaking basic functionality into your game, but a lot of things should be ready to go from the editor project.

---

## Setting Up a New FNA Game with Murder from Scratch

### 1. Create a new FNA game project

```bash
mkdir MyGame && cd MyGame
dotnet new sln --name MyGame       # create a new solution
dotnet new console --name MyGame   # create a console (game) project
dotnet sln add MyGame/MyGame.csproj
```

Edit `MyGame/MyGame.csproj`:

```xml
<PropertyGroup>
  <TargetFramework>net8.0</TargetFramework>
  <OutputType>WinExe</OutputType>
</PropertyGroup>
```

Add FNA:

```bash
git submodule add https://github.com/FNA-XNA/FNA.git libs/FNA
```

Then reference `FNA.Core.csproj` in your `.csproj`:

```xml
<ItemGroup>
  <ProjectReference Include="..\libs\FNA\FNA.Core.csproj" />
</ItemGroup>
```

### 2. Add a submodule for Murder

```bash
git submodule add https://github.com/isadorasophia/murder.git libs/murder
git submodule update --init --recursive
```

### 3. Reference Murder in your games `.csproj`

In your game’s `.csproj`, add:

```xml
<ItemGroup>
  <ProjectReference Include="..\libs\murder\src\Murder\Murder.csproj" />
</ItemGroup>
```

### 4. Create an editor project for your game

```bash
dotnet new console --name MyGame.Editor
dotnet sln add MyGame.Editor/MyGame.Editor.csproj
```

Then update `MyGame.Editor.csproj`:

```xml
<ItemGroup>
  <ProjectReference Include="..\libs\murder\src\Murder\Murder.csproj" />
  <ProjectReference Include="..\libs\murder\src\Murder.Editor\Murder.Editor.csproj" />
</ItemGroup>
```

Build and run:

```bash
cd MyGame.Editor
dotnet build
dotnet run
```
