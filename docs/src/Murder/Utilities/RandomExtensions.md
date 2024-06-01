# RandomExtensions

**Namespace:** Murder.Utilities \
**Assembly:** Murder.dll

```csharp
public static class RandomExtensions
```

### ⭐ Methods
#### FlipACoin(Random)
```csharp
public bool FlipACoin(Random random)
```

**Parameters** \
`random` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### TryWithChanceOf(Random, float)
```csharp
public bool TryWithChanceOf(Random random, float chance)
```

Flag a switch with a chance of <paramref name="chance" />.

**Parameters** \
`random` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \
\
`chance` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### TryWithChanceOf(Random, int)
```csharp
public bool TryWithChanceOf(Random random, int chance)
```

Flag a switch with a chance of <paramref name="chance" />%.

**Parameters** \
`random` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \
\
`chance` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
\

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### NextFloat(Random, float)
```csharp
public float NextFloat(Random r, float max)
```

**Parameters** \
`r` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \
`max` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### NextFloat(Random, float, float)
```csharp
public float NextFloat(Random r, float min, float max)
```

**Parameters** \
`r` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \
`min` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`max` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### NextFloat(Random)
```csharp
public float NextFloat(Random r)
```

Returns a float from 0f to 1f

**Parameters** \
`r` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### SmoothRandom(float, float)
```csharp
public float SmoothRandom(float seed, float smoothness)
```

**Parameters** \
`seed` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`smoothness` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### AnyOf(Random, IList<T>)
```csharp
public T AnyOf(Random r, IList<T> arr)
```

**Parameters** \
`r` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \
`arr` [IList\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1?view=net-7.0) \

**Returns** \
[T](../../) \

#### GetRandom(IList<T>, Random)
```csharp
public T GetRandom(IList<T> array, Random random)
```

**Parameters** \
`array` [IList\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1?view=net-7.0) \
`random` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \

**Returns** \
[T](../../) \

#### GetRandom(ImmutableArray<T>, Random)
```csharp
public T GetRandom(ImmutableArray<T> array, Random random)
```

**Parameters** \
`array` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
`random` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \

**Returns** \
[T](../../) \

#### GetRandomKey(IDictionary<TKey, TValue>, Random)
```csharp
public T GetRandomKey(IDictionary<TKey, TValue> dict, Random random)
```

**Parameters** \
`dict` [IDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IDictionary-2?view=net-7.0) \
`random` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \

**Returns** \
[T](../../) \

#### PopRandom(IList<T>, Random)
```csharp
public T PopRandom(IList<T> list, Random random)
```

**Parameters** \
`list` [IList\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1?view=net-7.0) \
`random` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \

**Returns** \
[T](../../) \

#### GetRandom(Random, T[], int)
```csharp
public T[] GetRandom(Random random, T[] array, int length)
```

**Parameters** \
`random` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \
`array` [T[]](../../) \
`length` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[T[]](../../) \

#### GetRandom(IDictionary<TKey, TValue>, Random)
```csharp
public U GetRandom(IDictionary<TKey, TValue> dict, Random random)
```

**Parameters** \
`dict` [IDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IDictionary-2?view=net-7.0) \
`random` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \

**Returns** \
[U](../../) \

#### PopRandom(Dictionary<TKey, TValue>, Random)
```csharp
public U PopRandom(Dictionary<TKey, TValue> dict, Random random)
```

**Parameters** \
`dict` [Dictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.Dictionary-2?view=net-7.0) \
`random` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \

**Returns** \
[U](../../) \

#### Direction(Random, float, float)
```csharp
public Vector2 Direction(Random r, float minAngle, float maxAngle)
```

This returns a vector one rotated from <paramref name="minAngle" /> to <paramref name="maxAngle" />.

**Parameters** \
`r` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \
`minAngle` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`maxAngle` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### DistributedDirection(Random, int, int, float, float)
```csharp
public Vector2 DistributedDirection(Random r, int currentStep, int totalSteps, float min, float max)
```

**Parameters** \
`r` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \
`currentStep` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`totalSteps` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`min` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`max` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### DistributedDirection(Random, int, int)
```csharp
public Vector2 DistributedDirection(Random r, int currentStep, int totalSteps)
```

**Parameters** \
`r` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \
`currentStep` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`totalSteps` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \



⚡