# 🔗 What is a Tuple in Python?

Learn what tuples are, how they differ from lists, and when to use them.

---

## 💡 What You'll Learn

* What a tuple is and how to define it
* How tuples differ from lists (immutability)
* When and why to use tuples

---

## 💻 Example with Explanation

### 📦 Define a tuple:

```python
data = ("Alice", 31, "Berlin")
```

### 📥 Access values by index:

```python
data = ("Alice", 31, "Berlin")
print(data[0])
```

🖨️ Output:

```
Alice
```

### 🚫 Tuples are immutable (can’t be changed):

```python
data = ("Alice", 31, "Berlin")
data[1] = 32  # ❌ This will raise an error
```

🖨️ Output:

```
TypeError: 'tuple' object does not support item assignment
```

---

## 📌 Key Notes

* Tuples use `()` instead of `[]`
* You can't change, add, or remove items from a tuple
* Tuples are faster and safer for fixed data sets

---

## 🧪 Try It Yourself

```python
coordinates = (52.5200, 13.4050)  # Berlin coordinates
print("Latitude:", coordinates[0])
print("Longitude:", coordinates[1])
```

### 🔈 Expected Output

```
Latitude: 52.52
Longitude: 13.405
```

---

💡 **Quick Tip:** Use tuples to group related values that shouldn't change.

```python
user_info = ("Alice", "Admin", True)
print("Role:", user_info[1])
```

🖨️ Output:

```
Role: Admin
```

---

🐍 This is part of the **Pythonly** beginner series.
Learn Python one line at a time. Follow **[@Pythonly](https://www.youtube.com/@Pythonly)** for more.

---

