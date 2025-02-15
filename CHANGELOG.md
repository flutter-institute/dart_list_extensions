## Next release

## [1.0.5] - 2020-09-27

* Added methods `sumOfBigInt()` and `max()`, `min()` for Iterable<BigInt>.

## [1.0.4] - 2020-10-28

* Method `List.addIfNotNull()` - adds element to the end of this list if this element is not null.

## [1.0.3] - 2020-10-14

* Method `List.copyWithInsertAll()` - copy current list with adding all elements at the position of new list.

## [1.0.2] - 2020-03-04

* Method `toMap()` use functions with specified element type (may be **breaking** in some cases).
That's because implementation with dynamic makes usage very inconvenient.
* Use [innim_lint](https://pub.dev/packages/innim_lint) analysis options.

## [1.0.1-nullsafety.0] - 2020-11-24

* Method `intersperse()` - Adds an element between elements of the iterable.

## [1.0.0-nullsafety.0] - 2020-12-01

* Migrated to null safety.
* **Removed** Removed deprecated method `containsWhere()`.

## [0.1.14] - 2020-11-03

* Method `List.replace()` - Remove element and replace it with another element.
* Method `List.replaceWhere()` - Replace all elements of list that satisfy given predicate.
* Method `List.copyWithReplace()` - Copy current list, replacing all element occurrences with another element.
* Method `List.copyWithReplaceWhere()` - Copy current list, replacing elements of list
that satisfy given predicate with another element.

## [0.1.13] - 2020-08-25

* Method `sortBy()` - sorts the list in ascending order of the object's field value.
* Method `sortByDescending()` - sorts the list in descending order of the object's field value.

## [0.1.12] - 2020-07-29

* Getter `random` - returns a random element from the list.

## [0.1.11+1] - 2020-07-16

* Readme fix.

## [0.1.11] - 2020-07-16

* Analysis problems fixed.
* Remove `containsWhere()` - duplicate of `any()`.

## [0.1.10] - 2020-06-24

* Method `containsWhere()` - returns `true` if the collection contains an element that satisfy the predicate.
* Method `containsAll()` - returns `true` if the collection contains all elements from the given collection.

## [0.1.9+1] - 2020-06-01

* Readme updated.

## [0.1.9] - 2020-06-01

* Refactor methods arrangements.
* Refactor tests in groups.
* Getter `firstOrNull` -  returns the first element or `null` if collection is empty.

## [0.1.8] - 2020-05-23

* Method `maxOf()` - returns the max value of int or double values by elements.
* Method `max()` for iterables of int and double.
* Method `minOf()` - returns the min value of int or double values by elements.
* Method `min()` for iterables of int and double.
* Method `reduceValue()` - reduces values of elements in a collection to a single value
by iteratively combining its using the provided function.

## [0.1.7] - 2020-05-20

* Fixed repository url.
* Method `tryElementAt()` - returns the element at the index if exists or `orElse` if it is out of range.

## [0.1.6] - 2020-05-11

* Add classifier in README.
* Method `avgOf()` - returns the average value of int values by elements.
* Method `avgOfDouble()` - returns the average value of double values by elements.
* Methods `avg()` for iterables of int and double.

## [0.1.5] - 2020-04-27

* Method `firstWhereOrNull()` - return the first element that satisfies the given predicate or `null` if no element satisfies.

## [0.1.4] - 2020-04-07

* Method `copyWithAll()` - copy current list with adding all elements at the end of new list.
* Method `copyWith()` support null list.

## [0.1.3] - 2020-04-01

* Method `isUnorderedEquivalent()` - check equality of the elements of this and other iterables without considering order.

## [0.1.2+1] - 2020-03-31

* `quiver` dependency decreased to 2.0.0.

## [0.1.2] - 2020-03-31

* Method `joinOf()` - get string value for each element and concatenates it with separator.
* Method `chunks()` - splits into chunks (shortcut for quiver `partition()`).
* Method `toMap()` - create `Map` from iterable (shortcut for `Map.fromIterable()`).
* Extensions for `List` and method `copyWith()` - copy current list with adding element at the end of it.

## [0.1.1] - 2020-03-27

* Getter `isNullOrEmpty` - returns `true` if iterable is `null` or empty.
* Getter `isNotNullOrEmpty` - returns `true` if iterable is not `null` and not empty.
* Remove redundant Flutter dependencies.

## [0.1.0] - 2020-03-27

* Add an example.
* Update package description.

## [0.0.1] - 2020-03-26

* Method `countWhere()` - returns count of elements that satisfy the predicate `test`.
* Method `sumOf()` - returns sum of int values by elements.
* Method `sumOfDouble()` - Returns sum of double values by elements.
* Methods `sum()` for iterables of int and double.
