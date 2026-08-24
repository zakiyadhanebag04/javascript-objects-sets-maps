# JavaScript Objects, Sets and Maps

## About the Project

This is a simple JavaScript project that demonstrates Objects, Sets, and Maps.

The program performs the required operations and displays the results in the browser console.

## Objects

The program creates two person objects.

Each object contains:

- Name
- Age
- Gender
- Occupation

Two different persons are created and their details are printed to the console.

## Sets

The program demonstrates Set operations.

It:

- Creates a Set containing only unique numbers.
- Performs union between two Sets.
- Performs intersection between two Sets.
- Finds the difference between two Sets.
- Checks whether one Set is a subset of another Set.

### Set Methods Used

- `new Set()` - Creates a Set.
- `has()` - Checks whether a value exists in a Set.
- `filter()` - Helps perform set operations.
- `every()` - Checks whether all values of one Set exist in another Set.

## Maps

The program demonstrates Map operations.

It:

- Creates a Map.
- Adds key-value pairs.
- Accesses a value.
- Updates a value.
- Deletes an entry.

### Map Methods Used

- `new Map()` - Creates a Map.
- `set()` - Adds or updates a key-value pair.
- `get()` - Accesses a value.
- `delete()` - Removes a key-value pair.

## Example Output

### objects

```text
Person 1: John, 25, Male, Developer
Person 2: Alice, 23, Female, Designer

### set

Unique numbers: [1, 2, 3, 4, 5]

Set A: [1, 2, 3, 4]
Set B: [3, 4, 5, 6]

Union: [1, 2, 3, 4, 5, 6]
Intersection: [3, 4]
Difference: [1, 2]

Is Set C a subset of Set A: true

###maps

Student name: Suhana
Updated age: 22
Map after deleting course: [["name", "Suhana"], ["age", 22]]
