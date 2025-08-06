# HashMap: Separate Chaining and Open Addressing
---
## Overview
This project implements a HashMap in Python using two different collision resolution techniques:

&nbsp;Separate Chaining with singly linked lists

&nbsp;Open Addressing with Quadratic Probing

&nbsp;The goal of the project is to deepen understanding of hash table internals, collision handling, dynamic resizing, and efficient data storage and retrieval.

&nbsp;This was completed as a portfolio assignment for Oregon State University’s CS261 course.

## Implemented Features
Core Methods (Implemented for Both Versions)
&nbsp;put(key, value) — Add or update key-value pairs

&nbsp;get(key) — Retrieve value for a given key

&nbsp;remove(key) — Delete key-value pair

&nbsp;resize_table(new_capacity) — Resize internal storage while preserving existing entries

&nbsp;contains_key(key) — Check if a key exists

&nbsp;empty_buckets() — Return the number of empty buckets

&nbsp;table_load() — Return the load factor of the table

&nbsp;get_keys_and_values() — Return a list of all keys and their values

&nbsp;clear() — Remove all entries

## Additional Features
&nbsp;find_mode() (Separate Chaining only) — Find the most frequently occurring value(s) in the table

__iter__() and __next__() (Open Addressing only) — Enable iteration over key-value pairs

##Technologies and Tools
Python 3

Object-Oriented Programming

Custom dynamic array and singly linked list (provided as starter code)

No third-party libraries
