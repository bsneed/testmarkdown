AClass
====

This is a class that does classy things.
Part of that is messing with full names, partial names, and all the names.
It does names, better than the world has ever seen.  As a matter of fact,
people have called me to tell me just *how* good at names this class is.

We will protect the names in this country.  The american people demand it,
and frankly, my administration is known for handling names well.  Fake
news or not, names will get handled.

As a matter of fact, my class handles names way classier than crooked Hillary
could ever hope.  My camp of deplorables will always handle names better than
any of crooked Hillary's.  Once we build a wall, all the bad hombres that 
want to come get a free ride while messing with our names.

Let me be very clear with this example:

```swift
AClass.dontFuck(with: me, and: myNames)
```

And that's all I have to say about that.


init()
---

##### Declaration

```swift
public init()
```

undocumented

<br />
<br />
aValue
---

##### Declaration

```swift
public var aValue: String = ""
```

This is an **awesome** documentation line for a really *useful* variable.

<br />
<br />
anotherValue
---

##### Declaration

```swift
private var anotherValue: Bool = false
```

This is an **awesome** documentation line for a really *useful* variable.

<br />
<br />
createFullName(firstname:lastname:)
---

##### Declaration

```swift
public func createFullName(firstname: String, lastname: String) -> String
```

This is an extremely complicated method that concatenates the first and last name and produces the full name.




##### Parameters

###### &nbsp;&nbsp;&nbsp;&nbsp;_firstname_
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The first part of the full name.

###### &nbsp;&nbsp;&nbsp;&nbsp;_lastname_
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The last part of the fullname.

##### Results
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;what happens with a 2nd return value?

<br />
<br />
breakFullName(fullname:)
---

##### Declaration

```swift
public func breakFullName(fullname: String) -> (firstname: String, lastname: String)
```

Another complicated function.


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


##### Parameters

###### &nbsp;&nbsp;&nbsp;&nbsp;_fullname_
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The fullname that will be broken into its parts.

##### Results
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A  with the first and last name.

<br />
<br />
x
---

##### Declaration

```swift
let x: Int = 0
```

This should not be shown.

<br />
<br />
doNothing()
---

##### Declaration

```swift
public func doNothing()
```

A do-nothing method.

<br />
<br />
