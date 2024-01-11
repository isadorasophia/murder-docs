# Chord

**Namespace:** Murder.Core.Input \
**Assembly:** Murder.dll

```csharp
public sealed class Chord
```

Represents a sequence of Key with optional modifiers.

### ⭐ Constructors
```csharp
public Chord(Keys key, Keys[] modifiers)
```

Represents a sequence of Key with optional modifiers.

**Parameters** \
`key` [Keys](https://docs.monogame.net/api/Microsoft.Xna.Framework.Input.Keys.html) \
\
`modifiers` [Keys[]](https://docs.monogame.net/api/Microsoft.Xna.Framework.Input.Keys.html) \
\

### ⭐ Properties
#### Key
```csharp
public Keys Key { get; }
```

The key that needs to be pressed to trigger this chord.

**Returns** \
[Keys](https://docs.monogame.net/api/Microsoft.Xna.Framework.Input.Keys.html) \
#### Modifiers
```csharp
public Keys[] Modifiers { get; }
```

A list of optional modifiers that need to be pressed along with [Chord.Key](../../../Murder/Core/Input/Chord.html#key) in order to trigger this chord.

**Returns** \
[Keys[]](https://docs.monogame.net/api/Microsoft.Xna.Framework.Input.Keys.html) \
### ⭐ Methods
#### ToString()
```csharp
public virtual string ToString()
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \



⚡