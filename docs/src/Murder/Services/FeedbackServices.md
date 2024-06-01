# FeedbackServices

**Namespace:** Murder.Services \
**Assembly:** Murder.dll

```csharp
public static class FeedbackServices
```

### ⭐ Methods
#### SendFeedbackAsync(string, bool)
```csharp
public Task SendFeedbackAsync(string message, bool sendLog)
```

**Parameters** \
`message` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`sendLog` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

**Returns** \
[Task](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task?view=net-7.0) \

#### SendFeedbackAsync(string, string, FileWrapper[])
```csharp
public Task SendFeedbackAsync(string url, string message, FileWrapper[] files)
```

**Parameters** \
`url` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`message` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`files` [FileWrapper[]](../../Murder/Services/FileWrapper.html) \

**Returns** \
[Task](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task?view=net-7.0) \

#### SendSaveDataFeedbackAsync(string)
```csharp
public Task<TResult> SendSaveDataFeedbackAsync(string message)
```

**Parameters** \
`message` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[Task\<TResult\>](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task-1?view=net-7.0) \

#### TryZipActiveSaveAsync()
```csharp
public Task<TResult> TryZipActiveSaveAsync()
```

**Returns** \
[Task\<TResult\>](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task-1?view=net-7.0) \



⚡