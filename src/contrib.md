# Example article

$$a^2 + b^2 = c^2$$

```cpp
int gcd (int a, int b) {
    if (b == 0)
        return a;
    else
        return gcd (b, a % b);
}
```
