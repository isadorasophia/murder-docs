# MurderSourceGenerationContext

**Namespace:** Murder.Serialization \
**Assembly:** Murder.dll

```csharp
public class MurderSourceGenerationContext : JsonSerializerContext, IJsonTypeInfoResolver, IBuiltInJsonTypeInfoResolver, IMurderSerializer
```

Serialization context for all the types within Murder. You may find here all the:
             - Components
             - State machines
             - Interactions
             - Game assets
             
            And any private fields that these types have.

**Implements:** _[JsonSerializerContext](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.JsonSerializerContext?view=net-7.0), [IJsonTypeInfoResolver](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.IJsonTypeInfoResolver?view=net-7.0), [IBuiltInJsonTypeInfoResolver](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.IBuiltInJsonTypeInfoResolver?view=net-7.0), [IMurderSerializer](../../Murder/Serialization/IMurderSerializer.html)_

### ⭐ Constructors
```csharp
public MurderSourceGenerationContext()
```

```csharp
public MurderSourceGenerationContext(JsonSerializerOptions options)
```

**Parameters** \
`options` [JsonSerializerOptions](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.JsonSerializerOptions?view=net-7.0) \

### ⭐ Properties
#### AddChildOnInteraction
```csharp
public JsonTypeInfo<T> AddChildOnInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AddChildProperties
```csharp
public JsonTypeInfo<T> AddChildProperties { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AddComponentOnInteraction
```csharp
public JsonTypeInfo<T> AddComponentOnInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AddEntityOnInteraction
```csharp
public JsonTypeInfo<T> AddEntityOnInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AdvancedBlackboardInteraction
```csharp
public JsonTypeInfo<T> AdvancedBlackboardInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AdvancedCollisionComponent
```csharp
public JsonTypeInfo<T> AdvancedCollisionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AfterInteractRule
```csharp
public JsonTypeInfo<T> AfterInteractRule { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AgentComponent
```csharp
public JsonTypeInfo<T> AgentComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AgentImpulseComponent
```csharp
public JsonTypeInfo<T> AgentImpulseComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AgentSpeedOverride
```csharp
public JsonTypeInfo<T> AgentSpeedOverride { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AgentSpriteComponent
```csharp
public JsonTypeInfo<T> AgentSpriteComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AggregateException
```csharp
public JsonTypeInfo<T> AggregateException { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AlphaComponent
```csharp
public JsonTypeInfo<T> AlphaComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Anchor
```csharp
public JsonTypeInfo<T> Anchor { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AnchorId
```csharp
public JsonTypeInfo<T> AnchorId { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Animation
```csharp
public JsonTypeInfo<T> Animation { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AnimationAndRule
```csharp
public JsonTypeInfo<T> AnimationAndRule { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AnimationCompleteComponent
```csharp
public JsonTypeInfo<T> AnimationCompleteComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AnimationCompleteMessage
```csharp
public JsonTypeInfo<T> AnimationCompleteMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AnimationEventBroadcasterComponent
```csharp
public JsonTypeInfo<T> AnimationEventBroadcasterComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AnimationEventMessage
```csharp
public JsonTypeInfo<T> AnimationEventMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AnimationOverloadComponent
```csharp
public JsonTypeInfo<T> AnimationOverloadComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AnimationSequence
```csharp
public JsonTypeInfo<T> AnimationSequence { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AnimationSpeedOverload
```csharp
public JsonTypeInfo<T> AnimationSpeedOverload { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AsepriteFileInfo
```csharp
public JsonTypeInfo<T> AsepriteFileInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AssetRefPrefabAsset
```csharp
public JsonTypeInfo<T> AssetRefPrefabAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AssetRefSpriteAsset
```csharp
public JsonTypeInfo<T> AssetRefSpriteAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AtlasCoordinates
```csharp
public JsonTypeInfo<T> AtlasCoordinates { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### AtlasId
```csharp
public JsonTypeInfo<T> AtlasId { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### BaseCharacterBlackboard
```csharp
public JsonTypeInfo<T> BaseCharacterBlackboard { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### BlackboardAction
```csharp
public JsonTypeInfo<T> BlackboardAction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### BlackboardActionInteraction
```csharp
public JsonTypeInfo<T> BlackboardActionInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### BlackboardActionKind
```csharp
public JsonTypeInfo<T> BlackboardActionKind { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### BlackboardInfo
```csharp
public JsonTypeInfo<T> BlackboardInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### BlackboardKind
```csharp
public JsonTypeInfo<T> BlackboardKind { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### BlackboardTracker
```csharp
public JsonTypeInfo<T> BlackboardTracker { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Blend
```csharp
public JsonTypeInfo<T> Blend { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### BlendFunction
```csharp
public JsonTypeInfo<T> BlendFunction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### BlendState
```csharp
public JsonTypeInfo<T> BlendState { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Boolean
```csharp
public JsonTypeInfo<T> Boolean { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### BounceAmountComponent
```csharp
public JsonTypeInfo<T> BounceAmountComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### BoxShape
```csharp
public JsonTypeInfo<T> BoxShape { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### BufferUsage
```csharp
public JsonTypeInfo<T> BufferUsage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Byte
```csharp
public JsonTypeInfo<T> Byte { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CameraFollowComponent
```csharp
public JsonTypeInfo<T> CameraFollowComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CameraStyle
```csharp
public JsonTypeInfo<T> CameraStyle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CarveComponent
```csharp
public JsonTypeInfo<T> CarveComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CellProperties
```csharp
public JsonTypeInfo<T> CellProperties { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Char
```csharp
public JsonTypeInfo<T> Char { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CharacterAsset
```csharp
public JsonTypeInfo<T> CharacterAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ChildTargetComponent
```csharp
public JsonTypeInfo<T> ChildTargetComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Circle
```csharp
public JsonTypeInfo<T> Circle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CircleShape
```csharp
public JsonTypeInfo<T> CircleShape { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ClippingStyle
```csharp
public JsonTypeInfo<T> ClippingStyle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CollidedWithMessage
```csharp
public JsonTypeInfo<T> CollidedWithMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ColliderComponent
```csharp
public JsonTypeInfo<T> ColliderComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CollisionDirection
```csharp
public JsonTypeInfo<T> CollisionDirection { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Color
```csharp
public JsonTypeInfo<T> Color { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ColorWriteChannels
```csharp
public JsonTypeInfo<T> ColorWriteChannels { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CompareFunction
```csharp
public JsonTypeInfo<T> CompareFunction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ComplexDictionaryDialogItemIdIComponent
```csharp
public JsonTypeInfo<T> ComplexDictionaryDialogItemIdIComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ComplexDictionaryDialogItemIdValueTupleGuidString
```csharp
public JsonTypeInfo<T> ComplexDictionaryDialogItemIdValueTupleGuidString { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ComplexDictionaryValueTupleGuidInt32Int32Int32
```csharp
public JsonTypeInfo<T> ComplexDictionaryValueTupleGuidInt32Int32Int32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Criterion
```csharp
public JsonTypeInfo<T> Criterion { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CriterionKind
```csharp
public JsonTypeInfo<T> CriterionKind { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CriterionNode
```csharp
public JsonTypeInfo<T> CriterionNode { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CriterionNodeKind
```csharp
public JsonTypeInfo<T> CriterionNodeKind { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CullMode
```csharp
public JsonTypeInfo<T> CullMode { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CustomCollisionMask
```csharp
public JsonTypeInfo<T> CustomCollisionMask { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CustomTargetSpriteBatchComponent
```csharp
public JsonTypeInfo<T> CustomTargetSpriteBatchComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CutsceneAnchorsComponent
```csharp
public JsonTypeInfo<T> CutsceneAnchorsComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### CutsceneAnchorsEditorComponent
```csharp
public JsonTypeInfo<T> CutsceneAnchorsEditorComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DateTime
```csharp
public JsonTypeInfo<T> DateTime { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DebugInteraction
```csharp
public JsonTypeInfo<T> DebugInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Default
```csharp
public static MurderSourceGenerationContext Default { get; }
```

The default [JsonSerializerOptions](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.JsonSerializerOptions?view=net-7.0) instance.

**Returns** \
[MurderSourceGenerationContext](../../Murder/Serialization/MurderSourceGenerationContext.html) \
#### DepthFormat
```csharp
public JsonTypeInfo<T> DepthFormat { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DepthStencilState
```csharp
public JsonTypeInfo<T> DepthStencilState { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DestroyAfterSecondsComponent
```csharp
public JsonTypeInfo<T> DestroyAfterSecondsComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DestroyOnAnimationCompleteComponent
```csharp
public JsonTypeInfo<T> DestroyOnAnimationCompleteComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DestroyOnBlackboardConditionComponent
```csharp
public JsonTypeInfo<T> DestroyOnBlackboardConditionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DestroyOnCollisionComponent
```csharp
public JsonTypeInfo<T> DestroyOnCollisionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DestroyWho
```csharp
public JsonTypeInfo<T> DestroyWho { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Dialog
```csharp
public JsonTypeInfo<T> Dialog { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DialogAction
```csharp
public JsonTypeInfo<T> DialogAction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DialogEdge
```csharp
public JsonTypeInfo<T> DialogEdge { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DialogItemId
```csharp
public JsonTypeInfo<T> DialogItemId { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DialogStateMachine
```csharp
public JsonTypeInfo<T> DialogStateMachine { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryGuidEntityInstance
```csharp
public JsonTypeInfo<T> DictionaryGuidEntityInstance { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryGuidEntityModifier
```csharp
public JsonTypeInfo<T> DictionaryGuidEntityModifier { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryGuidHashSetGuid
```csharp
public JsonTypeInfo<T> DictionaryGuidHashSetGuid { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryGuidImmutableDictionaryStringBlackboardInfo
```csharp
public JsonTypeInfo<T> DictionaryGuidImmutableDictionaryStringBlackboardInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryGuidPersistStageInfo
```csharp
public JsonTypeInfo<T> DictionaryGuidPersistStageInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryGuidString
```csharp
public JsonTypeInfo<T> DictionaryGuidString { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryInt32SaveDataInfo
```csharp
public JsonTypeInfo<T> DictionaryInt32SaveDataInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryInt32String
```csharp
public JsonTypeInfo<T> DictionaryInt32String { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryStringAtlasCoordinates
```csharp
public JsonTypeInfo<T> DictionaryStringAtlasCoordinates { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryStringDictionaryInt32String
```csharp
public JsonTypeInfo<T> DictionaryStringDictionaryInt32String { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryStringHashSetInt32
```csharp
public JsonTypeInfo<T> DictionaryStringHashSetInt32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryStringImmutableArrayGuid
```csharp
public JsonTypeInfo<T> DictionaryStringImmutableArrayGuid { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryStringOrphanBlackboardContext
```csharp
public JsonTypeInfo<T> DictionaryStringOrphanBlackboardContext { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryTypeGuid
```csharp
public JsonTypeInfo<T> DictionaryTypeGuid { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DictionaryTypeIComponent
```csharp
public JsonTypeInfo<T> DictionaryTypeIComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Direction
```csharp
public JsonTypeInfo<T> Direction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DisableAgentComponent
```csharp
public JsonTypeInfo<T> DisableAgentComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DisableEntityComponent
```csharp
public JsonTypeInfo<T> DisableEntityComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DisableParticleSystemComponent
```csharp
public JsonTypeInfo<T> DisableParticleSystemComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DisplayMode
```csharp
public JsonTypeInfo<T> DisplayMode { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DisplayModeCollection
```csharp
public JsonTypeInfo<T> DisplayModeCollection { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DisplayOrientation
```csharp
public JsonTypeInfo<T> DisplayOrientation { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DoNotLoopComponent
```csharp
public JsonTypeInfo<T> DoNotLoopComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DoNotPauseComponent
```csharp
public JsonTypeInfo<T> DoNotPauseComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DoNotPersistEntityOnSaveComponent
```csharp
public JsonTypeInfo<T> DoNotPersistEntityOnSaveComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DrawRectangleComponent
```csharp
public JsonTypeInfo<T> DrawRectangleComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### DynamicAsset
```csharp
public JsonTypeInfo<T> DynamicAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### EaseKind
```csharp
public JsonTypeInfo<T> EaseKind { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### EditorAssets
```csharp
public JsonTypeInfo<T> EditorAssets { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### EditorSettingsAsset
```csharp
public JsonTypeInfo<T> EditorSettingsAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Emitter
```csharp
public JsonTypeInfo<T> Emitter { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### EmitterShape
```csharp
public JsonTypeInfo<T> EmitterShape { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### EmitterShapeKind
```csharp
public JsonTypeInfo<T> EmitterShapeKind { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### EnableChildrenInteraction
```csharp
public JsonTypeInfo<T> EnableChildrenInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Entity
```csharp
public JsonTypeInfo<T> Entity { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### EntityInstance
```csharp
public JsonTypeInfo<T> EntityInstance { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### EntityModifier
```csharp
public JsonTypeInfo<T> EntityModifier { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### EntityTrackerComponent
```csharp
public JsonTypeInfo<T> EntityTrackerComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### EventListenerComponent
```csharp
public JsonTypeInfo<T> EventListenerComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### EventListenerEditorComponent
```csharp
public JsonTypeInfo<T> EventListenerEditorComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Exception
```csharp
public JsonTypeInfo<T> Exception { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Exploration
```csharp
public JsonTypeInfo<T> Exploration { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FacingComponent
```csharp
public JsonTypeInfo<T> FacingComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FacingInfo
```csharp
public JsonTypeInfo<T> FacingInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Fact
```csharp
public JsonTypeInfo<T> Fact { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FactKind
```csharp
public JsonTypeInfo<T> FactKind { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FadeScreenComponent
```csharp
public JsonTypeInfo<T> FadeScreenComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FadeScreenWithSolidColorComponent
```csharp
public JsonTypeInfo<T> FadeScreenWithSolidColorComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FadeType
```csharp
public JsonTypeInfo<T> FadeType { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FadeWhenInAreaComponent
```csharp
public JsonTypeInfo<T> FadeWhenInAreaComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FadeWhenInAreaStyle
```csharp
public JsonTypeInfo<T> FadeWhenInAreaStyle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FadeWhenInCutsceneComponent
```csharp
public JsonTypeInfo<T> FadeWhenInCutsceneComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FatalDamageMessage
```csharp
public JsonTypeInfo<T> FatalDamageMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FeatureAsset
```csharp
public JsonTypeInfo<T> FeatureAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Feedback
```csharp
public JsonTypeInfo<T> Feedback { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FillMode
```csharp
public JsonTypeInfo<T> FillMode { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FlashSpriteComponent
```csharp
public JsonTypeInfo<T> FlashSpriteComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FloatRange
```csharp
public JsonTypeInfo<T> FloatRange { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FloorAsset
```csharp
public JsonTypeInfo<T> FloorAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FontAsset
```csharp
public JsonTypeInfo<T> FontAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FreeMovementComponent
```csharp
public JsonTypeInfo<T> FreeMovementComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### FrictionComponent
```csharp
public JsonTypeInfo<T> FrictionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### GameAsset
```csharp
public JsonTypeInfo<T> GameAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### GamePreferences
```csharp
public JsonTypeInfo<T> GamePreferences { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### GameProfile
```csharp
public JsonTypeInfo<T> GameProfile { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### GeneratedSerializerOptions
```csharp
protected virtual JsonSerializerOptions GeneratedSerializerOptions { get; }
```

The source-generated options associated with this context.

**Returns** \
[JsonSerializerOptions](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.JsonSerializerOptions?view=net-7.0) \
#### GlobalShaderComponent
```csharp
public JsonTypeInfo<T> GlobalShaderComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### GraphicsAdapter
```csharp
public JsonTypeInfo<T> GraphicsAdapter { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### GraphicsDevice
```csharp
public JsonTypeInfo<T> GraphicsDevice { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### GraphicsDeviceStatus
```csharp
public JsonTypeInfo<T> GraphicsDeviceStatus { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### GraphicsProfile
```csharp
public JsonTypeInfo<T> GraphicsProfile { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Guid
```csharp
public JsonTypeInfo<T> Guid { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### GuidArray
```csharp
public JsonTypeInfo<T> GuidArray { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### GuidId
```csharp
public JsonTypeInfo<T> GuidId { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### GuidToIdTargetCollectionComponent
```csharp
public JsonTypeInfo<T> GuidToIdTargetCollectionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### GuidToIdTargetComponent
```csharp
public JsonTypeInfo<T> GuidToIdTargetComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### HashSetGuid
```csharp
public JsonTypeInfo<T> HashSetGuid { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### HashSetInt32
```csharp
public JsonTypeInfo<T> HashSetInt32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### HashSetType
```csharp
public JsonTypeInfo<T> HashSetType { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### HasVisionComponent
```csharp
public JsonTypeInfo<T> HasVisionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### HighlightMessage
```csharp
public JsonTypeInfo<T> HighlightMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### HighlightOnChildrenComponent
```csharp
public JsonTypeInfo<T> HighlightOnChildrenComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### HighlightSpriteComponent
```csharp
public JsonTypeInfo<T> HighlightSpriteComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IBlackboard
```csharp
public JsonTypeInfo<T> IBlackboard { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ICharacterBlackboard
```csharp
public JsonTypeInfo<T> ICharacterBlackboard { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IComponent
```csharp
public JsonTypeInfo<T> IComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IDictionary
```csharp
public JsonTypeInfo<T> IDictionary { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IdTargetCollectionComponent
```csharp
public JsonTypeInfo<T> IdTargetCollectionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IdTargetComponent
```csharp
public JsonTypeInfo<T> IdTargetComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IgnoreTriggersUntilComponent
```csharp
public JsonTypeInfo<T> IgnoreTriggersUntilComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IgnoreUntilComponent
```csharp
public JsonTypeInfo<T> IgnoreUntilComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IInteraction
```csharp
public JsonTypeInfo<T> IInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IInteractiveComponent
```csharp
public JsonTypeInfo<T> IInteractiveComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IMessage
```csharp
public JsonTypeInfo<T> IMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayAnchorId
```csharp
public JsonTypeInfo<T> ImmutableArrayAnchorId { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayAnimationAndRule
```csharp
public JsonTypeInfo<T> ImmutableArrayAnimationAndRule { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayAtlasCoordinates
```csharp
public JsonTypeInfo<T> ImmutableArrayAtlasCoordinates { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayBlackboardAction
```csharp
public JsonTypeInfo<T> ImmutableArrayBlackboardAction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayCellProperties
```csharp
public JsonTypeInfo<T> ImmutableArrayCellProperties { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayColor
```csharp
public JsonTypeInfo<T> ImmutableArrayColor { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayCriterionNode
```csharp
public JsonTypeInfo<T> ImmutableArrayCriterionNode { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayDialog
```csharp
public JsonTypeInfo<T> ImmutableArrayDialog { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayDialogAction
```csharp
public JsonTypeInfo<T> ImmutableArrayDialogAction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayFacingInfo
```csharp
public JsonTypeInfo<T> ImmutableArrayFacingInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayGuid
```csharp
public JsonTypeInfo<T> ImmutableArrayGuid { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayGuidId
```csharp
public JsonTypeInfo<T> ImmutableArrayGuidId { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayIComponent
```csharp
public JsonTypeInfo<T> ImmutableArrayIComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayIInteractiveComponent
```csharp
public JsonTypeInfo<T> ImmutableArrayIInteractiveComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayInt32
```csharp
public JsonTypeInfo<T> ImmutableArrayInt32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayInteractOnRuleMatchComponent
```csharp
public JsonTypeInfo<T> ImmutableArrayInteractOnRuleMatchComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayIShape
```csharp
public JsonTypeInfo<T> ImmutableArrayIShape { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayKerning
```csharp
public JsonTypeInfo<T> ImmutableArrayKerning { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayLine
```csharp
public JsonTypeInfo<T> ImmutableArrayLine { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayLocalizedStringData
```csharp
public JsonTypeInfo<T> ImmutableArrayLocalizedStringData { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayMurderTargetedAction
```csharp
public JsonTypeInfo<T> ImmutableArrayMurderTargetedAction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayParameterRuleAction
```csharp
public JsonTypeInfo<T> ImmutableArrayParameterRuleAction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayQuestStage
```csharp
public JsonTypeInfo<T> ImmutableArrayQuestStage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayRequirementsCollection
```csharp
public JsonTypeInfo<T> ImmutableArrayRequirementsCollection { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayResourceDataForAsset
```csharp
public JsonTypeInfo<T> ImmutableArrayResourceDataForAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArraySingle
```csharp
public JsonTypeInfo<T> ImmutableArraySingle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArraySituation
```csharp
public JsonTypeInfo<T> ImmutableArraySituation { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArraySoundEventId
```csharp
public JsonTypeInfo<T> ImmutableArraySoundEventId { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArraySoundRuleAction
```csharp
public JsonTypeInfo<T> ImmutableArraySoundRuleAction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArraySpriteEventInfo
```csharp
public JsonTypeInfo<T> ImmutableArraySpriteEventInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayString
```csharp
public JsonTypeInfo<T> ImmutableArrayString { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayTargetedInteractionCollectionItem
```csharp
public JsonTypeInfo<T> ImmutableArrayTargetedInteractionCollectionItem { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayTriggerEventOn
```csharp
public JsonTypeInfo<T> ImmutableArrayTriggerEventOn { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayValueTupleGuidBoolean
```csharp
public JsonTypeInfo<T> ImmutableArrayValueTupleGuidBoolean { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayValueTupleTypeBoolean
```csharp
public JsonTypeInfo<T> ImmutableArrayValueTupleTypeBoolean { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableArrayVector2
```csharp
public JsonTypeInfo<T> ImmutableArrayVector2 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryDialogItemIdIComponent
```csharp
public JsonTypeInfo<T> ImmutableDictionaryDialogItemIdIComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryDialogItemIdValueTupleGuidString
```csharp
public JsonTypeInfo<T> ImmutableDictionaryDialogItemIdValueTupleGuidString { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryGuidEntityInstance
```csharp
public JsonTypeInfo<T> ImmutableDictionaryGuidEntityInstance { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryGuidGuid
```csharp
public JsonTypeInfo<T> ImmutableDictionaryGuidGuid { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryGuidInt32
```csharp
public JsonTypeInfo<T> ImmutableDictionaryGuidInt32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryGuidSpriteEventData
```csharp
public JsonTypeInfo<T> ImmutableDictionaryGuidSpriteEventData { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryInt32DialogEdge
```csharp
public JsonTypeInfo<T> ImmutableDictionaryInt32DialogEdge { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryInt32Guid
```csharp
public JsonTypeInfo<T> ImmutableDictionaryInt32Guid { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryInt32Int32
```csharp
public JsonTypeInfo<T> ImmutableDictionaryInt32Int32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryInt32PixelFontCharacter
```csharp
public JsonTypeInfo<T> ImmutableDictionaryInt32PixelFontCharacter { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryInt32String
```csharp
public JsonTypeInfo<T> ImmutableDictionaryInt32String { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryLanguageIdGuid
```csharp
public JsonTypeInfo<T> ImmutableDictionaryLanguageIdGuid { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryPointPoint
```csharp
public JsonTypeInfo<T> ImmutableDictionaryPointPoint { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryStringAnchor
```csharp
public JsonTypeInfo<T> ImmutableDictionaryStringAnchor { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryStringAnimation
```csharp
public JsonTypeInfo<T> ImmutableDictionaryStringAnimation { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryStringBlackboardInfo
```csharp
public JsonTypeInfo<T> ImmutableDictionaryStringBlackboardInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryStringInt32
```csharp
public JsonTypeInfo<T> ImmutableDictionaryStringInt32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryStringListString
```csharp
public JsonTypeInfo<T> ImmutableDictionaryStringListString { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryStringPortrait
```csharp
public JsonTypeInfo<T> ImmutableDictionaryStringPortrait { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableDictionaryStringSpriteEventInfo
```csharp
public JsonTypeInfo<T> ImmutableDictionaryStringSpriteEventInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ImmutableHashSetInt32
```csharp
public JsonTypeInfo<T> ImmutableHashSetInt32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IndestructibleComponent
```csharp
public JsonTypeInfo<T> IndestructibleComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IndexBuffer
```csharp
public JsonTypeInfo<T> IndexBuffer { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IndexElementSize
```csharp
public JsonTypeInfo<T> IndexElementSize { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InstanceToEntityLookupComponent
```csharp
public JsonTypeInfo<T> InstanceToEntityLookupComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Int32
```csharp
public JsonTypeInfo<T> Int32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Int32Array
```csharp
public JsonTypeInfo<T> Int32Array { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractChildOnInteraction
```csharp
public JsonTypeInfo<T> InteractChildOnInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractionCollection
```csharp
public JsonTypeInfo<T> InteractionCollection { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentAddChildOnInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentAddChildOnInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentAddComponentOnInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentAddComponentOnInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentAddEntityOnInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentAddEntityOnInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentAdvancedBlackboardInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentAdvancedBlackboardInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentBlackboardActionInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentBlackboardActionInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentDebugInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentDebugInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentEnableChildrenInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentEnableChildrenInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentInteractChildOnInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentInteractChildOnInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentInteractionCollection
```csharp
public JsonTypeInfo<T> InteractiveComponentInteractionCollection { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentInteractWithDelayInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentInteractWithDelayInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentPlayMusicInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentPlayMusicInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentPlaySoundInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentPlaySoundInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentRemoveEntityOnInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentRemoveEntityOnInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentSendInteractMessageInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentSendInteractMessageInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentSendMessageInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentSendMessageInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentSendToOtherInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentSendToOtherInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentSendToParentInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentSendToParentInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentSetPositionInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentSetPositionInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentSetSoundOnInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentSetSoundOnInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentStopMusicInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentStopMusicInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentTalkToInteraction
```csharp
public JsonTypeInfo<T> InteractiveComponentTalkToInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractiveComponentTargetedInteractionCollection
```csharp
public JsonTypeInfo<T> InteractiveComponentTargetedInteractionCollection { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractOn
```csharp
public JsonTypeInfo<T> InteractOn { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractOnCollisionComponent
```csharp
public JsonTypeInfo<T> InteractOnCollisionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractOnRuleMatchCollectionComponent
```csharp
public JsonTypeInfo<T> InteractOnRuleMatchCollectionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractOnRuleMatchComponent
```csharp
public JsonTypeInfo<T> InteractOnRuleMatchComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractOnStartComponent
```csharp
public JsonTypeInfo<T> InteractOnStartComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractorComponent
```csharp
public JsonTypeInfo<T> InteractorComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InteractWithDelayInteraction
```csharp
public JsonTypeInfo<T> InteractWithDelayInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IntPtr
```csharp
public JsonTypeInfo<T> IntPtr { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IntRectangle
```csharp
public JsonTypeInfo<T> IntRectangle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### InvisibleComponent
```csharp
public JsonTypeInfo<T> InvisibleComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IShape
```csharp
public JsonTypeInfo<T> IShape { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IsInsideOfMessage
```csharp
public JsonTypeInfo<T> IsInsideOfMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ISoundBlackboard
```csharp
public JsonTypeInfo<T> ISoundBlackboard { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### IStateMachineComponent
```csharp
public JsonTypeInfo<T> IStateMachineComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ITileProperties
```csharp
public JsonTypeInfo<T> ITileProperties { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Kerning
```csharp
public JsonTypeInfo<T> Kerning { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### LanguageId
```csharp
public JsonTypeInfo<T> LanguageId { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### LazyShape
```csharp
public JsonTypeInfo<T> LazyShape { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Line
```csharp
public JsonTypeInfo<T> Line { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Line2
```csharp
public JsonTypeInfo<T> Line2 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### LineShape
```csharp
public JsonTypeInfo<T> LineShape { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ListGameAsset
```csharp
public JsonTypeInfo<T> ListGameAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ListString
```csharp
public JsonTypeInfo<T> ListString { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ListValueTupleBlackboardInfoStringObject
```csharp
public JsonTypeInfo<T> ListValueTupleBlackboardInfoStringObject { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### LocalizationAsset
```csharp
public JsonTypeInfo<T> LocalizationAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### LocalizedString
```csharp
public JsonTypeInfo<T> LocalizedString { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### LocalizedStringData
```csharp
public JsonTypeInfo<T> LocalizedStringData { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### MatchKind
```csharp
public JsonTypeInfo<T> MatchKind { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### MethodBase
```csharp
public JsonTypeInfo<T> MethodBase { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### MovementModAreaComponent
```csharp
public JsonTypeInfo<T> MovementModAreaComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### MoveToComponent
```csharp
public JsonTypeInfo<T> MoveToComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### MoveToTargetComponent
```csharp
public JsonTypeInfo<T> MoveToTargetComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### MurderColor
```csharp
public JsonTypeInfo<T> MurderColor { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### MurderPoint
```csharp
public JsonTypeInfo<T> MurderPoint { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### MurderRectangle
```csharp
public JsonTypeInfo<T> MurderRectangle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### MurderTargetedAction
```csharp
public JsonTypeInfo<T> MurderTargetedAction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### MusicComponent
```csharp
public JsonTypeInfo<T> MusicComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### MuteEventsComponent
```csharp
public JsonTypeInfo<T> MuteEventsComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NextDialogMessage
```csharp
public JsonTypeInfo<T> NextDialogMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NineSliceComponent
```csharp
public JsonTypeInfo<T> NineSliceComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NineSliceInfo
```csharp
public JsonTypeInfo<T> NineSliceInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NineSliceStyle
```csharp
public JsonTypeInfo<T> NineSliceStyle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableAnimationSequence
```csharp
public JsonTypeInfo<T> NullableAnimationSequence { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableAsepriteFileInfo
```csharp
public JsonTypeInfo<T> NullableAsepriteFileInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableBoolean
```csharp
public JsonTypeInfo<T> NullableBoolean { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableDirection
```csharp
public JsonTypeInfo<T> NullableDirection { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableGuid
```csharp
public JsonTypeInfo<T> NullableGuid { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableImmutableArrayDialogAction
```csharp
public JsonTypeInfo<T> NullableImmutableArrayDialogAction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableImmutableArraySoundEventId
```csharp
public JsonTypeInfo<T> NullableImmutableArraySoundEventId { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableInt32
```csharp
public JsonTypeInfo<T> NullableInt32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableLocalizedString
```csharp
public JsonTypeInfo<T> NullableLocalizedString { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullablePoint
```csharp
public JsonTypeInfo<T> NullablePoint { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullablePortrait
```csharp
public JsonTypeInfo<T> NullablePortrait { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableSingle
```csharp
public JsonTypeInfo<T> NullableSingle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableSoundEventId
```csharp
public JsonTypeInfo<T> NullableSoundEventId { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableValueTupleGuidIStateMachineComponent
```csharp
public JsonTypeInfo<T> NullableValueTupleGuidIStateMachineComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### NullableVector2FromTo
```csharp
public JsonTypeInfo<T> NullableVector2FromTo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Object
```csharp
public JsonTypeInfo<T> Object { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### OnCollisionMessage
```csharp
public JsonTypeInfo<T> OnCollisionMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### OnEnterOnExitComponent
```csharp
public JsonTypeInfo<T> OnEnterOnExitComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### OnInteractExitMessage
```csharp
public JsonTypeInfo<T> OnInteractExitMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Options
```csharp
public JsonSerializerOptions Options { get; }
```

**Returns** \
[JsonSerializerOptions](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.JsonSerializerOptions?view=net-7.0) \
#### Orientation
```csharp
public JsonTypeInfo<T> Orientation { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### OrphanBlackboardContext
```csharp
public JsonTypeInfo<T> OrphanBlackboardContext { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### OutlineStyle
```csharp
public JsonTypeInfo<T> OutlineStyle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PackedGameData
```csharp
public JsonTypeInfo<T> PackedGameData { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PackedSaveAssetsData
```csharp
public JsonTypeInfo<T> PackedSaveAssetsData { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PackedSaveData
```csharp
public JsonTypeInfo<T> PackedSaveData { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PackedSoundData
```csharp
public JsonTypeInfo<T> PackedSoundData { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ParallaxComponent
```csharp
public JsonTypeInfo<T> ParallaxComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ParameterId
```csharp
public JsonTypeInfo<T> ParameterId { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ParameterRuleAction
```csharp
public JsonTypeInfo<T> ParameterRuleAction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Particle
```csharp
public JsonTypeInfo<T> Particle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ParticleIntValueProperty
```csharp
public JsonTypeInfo<T> ParticleIntValueProperty { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ParticleSystemAsset
```csharp
public JsonTypeInfo<T> ParticleSystemAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ParticleSystemComponent
```csharp
public JsonTypeInfo<T> ParticleSystemComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ParticleTexture
```csharp
public JsonTypeInfo<T> ParticleTexture { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ParticleTextureKind
```csharp
public JsonTypeInfo<T> ParticleTextureKind { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ParticleValueProperty
```csharp
public JsonTypeInfo<T> ParticleValueProperty { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ParticleValuePropertyKind
```csharp
public JsonTypeInfo<T> ParticleValuePropertyKind { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ParticleVectorValueProperty
```csharp
public JsonTypeInfo<T> ParticleVectorValueProperty { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PathfindAlgorithmKind
```csharp
public JsonTypeInfo<T> PathfindAlgorithmKind { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PathfindComponent
```csharp
public JsonTypeInfo<T> PathfindComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PathfindGridComponent
```csharp
public JsonTypeInfo<T> PathfindGridComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PathNotPossibleMessage
```csharp
public JsonTypeInfo<T> PathNotPossibleMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PauseAnimationComponent
```csharp
public JsonTypeInfo<T> PauseAnimationComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PersistPathfindComponent
```csharp
public JsonTypeInfo<T> PersistPathfindComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PersistStageInfo
```csharp
public JsonTypeInfo<T> PersistStageInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PickChoiceMessage
```csharp
public JsonTypeInfo<T> PickChoiceMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PickEntityToAddOnStartComponent
```csharp
public JsonTypeInfo<T> PickEntityToAddOnStartComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PixelFontCharacter
```csharp
public JsonTypeInfo<T> PixelFontCharacter { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PlayAnimationOnRuleComponent
```csharp
public JsonTypeInfo<T> PlayAnimationOnRuleComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PlayMusicInteraction
```csharp
public JsonTypeInfo<T> PlayMusicInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PlaySoundInteraction
```csharp
public JsonTypeInfo<T> PlaySoundInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PointShape
```csharp
public JsonTypeInfo<T> PointShape { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Polygon
```csharp
public JsonTypeInfo<T> Polygon { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PolygonShape
```csharp
public JsonTypeInfo<T> PolygonShape { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PolygonSpriteComponent
```csharp
public JsonTypeInfo<T> PolygonSpriteComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Portrait
```csharp
public JsonTypeInfo<T> Portrait { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PositionComponent
```csharp
public JsonTypeInfo<T> PositionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PrefabAsset
```csharp
public JsonTypeInfo<T> PrefabAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PrefabEntityInstance
```csharp
public JsonTypeInfo<T> PrefabEntityInstance { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PrefabRefComponent
```csharp
public JsonTypeInfo<T> PrefabRefComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PrefabReference
```csharp
public JsonTypeInfo<T> PrefabReference { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PreloadPackedGameData
```csharp
public JsonTypeInfo<T> PreloadPackedGameData { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PresentationParameters
```csharp
public JsonTypeInfo<T> PresentationParameters { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PresentInterval
```csharp
public JsonTypeInfo<T> PresentInterval { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### PushAwayComponent
```csharp
public JsonTypeInfo<T> PushAwayComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### QuestStage
```csharp
public JsonTypeInfo<T> QuestStage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### QuestTrackerComponent
```csharp
public JsonTypeInfo<T> QuestTrackerComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RandomizeSpriteComponent
```csharp
public JsonTypeInfo<T> RandomizeSpriteComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RasterizerState
```csharp
public JsonTypeInfo<T> RasterizerState { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ReadOnlyCollectionException
```csharp
public JsonTypeInfo<T> ReadOnlyCollectionException { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Rectangle
```csharp
public JsonTypeInfo<T> Rectangle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RectPositionComponent
```csharp
public JsonTypeInfo<T> RectPositionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ReflectionComponent
```csharp
public JsonTypeInfo<T> ReflectionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RemoveColliderWhenStoppedComponent
```csharp
public JsonTypeInfo<T> RemoveColliderWhenStoppedComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RemoveEntityOnInteraction
```csharp
public JsonTypeInfo<T> RemoveEntityOnInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RemoveEntityOnRuleMatchAtLoadComponent
```csharp
public JsonTypeInfo<T> RemoveEntityOnRuleMatchAtLoadComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RenderTargetUsage
```csharp
public JsonTypeInfo<T> RenderTargetUsage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RequirementsCollection
```csharp
public JsonTypeInfo<T> RequirementsCollection { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RequiresVisionComponent
```csharp
public JsonTypeInfo<T> RequiresVisionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ResourceDataForAsset
```csharp
public JsonTypeInfo<T> ResourceDataForAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RoomComponent
```csharp
public JsonTypeInfo<T> RoomComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RotationComponent
```csharp
public JsonTypeInfo<T> RotationComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RoundingMode
```csharp
public JsonTypeInfo<T> RoundingMode { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### RouteComponent
```csharp
public JsonTypeInfo<T> RouteComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SamplerStateCollection
```csharp
public JsonTypeInfo<T> SamplerStateCollection { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SaveData
```csharp
public JsonTypeInfo<T> SaveData { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SaveDataInfo
```csharp
public JsonTypeInfo<T> SaveDataInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SaveDataTracker
```csharp
public JsonTypeInfo<T> SaveDataTracker { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SavedWorld
```csharp
public JsonTypeInfo<T> SavedWorld { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ScaleComponent
```csharp
public JsonTypeInfo<T> ScaleComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SendInteractMessageInteraction
```csharp
public JsonTypeInfo<T> SendInteractMessageInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SendMessageInteraction
```csharp
public JsonTypeInfo<T> SendMessageInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SendToOtherInteraction
```csharp
public JsonTypeInfo<T> SendToOtherInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SendToParentInteraction
```csharp
public JsonTypeInfo<T> SendToParentInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SetPositionInteraction
```csharp
public JsonTypeInfo<T> SetPositionInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SetSoundOnInteraction
```csharp
public JsonTypeInfo<T> SetSoundOnInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Single
```csharp
public JsonTypeInfo<T> Single { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SingleArray
```csharp
public JsonTypeInfo<T> SingleArray { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Situation
```csharp
public JsonTypeInfo<T> Situation { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SituationComponent
```csharp
public JsonTypeInfo<T> SituationComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SmartFloatAsset
```csharp
public JsonTypeInfo<T> SmartFloatAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SmartIntAsset
```csharp
public JsonTypeInfo<T> SmartIntAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SortedListInt32Situation
```csharp
public JsonTypeInfo<T> SortedListInt32Situation { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SoundComponent
```csharp
public JsonTypeInfo<T> SoundComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SoundEventId
```csharp
public JsonTypeInfo<T> SoundEventId { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SoundEventPositionTrackerComponent
```csharp
public JsonTypeInfo<T> SoundEventPositionTrackerComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SoundFact
```csharp
public JsonTypeInfo<T> SoundFact { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SoundParameterComponent
```csharp
public JsonTypeInfo<T> SoundParameterComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SoundRuleAction
```csharp
public JsonTypeInfo<T> SoundRuleAction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SpeakerAsset
```csharp
public JsonTypeInfo<T> SpeakerAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SpeakerComponent
```csharp
public JsonTypeInfo<T> SpeakerComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SpriteAsset
```csharp
public JsonTypeInfo<T> SpriteAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SpriteClippingRectComponent
```csharp
public JsonTypeInfo<T> SpriteClippingRectComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SpriteComponent
```csharp
public JsonTypeInfo<T> SpriteComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SpriteEventData
```csharp
public JsonTypeInfo<T> SpriteEventData { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SpriteEventDataManagerAsset
```csharp
public JsonTypeInfo<T> SpriteEventDataManagerAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SpriteEventInfo
```csharp
public JsonTypeInfo<T> SpriteEventInfo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SpriteFacingComponent
```csharp
public JsonTypeInfo<T> SpriteFacingComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SpriteOffsetComponent
```csharp
public JsonTypeInfo<T> SpriteOffsetComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### StateMachine
```csharp
public JsonTypeInfo<T> StateMachine { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### StateMachineComponentDialogStateMachine
```csharp
public JsonTypeInfo<T> StateMachineComponentDialogStateMachine { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### StaticComponent
```csharp
public JsonTypeInfo<T> StaticComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### StencilOperation
```csharp
public JsonTypeInfo<T> StencilOperation { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### StopMusicInteraction
```csharp
public JsonTypeInfo<T> StopMusicInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### StrafingComponent
```csharp
public JsonTypeInfo<T> StrafingComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### String
```csharp
public JsonTypeInfo<T> String { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### SurfaceFormat
```csharp
public JsonTypeInfo<T> SurfaceFormat { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Tags
```csharp
public JsonTypeInfo<T> Tags { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TagsComponent
```csharp
public JsonTypeInfo<T> TagsComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TalkToInteraction
```csharp
public JsonTypeInfo<T> TalkToInteraction { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TargetedInteractionCollection
```csharp
public JsonTypeInfo<T> TargetedInteractionCollection { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TargetedInteractionCollectionItem
```csharp
public JsonTypeInfo<T> TargetedInteractionCollectionItem { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TargetEntity
```csharp
public JsonTypeInfo<T> TargetEntity { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Task
```csharp
public JsonTypeInfo<T> Task { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TaskCreationOptions
```csharp
public JsonTypeInfo<T> TaskCreationOptions { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TaskStatus
```csharp
public JsonTypeInfo<T> TaskStatus { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Texture2D
```csharp
public JsonTypeInfo<T> Texture2D { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TextureAtlas
```csharp
public JsonTypeInfo<T> TextureAtlas { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TextureCollection
```csharp
public JsonTypeInfo<T> TextureCollection { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Theme
```csharp
public JsonTypeInfo<T> Theme { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ThetherSnapMessage
```csharp
public JsonTypeInfo<T> ThetherSnapMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ThreeSliceComponent
```csharp
public JsonTypeInfo<T> ThreeSliceComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TileDimensions
```csharp
public JsonTypeInfo<T> TileDimensions { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TileGrid
```csharp
public JsonTypeInfo<T> TileGrid { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TileGridComponent
```csharp
public JsonTypeInfo<T> TileGridComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TilesetAsset
```csharp
public JsonTypeInfo<T> TilesetAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TilesetComponent
```csharp
public JsonTypeInfo<T> TilesetComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TimeScaleComponent
```csharp
public JsonTypeInfo<T> TimeScaleComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TintComponent
```csharp
public JsonTypeInfo<T> TintComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TouchedGroundMessage
```csharp
public JsonTypeInfo<T> TouchedGroundMessage { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TriggerEventOn
```csharp
public JsonTypeInfo<T> TriggerEventOn { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### TweenComponent
```csharp
public JsonTypeInfo<T> TweenComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Type
```csharp
public JsonTypeInfo<T> Type { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### UiDisplayComponent
```csharp
public JsonTypeInfo<T> UiDisplayComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### UInt32
```csharp
public JsonTypeInfo<T> UInt32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### UnscaledDeltaTimeComponent
```csharp
public JsonTypeInfo<T> UnscaledDeltaTimeComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ValueTupleBlackboardInfoStringObject
```csharp
public JsonTypeInfo<T> ValueTupleBlackboardInfoStringObject { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ValueTupleGuidBoolean
```csharp
public JsonTypeInfo<T> ValueTupleGuidBoolean { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ValueTupleGuidInt32Int32
```csharp
public JsonTypeInfo<T> ValueTupleGuidInt32Int32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ValueTupleGuidIStateMachineComponent
```csharp
public JsonTypeInfo<T> ValueTupleGuidIStateMachineComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ValueTupleGuidString
```csharp
public JsonTypeInfo<T> ValueTupleGuidString { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ValueTupleInt32Int32
```csharp
public JsonTypeInfo<T> ValueTupleInt32Int32 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ValueTupleTypeBoolean
```csharp
public JsonTypeInfo<T> ValueTupleTypeBoolean { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Vector2
```csharp
public JsonTypeInfo<T> Vector2 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Vector2FromTo
```csharp
public JsonTypeInfo<T> Vector2FromTo { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Vector4
```csharp
public JsonTypeInfo<T> Vector4 { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### VelocityComponent
```csharp
public JsonTypeInfo<T> VelocityComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### VelocityTowardsFacingComponent
```csharp
public JsonTypeInfo<T> VelocityTowardsFacingComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### VerticalPositionComponent
```csharp
public JsonTypeInfo<T> VerticalPositionComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### Viewport
```csharp
public JsonTypeInfo<T> Viewport { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ViewportResizeMode
```csharp
public JsonTypeInfo<T> ViewportResizeMode { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### ViewportResizeStyle
```csharp
public JsonTypeInfo<T> ViewportResizeStyle { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### WaitForVacancyComponent
```csharp
public JsonTypeInfo<T> WaitForVacancyComponent { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### WorldAsset
```csharp
public JsonTypeInfo<T> WorldAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### WorldEventsAsset
```csharp
public JsonTypeInfo<T> WorldEventsAsset { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
#### XnaPoint
```csharp
public JsonTypeInfo<T> XnaPoint { get; }
```

Defines the source generated JSON serialization contract metadata for a given type.

**Returns** \
[JsonTypeInfo\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo-1?view=net-7.0) \
### ⭐ Methods
#### GetTypeInfo(Type)
```csharp
public virtual JsonTypeInfo GetTypeInfo(Type type)
```

**Parameters** \
`type` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \

**Returns** \
[JsonTypeInfo](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo?view=net-7.0) \



⚡