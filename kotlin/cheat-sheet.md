## 1. Declaring Variables

```kotlin
var mutableVariable: String = "Hello"
val immutableVariable: Int = 10
```

## 2. Data Types

```kotlin
val string: String = "Hello"
val int: Int = 123
val long: Long = 123456789012345
val double: Double = 12.34
val float: Float = 12.34f
val boolean: Boolean = true
```

## 3. Control Flow

```kotlin
// If-Else
if (condition) {
    // statements
} else {
    // statements
}

// When (Switch)
when (variable) {
    value1 -> // statements
    value2 -> // statements
    else -> // default statements
}

// For loop
for (item in collection) {
    // statements
}

// While loop
while (condition) {
    // statements
}
```

## 4. Functions

```kotlin
fun functionName(param1: Type1, param2: Type2): ReturnType {
    // statements
    return result
}
```

## 5. Nullability

```kotlin
var canBeNull: String? = null
var cannotBeNull: String = "Hello"
```

## 6. Collections

```kotlin
val list = listOf("A", "B", "C")
val set = setOf("A", "B", "C")
val map = mapOf("A" to 1, "B" to 2, "C" to 3)
```

## 7. Classes

```kotlin
class ClassName {
    // properties and methods
}

// Data class (Automatically provides equals(), hashCode(), toString(), and copy())
data class DataClassName(val property1: Type1, var property2: Type2)
```

## 8. Interface

```kotlin
interface InterfaceName {
    // properties and methods
}
```

## 9. Exception Handling

```kotlin
try {
    // statements
} catch (e: ExceptionType) {
    // handle exception
} finally {
    // cleanup statements
}
```

## 10. Extension Functions

```kotlin
fun Type.newFunction(param: ParamType): ReturnType {
    // statements
    return result
}
```

## 11. Coroutines

```kotlin
import kotlinx.coroutines.*

fun main() = runBlocking {
    launch {
        // start new coroutine
    }
}
```
