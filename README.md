# Combine Rust and Python

Steps taken:

1. Installing Maturin

   ```sh
   brew install maturin
   ```

2. Creating Project

   ```sh
   maturin new -b pyo3 combine-rust-and-python
   ```

3. Adding Rust code
4. Creating virtual environment

   ```sh
   python -m venv venv
   source venv/bin/activate
   ```

5. Building and installing

   ```sh
   maturing develop
   ```

Testing out via Python's REPL via:

```py
import combine_rust_and_python as crp
crp.sum_as_string(1,2)
'3'
```
