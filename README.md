# Practice_4

**а.** Дополните схему дерева файлов и модулей пакета `calculator`, указав, какие модули и функции в них содержатся.

    calculator/
    ├── __init__.py
    ├── basic/
    │   ├── __init__.py
    │   ├── addition.py
    │   └── subtraction.py
    └── advanced/
        ├── __init__.py
        ├── exponentiation.py
        └── root.py


  Ответ: 

    calculator/
    ├── __init__.py
    ├── basic/
    │   ├── __init__.py
    │   ├── addition.py
    │   │   └── add(a, b)
    │   └── subtraction.py
    │       └── subtract(a, b)
    └── advanced/
        ├── __init__.py
        ├── exponentiation.py
        │   └── power(a, b)
        └── root.py
            └── square_root(a)
