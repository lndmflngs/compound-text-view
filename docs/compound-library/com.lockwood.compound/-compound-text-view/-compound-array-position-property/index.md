[compound-library](../../../index.md) / [com.lockwood.compound](../../index.md) / [CompoundTextView](../index.md) / [CompoundArrayPositionProperty](./index.md)

# CompoundArrayPositionProperty

`protected inner class CompoundArrayPositionProperty<T> : `[`ReadWriteProperty`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.properties/-read-write-property/index.html)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?, T>` [(source)](https://github.com/lndmflngs/compound-text-view/tree/master/compound-library/src/main/java/com/lockwood/compound/CompoundTextView.kt#L1177)

Property that store drawable related value in [array](#) at specific [position](#)

### Parameters

`T` - type of stored value

`array` - to store values

`position` - of value (drawable)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Property that store drawable related value in [array](#) at specific [position](#)`CompoundArrayPositionProperty(array: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<T>, position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)` |

### Functions

| Name | Summary |
|---|---|
| [getValue](get-value.md) | `fun getValue(thisRef: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?, property: `[`KProperty`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)`<*>): T` |
| [setValue](set-value.md) | Set value in [array](#) at [position](#) and then update state of compound drawables`fun setValue(thisRef: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?, property: `[`KProperty`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.reflect/-k-property/index.html)`<*>, value: T): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |