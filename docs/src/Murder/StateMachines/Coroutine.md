# Coroutine

**Namespace:** Murder.StateMachines \
**Assembly:** Murder.dll

```csharp
public class Coroutine : StateMachine
```

This CANNOT and WONT be serialized it is just a bad idea. Remember, we can't (or don't want to) serialize lambdas.

**Implements:** _[StateMachine](../../Bang/StateMachines/StateMachine.html)_

### ⭐ Constructors
```csharp
public Coroutine()
```

```csharp
public Coroutine(IEnumerator<T> routine)
```

**Parameters** \
`routine` [IEnumerator\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerator-1?view=net-7.0) \

### ⭐ Properties
#### Entity
```csharp
protected Entity Entity;
```

**Returns** \
[Entity](../../Bang/Entities/Entity.html) \
#### Name
```csharp
public string Name { get; }
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### PersistStateOnSave
```csharp
protected virtual bool PersistStateOnSave { get; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### World
```csharp
protected World World;
```

**Returns** \
[World](../../Bang/World.html) \
### ⭐ Methods
#### OnMessage(IMessage)
```csharp
protected virtual void OnMessage(IMessage message)
```

**Parameters** \
`message` [IMessage](../../Bang/Components/IMessage.html) \

#### OnStart()
```csharp
protected virtual void OnStart()
```

#### Transition(Func<TResult>)
```csharp
protected virtual void Transition(Func<TResult> routine)
```

**Parameters** \
`routine` [Func\<TResult\>](https://learn.microsoft.com/en-us/dotnet/api/System.Func-1?view=net-7.0) \

#### GoTo(Func<TResult>)
```csharp
protected virtual Wait GoTo(Func<TResult> routine)
```

**Parameters** \
`routine` [Func\<TResult\>](https://learn.microsoft.com/en-us/dotnet/api/System.Func-1?view=net-7.0) \

**Returns** \
[Wait](../../Bang/StateMachines/Wait.html) \

#### Reset()
```csharp
protected void Reset()
```

#### State(Func<TResult>)
```csharp
protected void State(Func<TResult> routine)
```

**Parameters** \
`routine` [Func\<TResult\>](https://learn.microsoft.com/en-us/dotnet/api/System.Func-1?view=net-7.0) \

#### SwitchState(Func<TResult>)
```csharp
protected void SwitchState(Func<TResult> routine)
```

**Parameters** \
`routine` [Func\<TResult\>](https://learn.microsoft.com/en-us/dotnet/api/System.Func-1?view=net-7.0) \

#### OnDestroyed()
```csharp
public virtual void OnDestroyed()
```

#### Subscribe(Action)
```csharp
public void Subscribe(Action notification)
```

**Parameters** \
`notification` [Action](https://learn.microsoft.com/en-us/dotnet/api/System.Action?view=net-7.0) \

#### Unsubscribe(Action)
```csharp
public void Unsubscribe(Action notification)
```

**Parameters** \
`notification` [Action](https://learn.microsoft.com/en-us/dotnet/api/System.Action?view=net-7.0) \



⚡