# EnumerableUtility.FirstOrDefault&lt;T&gt; method (1 of 2)

Returns the first element of a sequence or a default value if no such element is found.

```csharp
public static T FirstOrDefault<T>(this IEnumerable<T> seq, T defaultValue)
```

| parameter | description |
| --- | --- |
| T | The type of the elements of *seq*. |
| seq | An IEnumerable&lt;TSource&gt; to return an element from. |
| defaultValue | The value to return if no element is found. |

## Return Value

*defaultValue* if *seq* is empty; otherwise, the first element in *seq*.

## See Also

* class [EnumerableUtility](../EnumerableUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

---

# EnumerableUtility.FirstOrDefault&lt;T&gt; method (2 of 2)

Returns the first element of a sequence that satisfies a condition or a default value if no such element is found.

```csharp
public static T FirstOrDefault<T>(this IEnumerable<T> seq, Func<T, bool> fnPredicate, T defaultValue)
```

| parameter | description |
| --- | --- |
| T | The type of the elements of *seq*. |
| seq | An IEnumerable&lt;TSource&gt; to return an element from. |
| fnPredicate | A function to test each element for a condition. |
| defaultValue | The value to return if no element satisfies the condition. |

## Return Value

*defaultValue* if *seq* is empty or if no element passes the test specified by *fnPredicate*; otherwise, the first element in *seq* that passes the test specified by *fnPredicate*.

## See Also

* class [EnumerableUtility](../EnumerableUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->