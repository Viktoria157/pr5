[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/hlhiSF65)
# 📘 Практична робота 5: Математичні формули та таблиці в LaTeX

---

## 🎯 Мета роботи
Навчитися:
- створювати математичні формули в LaTeX  
- використовувати різні типи формул  
- створювати таблиці  
- працювати з GitHub  

---

## 📂 Завдання

### 🔹 Крок 1. Отримання репозиторію
1. Перейдіть за посиланням GitHub Classroom  
2. Натисніть **Accept assignment**  
3. Клонуйте репозиторій  

---

### 🔹 Крок 2. Відкриття файлу
1. Запустіть TeXmaker  
2. Відкрийте файл `.tex`

---

### 🔹 Крок 3. Налаштування преамбули

```latex
\documentclass[12pt]{article}
\usepackage[T2A]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage[ukrainian]{babel}
\usepackage{amsmath, amssymb}
\usepackage{array}

\title{Практична робота: Математичні формули}
\author{Ваше ім'я}
\date{\today}
```

---

### 🔹 Крок 4. Структура документа

```latex
\begin{document}

\maketitle

\section*{Квадратне рівняння}
```

---

### 🔹 Крок 5. Формули

✔ Додайте:
- формулу в тексті `$...$`  
- формулу в окремому рядку (`equation`)  
- вирівняні формули (`align`)  

Приклад:

```latex
\begin{equation}
ax^2 + bx + c = 0
\end{equation}
```

---

### 🔹 Крок 6. Таблиці

✔ Створіть:
- просту таблицю 3×3  
- таблицю з формулами  

```latex
\begin{tabular}{|c|c|c|}
\hline
1 & 2 & 3 \\
\hline
4 & 5 & 6 \\
\hline
\end{tabular}
```

---

### 🔹 Крок 7. Компіляція
1. Натисніть **Quick Build**  
2. Перевірте PDF  

---

### 🔹 Крок 8. Завантаження в GitHub

```bash
git add .
git commit -m "Практична робота виконана"
git push
```

---

## 📤 Що здати
У репозиторії мають бути:
- `main.tex` (або ваш `.tex` файл)  
- `.pdf` файл  

---

## ✅ Чек-лист

- [ ] Документ компілюється  
- [ ] Є формули  
- [ ] Є таблиці  
- [ ] Є PDF  
- [ ] Завантажено в GitHub  

---

## 💡 Порада
Перевіряйте лог помилок у TeXmaker.
