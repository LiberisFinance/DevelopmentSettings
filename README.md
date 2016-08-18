## Templates

### `ate`

```csharp
Assert.That($Actual$, Is.EqualTo($Expected$));
```

### `given`

```csharp
[OneTimeSetUp]
public void Given$What$() {
	$END$
}
```

### `kill`

```csharp
[OneTimeTearDown]
public void Kill() {
	$END$
}
```

### `msr`

```csharp
$Mock$
	.Setup(x => x.$Method$)
	.Returns($Value$);
```

### `then`

```csharp
[Test]
public void Then$What$() {
	$END$
}
```

### `vrf`

```csharp
$Mock$.Verify(x => x.$Method$);
```

### `when`

```csharp
[SetUp]
public void When$What$() {
	$END$
}
```
