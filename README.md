# SQLi-detection-using-Graph-Attention-Network
Этот проект сделан как часть научно-исследовательской работы.

Код полностью написал AI.

Цель проекта: увеличение эффективности детектирования sql-инъекций, используя графовую нейронную сеть.

Стек технологий: PyTorch Geometric, Pandas, Scikit-learn, Numpy.

Результаты которые удалось получить:

| Датасет (строк) | Accuracy | Precision | Recall | F1-Score |
|:--- |:---:|:---:|:---:|:---:|
| 32 695 | 98.4% | 0.988 | 0.980 | **0.983984** |
| 33 726 | 97.9% | 0.946 | 0.996 | **0.970356** |

Матрицы ошибок:

<img width="615" height="413" alt="image" src="https://github.com/user-attachments/assets/fc9a46fd-aa81-4837-b3e0-09155c97d7ec" />

<img width="616" height="413" alt="image" src="https://github.com/user-attachments/assets/ed0da21c-6271-4432-8818-015c1c77853d" />


How to use:

Код программы, файл модели и дополнительные файлы расположены на google drive:

https://drive.google.com/drive/folders/1A5I4VG-Elx1-wtpLLbpPd8ZC4BBrJFrJ?usp=sharing

