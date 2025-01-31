### Висновки щодо коректності розрахунків

Проаналізувавши результати, отримані з використанням **методу Монте-Карло**, та порівнявши їх із **аналітичними розрахунками**, можна зробити кілька важливих висновків:

#### 1. **Схожість результатів**
- Значення, отримані під час симуляції Монте-Карло, дуже наближені до аналітичних. Наприклад, якщо ймовірність для суми **7** в аналітичному розрахунку становить **16.67%**, то симуляція може показати значення від **16.6%** до **16.8%**. Це свідчить про точне відтворення розподілу ймовірностей у симуляції.

#### 2. **Наявність випадкових відхилень**
- Невеликі відхилення (у межах 0.1%–0.3%) між симуляційними та аналітичними даними виникають через **стохастичну природу** методу Монте-Карло, оскільки цей метод базується на випадкових вибірках. Відхилення зменшується із збільшенням кількості ітерацій.

#### 3. **Збереження тенденцій**
- Попри наявність незначних відхилень, **основні тенденції розподілу ймовірностей залишаються незмінними**: наприклад, як і в аналітичному розрахунку, найвищу ймовірність має сума **7**, а суми **2** і **12** — найнижчу. Значення для сум ближче до **7** також є вищими.

#### 4. **Висновки щодо коректності моделі**
- Оскільки симуляційні результати збігаються з аналітичними в межах допустимих похибок, можна зробити висновок, що:
  - **Метод Монте-Карло точно відображає ймовірності**.
  - Модель роботи двох кубиків реалізована **коректно**.

#### 5. **Практична користь методу Монте-Карло**
- Метод Монте-Карло є корисним інструментом для наближеного обчислення ймовірностей, особливо у випадках складних аналітичних розрахунків. У нашому випадку, де кількість можливих результатів гри з кубиками обмежена, аналітичні ймовірності легко обчислити, але **результати Монте-Карло підтверджують їхню точність**.

---

### Підсумок
Симуляція Монте-Карло забезпечила високу точність, наближену до аналітичних результатів, що підтверджує правильність моделі та розрахунків. Для подальшого зменшення похибки можна збільшити кількість ітерацій у симуляції.
