# Ruby Arrays & Hashes - Bootcamp Week 2 Day 4

This is a hands-on exercise from a coding bootcamp focused on mastering **Arrays** and **Hashes** in Ruby. The exercises help solidify fundamental data structure manipulation skills through practical examples.

## Learning Objectives
- Master Ruby array methods and operations
- Practice data manipulation and filtering
- Understand iteration and enumeration
- Work with string manipulation
- Apply sorting and searching algorithms
- Create and manipulate hashes
- Use the `.zip` method to combine arrays

## Project Structure
```
lib/
├── 00_journalists.rb           # Array manipulation exercises (starter file)
├── 01_cryptocurrencies.rb      # Cryptocurrencies array exercises
```

## 🧑‍💻 Exercises

### Exercise 00: Journalists (`00_journalists.rb`)

**Tasks Covered:**
- **Count elements**: Get the total number of handles in the array
- **Find shortest**: Identify the handle with the minimum length
- **Filter by criteria**: Select handles with exactly 5 characters (excluding @)
- **Count capitalized**: Count handles starting with a capital letter after @
- **Sort alphabetically**: Organize handles in alphabetical order
- **Sort by length**: Arrange handles from shortest to longest
- **Search position**: Find the index position of a specific handle in the array

**Key Ruby Methods Used:**
- `.length` - Count array elements
- `.min_by` - Find minimum by a given criteria
- `.select` - Filter elements based on conditions
- `.count` - Count elements matching a condition
- `.sort` - Sort alphabetically
- `.sort_by` - Sort by custom criteria
- `.index` - Find position of an element

### Exercise 02: Cryptocurrency Hash (`02_cryptocurrencies_hash.rb`)

**Tasks Covered:**
- **Create hash from arrays**: Use `.zip` to combine two arrays (names and prices) into a hash
- **Find highest value**: Identify cryptocurrency with maximum price
- **Find lowest value**: Identify cryptocurrency with minimum price
- **Filter by price**: Find all currencies below a certain threshold ($6000)
- **Complex queries**: Find the most expensive currency among filtered results

**Key Ruby Methods Used:**
- `.zip` - Combine two arrays into pairs
- `.to_h` - Convert array of pairs to hash
- `.map(&:to_f)` - Convert strings to floats
- `.select` - Filter hash based on conditions
- `.max` / `.min` - Find maximum/minimum values
- `.max_by` - Find element with maximum value by criteria
- `.values` - Get all values from hash
