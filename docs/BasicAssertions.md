# Basic assertions

This assertions are available for all objects:

## Testing for equality
```kt
anObject shouldEqual anotherObject
anObject shouldNotEqual anotherObject
```

## Testing for referential equality
```kt
anObject shouldBe anObject
anObject shouldNotBe anotherObject
```

## Testing for subtypes
```kt
anObject shouldBeInstanceOf Any::class
anObject shouldNotBeInstanceOf Int::class
```

## Test for nullability
```kt
anObject.shouldBeNull()
anObject.shouldNotBeNull()
```

## Testing booleans
```kt
isMale.shouldBeTrue()
isMale.shouldBeFalse()
isMale.shouldNotBeTrue()
isMale.shouldNotBeFalse()
```
