[shark](../../index.md) / [shark](../index.md) / [LibraryLeak](index.md) / [retainedHeapByteSize](./retained-heap-byte-size.md)

# retainedHeapByteSize

`val retainedHeapByteSize: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`?`

Overrides [Leak.retainedHeapByteSize](../-leak/retained-heap-byte-size.md)

The number of bytes which would be freed if all references to the leaking object were
released. Null if the retained heap size was not computed.

