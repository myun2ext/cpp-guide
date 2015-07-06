# Const method

```cpp
class A {
private:
  int a;
public:
  void set(int n) { a = n; }
  int get() const { return a; }
};
```

```cpp
A a;
a.set(3);
a.get();

const A aa;
a.set(3); // Compile error!
a.get();  // Compilable
```
