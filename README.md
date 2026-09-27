# Hashing – Division Method

## 📌 Project Overview

This project demonstrates the **Hashing Division Method** using C.

Hashing is used to store and search data efficiently by mapping a key to an index in a hash table.

## 🔹 Hash Function

The division method is used to calculate the hash index:

h(k) = k % m

Where:

- `k` = key/value
- `m` = size of the hash table

In this project:

```text
Hash table size = 10
Hash function = k % 10
