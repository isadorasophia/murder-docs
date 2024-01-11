# FileHelper

**Namespace:** Murder.Serialization \
**Assembly:** Murder.dll

```csharp
public static class FileHelper
```

FileHelper which will do OS operations. This is system-agnostic.

### ⭐ Methods
#### DeleteDirectoryIfExists(String&)
```csharp
public bool DeleteDirectoryIfExists(String& path)
```

**Parameters** \
`path` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### DeleteFileIfExists(String&)
```csharp
public bool DeleteFileIfExists(String& path)
```

**Parameters** \
`path` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Exists(String&)
```csharp
public bool Exists(String& path)
```

**Parameters** \
`path` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### ExistsFromRelativePath(String&)
```csharp
public bool ExistsFromRelativePath(String& relativePath)
```

**Parameters** \
`relativePath` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### FileExists(String&)
```csharp
public bool FileExists(String& path)
```

**Parameters** \
`path` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### IsPathInsideOf(string, String[])
```csharp
public bool IsPathInsideOf(string path, String[] filterFolders)
```

**Parameters** \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`filterFolders` [string[]](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### GetOrCreateDirectory(String&)
```csharp
public DirectoryInfo GetOrCreateDirectory(String& path)
```

**Parameters** \
`path` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[DirectoryInfo](https://learn.microsoft.com/en-us/dotnet/api/System.IO.DirectoryInfo?view=net-7.0) \

#### GuidFromName(string)
```csharp
public Guid GuidFromName(string name)
```

**Parameters** \
`name` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

#### GetAllFilesInFolder(string, bool, String[])
```csharp
public IEnumerable<T> GetAllFilesInFolder(string path, bool recursive, String[] filters)
```

**Parameters** \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`recursive` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
`filters` [string[]](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \

#### GetAllFilesInFolder(string, string, bool)
```csharp
public IEnumerable<T> GetAllFilesInFolder(string path, string filter, bool recursive)
```

**Parameters** \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`filter` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`recursive` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

**Returns** \
[IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \

#### ListAllDirectories(string)
```csharp
public IEnumerable<T> ListAllDirectories(string path)
```

**Parameters** \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \

#### DirectoryDeepCopy(string, string)
```csharp
public int DirectoryDeepCopy(string sourceDirectoryPath, string destDirectoryPath)
```

Copies all files from <paramref name="sourceDirectoryPath" /> to <paramref name="destDirectoryPath" />.
            Do not delete existing files.

**Parameters** \
`sourceDirectoryPath` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
\
`destDirectoryPath` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
\

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Exceptions** \
[DirectoryNotFoundException](https://learn.microsoft.com/en-us/dotnet/api/System.IO.DirectoryNotFoundException?view=net-7.0) \
\
#### Normalize(string)
```csharp
public Object Normalize(string source)
```

Used to normalize file paths from different OS into the same output.

**Parameters** \
`source` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
\

**Returns** \
[Object](https://learn.microsoft.com/en-us/dotnet/api/System.Object?view=net-7.0) \
\

#### Clean(string)
```csharp
public ReadOnlySpan<T> Clean(string str)
```

**Parameters** \
`str` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[ReadOnlySpan\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1?view=net-7.0) \

#### ComputeHash(string)
```csharp
public string ComputeHash(string filePath)
```

Computes a file Hash to watch it for changes

**Parameters** \
`filePath` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### EscapePath(string)
```csharp
public string EscapePath(string path)
```

**Parameters** \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### ExtensionForOperatingSystem()
```csharp
public string ExtensionForOperatingSystem()
```

Returns the assembly extension for the target operating system.
            For example, if targeting Windows, this returns ".dll".

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
\

**Exceptions** \
[PlatformNotSupportedException](https://learn.microsoft.com/en-us/dotnet/api/System.PlatformNotSupportedException?view=net-7.0) \
\
#### GetPath(String[])
```csharp
public string GetPath(String[] paths)
```

Gets the rooted path from a relative one

**Parameters** \
`paths` [string[]](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
\

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
\

#### GetPathWithoutExtension(string)
```csharp
public string GetPathWithoutExtension(string path)
```

**Parameters** \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### RemoveExtension(string)
```csharp
public string RemoveExtension(string filePath)
```

Remove extension from a string.

**Parameters** \
`filePath` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### SaveSerialized(T, string, bool)
```csharp
public string SaveSerialized(T value, string path, bool isCompressed)
```

**Parameters** \
`value` [T](../../) \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`isCompressed` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### SaveSerializedFromRelativePath(T, String&)
```csharp
public string SaveSerializedFromRelativePath(T value, String& relativePath)
```

**Parameters** \
`value` [T](../../) \
`relativePath` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### DeserializeAsset(string)
```csharp
public T DeserializeAsset(string path)
```

**Parameters** \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[T](../../) \

#### DeserializeGeneric(string, bool)
```csharp
public T DeserializeGeneric(string path, bool warnOnErrors)
```

**Parameters** \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`warnOnErrors` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

**Returns** \
[T](../../) \

#### TryGetLastWrite(string)
```csharp
public T? TryGetLastWrite(string path)
```

This will iterate recursively over all files in <paramref name="path" /> and return
            the latest modified date.

**Parameters** \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \

#### SaveTextAsync(string, string)
```csharp
public Task SaveTextAsync(string fullpath, string content)
```

**Parameters** \
`fullpath` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`content` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[Task](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task?view=net-7.0) \

#### SaveSerializedAsync(T, string, bool)
```csharp
public ValueTask<TResult> SaveSerializedAsync(T value, string path, bool isCompressed)
```

**Parameters** \
`value` [T](../../) \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`isCompressed` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

**Returns** \
[ValueTask\<TResult\>](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.ValueTask-1?view=net-7.0) \

#### CreateDirectoryPathIfNotExists(string)
```csharp
public void CreateDirectoryPathIfNotExists(string filePath)
```

This will create a directory on the root of this <paramref name="filePath" />,
            if the directory is not available.

**Parameters** \
`filePath` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### DeleteContent(String&, bool)
```csharp
public void DeleteContent(String& fullpath, bool deleteRootFiles)
```

**Parameters** \
`fullpath` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`deleteRootFiles` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### OpenFolder(string)
```csharp
public void OpenFolder(string path)
```

**Parameters** \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### SaveText(String&, String&)
```csharp
public void SaveText(String& fullpath, String& content)
```

**Parameters** \
`fullpath` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`content` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### SaveTextFromRelativePath(String&, String&)
```csharp
public void SaveTextFromRelativePath(String& relativePath, String& content)
```

**Parameters** \
`relativePath` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`content` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \



⚡