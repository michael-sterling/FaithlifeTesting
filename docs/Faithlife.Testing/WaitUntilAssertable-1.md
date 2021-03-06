# WaitUntilAssertable&lt;T&gt; class

Waits for a value which pases provided assertions.

```csharp
public sealed class WaitUntilAssertable<T>
    where T : class
```

## Public Members

| name | description |
| --- | --- |
| [Value](WaitUntilAssertable-1/Value.md) { get; } | Synchronously waits for an appropiate value. |
| [Apply&lt;TResult&gt;](WaitUntilAssertable-1/Apply.md)(…) | Applies a *transform* to the assertion we will wait for. |
| [Context](WaitUntilAssertable-1/Context.md)(…) | Adds informational context to all assertions made using this chain. (5 methods) |
| [Context&lt;TValue&gt;](WaitUntilAssertable-1/Context.md)(…) | Adds informational context to all assertions made using this chain. |
| [DoesNotThrow](WaitUntilAssertable-1/DoesNotThrow.md)(…) | Asserts that *assertionExpression* does not throw an exception and allows chaining further asserts on the current value. |
| [GetAwaiter](WaitUntilAssertable-1/GetAwaiter.md)() | Starts waiting. |
| [HasValue&lt;TResult&gt;](WaitUntilAssertable-1/HasValue.md)(…) | Asserts that *mapExpression* does not return `null` and allows chaining further asserts on that *TResult* value. (2 methods) |
| [IsTrue](WaitUntilAssertable-1/IsTrue.md)(…) | Asserts that *predicateExpression* does not return `false` and allows chaining further asserts on the current value. |
| [WithTimeout](WaitUntilAssertable-1/WithTimeout.md)(…) | Returns a new `WaitUntilAssertable{T}` with the specified *timeout* |
| [implicit operator](WaitUntilAssertable-1/op_Implicit.md) |  (2 operators) |

## See Also

* namespace [Faithlife.Testing](../Faithlife.Testing.md)
* [WaitUntilAssertable.cs](https://github.com/Faithlife/FaithlifeTesting/tree/master/src/Faithlife.Testing/WaitUntilAssertable.cs)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Testing.dll -->
