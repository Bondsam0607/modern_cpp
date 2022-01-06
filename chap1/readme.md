# Towards Modern C++

## Deprecated Features

1. string literal constant 
   ```
   char * str = "abc"; // not allowed
   const char * str = "abc"; // allowed
   auto str = "abc";// allowed
   ```
2. `auto_ptr` is deprecated, `unique_ptr` should be used
3. `register` no longer has meaning
4. If a class has a destructor, it will no longer automatically generate copy constructor and copy assignment operator.
5. should not use `(int)2.0`, use `static_cast`, `reinterpret_cast`, `const_cast`
 
