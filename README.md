# HandsOn_12

## Output

<img width="612" alt="Screen Shot 2025-04-01 at 6 18 22 PM" src="https://github.com/user-attachments/assets/74ce7899-1c73-4137-b800-fb546d3938d1" />

## DynamicList

A simple dynamic array implementation in Python, similar to Python's built-in list. This class supports basic operations like adding, retrieving, and removing elements, with automatic resizing when the array reaches capacity.

## Features

- **Dynamic resizing**: The array doubles its capacity when needed, ensuring efficient memory management.
- **Basic operations**: Supports adding (`append`), retrieving (`get_item`), and removing (`remove_item`) elements.
- **Simple API**: Minimal and easy-to-use interface for common list operations.

## Getting Started

### Prerequisites

This implementation uses the `ctypes` module, which is included in Python’s standard library, so no additional dependencies are required.

### Installation

Simply download or copy the `DynamicList` class into your project file.

## Usage

```python
# Import or paste the DynamicList class into your script

# Initialize an instance of DynamicList
my_list = DynamicList()

# Add elements to the list
my_list.append(10)
my_list.append(20)
my_list.append(30)

# Retrieve an element by index
print("Item at index 1:", my_list.get_item(1))  # Output: 20

# Remove an element
my_list.remove_item(10)
print("List after removing 10:", my_list)        # Output: DynamicList([20, 30])
```
