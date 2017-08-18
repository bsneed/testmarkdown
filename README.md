AClass
====

This is a class that does classy things.
Part of that is messing with full names, partial names, and all the names.
It does names, better than the world has ever seen.  As a matter of fact,
people have called me to tell me just *how* good at names this class is.

We will protect the names in this country.  The american people demand it,
and frankly, my administration is known for handling names well.  Fake
news or not, names will get handled.


init()
---

##### Declaration

```swift
public init()
```

undocumented

aValue
---

##### Declaration

```swift
public var aValue: String = ""
```

This is an **awesome** documentation line for a really *useful* variable.

anotherValue
---

##### Declaration

```swift
private var anotherValue: Bool = false
```

This is an **awesome** documentation line for a really *useful* variable.

createFullName(firstname:lastname:)
---

##### Declaration

```swift
public func createFullName(firstname: String, lastname: String) -> String
```

This is an extremely complicated method that concatenates the first and last name and produces the full name.

- Parameter firstname: The first part of the full name.
- Parameter lastname: The last part of the fullname.
- Returns: The full name as a string value.

breakFullName(fullname:)
---

##### Declaration

```swift
public func breakFullName(fullname: String) -> (firstname: String, lastname: String)
```

Another complicated function.

- Parameter fullname: The fullname that will be broken into its parts.
- Returns: A *tuple* with the first and last name.

- Remark:
There's a counterpart function that concatenates the first and last name into a full name.

- SeeAlso:  `createFullName(_:lastname:)`

- Precondition: `fullname` should not be nil.
- Requires: Both first and last name should be parts of the full name, separated with a *space character*.

- Todo: Support middle name in the next version.

- Warning: A wonderful **crash** will be the result of a `nil` argument.

- Version: 1.1

- Author: Myself Only

- Note: Too much documentation for such a small function.

x
---

##### Declaration

```swift
let x: Int = 0
```

This should not be shown.

doNothing()
---

##### Declaration

```swift
public func doNothing()
```

A do-nothing method.

