
# Week 7 Assignment: Hands-On Lab — Shopping List Manager

## Project Description

This project demonstrates Python list operations, loops, conditional statements, membership checks, and basic data reporting.

## Files

- `list_warmup.py` - Demonstrates creating a list, accessing items by index, adding and removing fruits, and counting list items.
- `shopping_list.py` - Implements an interactive shopping list manager with add, remove, show, and done commands.
- `list_report.py` - Prints numbered shopping items, counts names with more than four letters, and finds the longest item name.
- `README.md` - Provides the assignment description, file summaries, and an explanation of safe list removal.
- `screenshots/` - Contains screenshots showing the output of all three programs.

## Why is it safer to check `in` before calling `.remove()`?

Checking whether an item exists in a list before calling `.remove()` prevents a `ValueError` when the item is missing. The `in` operator allows the program to handle missing items with a helpful message instead of stopping unexpectedly.

## How to Run the Programs

Run each program separately in the terminal:

```bash
python list_warmup.py
python shopping_list.py
python list_report.py
```

## Conclusion

This assignment demonstrates how Python lists and loops can be used to manage collections, respond to user choices, and generate useful reports.