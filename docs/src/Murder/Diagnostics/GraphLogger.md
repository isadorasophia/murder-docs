# GraphLogger

**Namespace:** Murder.Diagnostics \
**Assembly:** Murder.dll

```csharp
public class GraphLogger
```

Implement this for plotting graphs into the debug system.

### ⭐ Constructors
```csharp
public GraphLogger()
```

### ⭐ Methods
#### ClearAllGraphs()
```csharp
public virtual void ClearAllGraphs()
```

#### ClearGraph(string)
```csharp
public virtual void ClearGraph(string callerFilePath)
```

**Parameters** \
`callerFilePath` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### PlotGraph(float, int, string)
```csharp
public virtual void PlotGraph(float value, int max, string callerFilePath)
```

**Parameters** \
`value` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`max` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`callerFilePath` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### PlotGraph(float, string)
```csharp
public virtual void PlotGraph(float value, string callerFilePath)
```

**Parameters** \
`value` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`callerFilePath` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \



⚡