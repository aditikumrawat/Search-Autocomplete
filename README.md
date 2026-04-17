# 🔍 Search Autocomplete using Trie

This project implements a search autocomplete system using a **Trie (prefix tree)** to efficiently return the **top-k suggestions** based on user input.

## 🚀 Features
- Fast prefix-based search using Trie
- Returns top-k relevant suggestions in real time
- Scalable for large datasets
- Efficient insertion and lookup operations

## 🧠 How It Works
- Words are stored in a Trie structure.
- As the user types a prefix, the Trie is traversed character by character.
- Once the prefix node is reached, a search is performed to fetch the top-k suggestions.
- Suggestions can be ranked based on frequency or lexicographical order.

## 🛠️ Tech Stack
- Java
- Spring Boot

## 📌 Use Cases
- Search engines
- E-commerce product search
- Code editors (auto-suggestions)
- Text prediction systems
