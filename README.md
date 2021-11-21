# PyCharm Task
 
filter.py

![filter](https://user-images.githubusercontent.com/81950751/142760168-8c6050dc-cc73-4378-8d60-cec33685653f.png)
old_filter.py

![old_filter](https://user-images.githubusercontent.com/81950751/142760195-64d3d420-d0c5-4cdf-aadd-abd8f8943550.png)

Кажется, что old_filter.py работает быстрее, однако filter.py работает долго только из-за ввода данных пользователем в консольную утилиту.
Это доказывает файл filter_with_filename.py, который использует код filter.py, но не использует ввод пользователя. Видно, что после рефакторинга удалось существенно ускорить программу.

filter_with_filename.py

![filter_with_filename](https://user-images.githubusercontent.com/81950751/142760197-24ba0d9d-1da7-474a-aeb9-c1a786927e9e.png)