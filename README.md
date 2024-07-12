### Array Methods and Properties in Swift

#### Creating and Initializing Arrays
- `Array<Element>()` - Creates an empty array.
- `Array(repeating: Element, count: Int)` - Creates an array with a repeated value.
- `Array(arrayLiteral: Element...)` - Creates an array from a literal.

#### Properties
- `var count: Int` - Number of elements in the array.
- `var isEmpty: Bool` - Checks if the array is empty.
- `var first: Element?` - First element of the array.
- `var last: Element?` - Last element of the array.
- `var capacity: Int` - The array's storage capacity.

#### Adding and Removing Elements
- `append(_:)` - Adds an element to the end of the array.
- `append(contentsOf:)` - Adds elements from another sequence to the end of the array.
- `insert(_:at:)` - Inserts an element at a specific position.
- `insert(contentsOf:at:)` - Inserts elements from another sequence at a specific position.
- `remove(at:)` - Removes an element at a specific position.
- `removeAll(keepingCapacity:)` - Removes all elements.
- `removeLast()` - Removes the last element.
- `removeFirst()` - Removes the first element.
- `removeSubrange(_:)` - Removes elements in the specified subrange.
- `removeAll(where:)` - Removes all elements that satisfy the given predicate.
- `removeLast(_:)` - Removes the specified number of elements from the end.
- `removeFirst(_:)` - Removes the specified number of elements from the beginning.
- `popLast()` - Removes and returns the last element.

#### Accessing Elements
- `subscript(index: Int) -> Element` - Accesses the element at the specified position.
- `subscript(bounds: Range<Int>) -> ArraySlice<Element>` - Accesses a subrange of elements.
- `subscript(bounds: ClosedRange<Int>) -> ArraySlice<Element>` - Accesses a subrange of elements.

#### Finding Elements
- `contains(_:)` - Checks if the array contains a specific element.
- `first(where:)` - Returns the first element that satisfies the given predicate.
- `firstIndex(of:)` - Returns the index of the first occurrence of a specific element.
- `firstIndex(where:)` - Returns the index of the first element that satisfies the given predicate.
- `last(where:)` - Returns the last element that satisfies the given predicate.
- `lastIndex(of:)` - Returns the index of the last occurrence of a specific element.
- `lastIndex(where:)` - Returns the index of the last element that satisfies the given predicate.
- `index(of:)` - Deprecated, use `firstIndex(of:)` instead.
- `index(where:)` - Deprecated, use `firstIndex(where:)` instead.

#### Modifying Elements
- `sort()` - Sorts the array in place.
- `sorted()` - Returns a new array that is sorted.
- `sort(by:)` - Sorts the array in place using a predicate.
- `sorted(by:)` - Returns a new array that is sorted using a predicate.
- `reverse()` - Reverses the order of the elements in the array in place.
- `reversed()` - Returns a new array with the elements in reverse order.
- `shuffle()` - Shuffles the elements of the array in place.
- `shuffled()` - Returns a new array with the elements shuffled.
- `swapAt(_:_:)` - Swaps the elements at the specified positions.
- `replaceSubrange(_:with:)` -
