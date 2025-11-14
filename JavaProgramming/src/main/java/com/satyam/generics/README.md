# Generics

Generics allow you to define classes, interfaces and methods with type parameters.
	Instead of writing the same code for int, String, or Employee, you write one 
	generic version that works for any type — safely.
	

##  Limitations of Generics

- Can’t instantiate a generic type: new T() ❌
- Can’t use primitives as type arguments (List<int> ❌).
- Can’t use instanceof with generic types (if (obj instanceof Box<String>) ❌).
- Type information is erased at runtime (no reified generics). 

##  Useful Generic Utility Classes in Java
	
- Optional<T> — wraps possibly-null values safely.
- Comparator<T> — functional interface for sorting.
- Stream<T> — collection-like data pipeline.
- Function<T,R>, Predicate<T>, Supplier<T>, Consumer<T> — for functional programming.

