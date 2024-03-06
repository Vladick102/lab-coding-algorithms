- Лушпак Вікторія (LZ77, LZW)
- Сидорак Владислав (Huffman, звіт та тестування)
У результаті дослідження трьох алгоритмів стиснення даних - LZ77, LZW та алгоритму Хаффмана - ми отримали цікаві висновки щодо їхньої ефективності та застосовності.

LZ77:
Ми провели тестування з різними розмірами буфера та виявили, що збільшення розміру буфера може призвести до збільшення ступеня стиснення.
Проте, великий розмір буфера може призвести до збільшення вимог до пам'яті, що може бути недоцільним для обробки великих обсягів даних.

LZW:
LZW зазвичай працює добре навіть без параметрів налаштування, що робить його привабливим для різних сценаріїв застосування.

Алгоритм Хаффмана:
Хаффман є ефективним для стиснення даних з нерівномірним розподілом символів, особливо на текстових даних.
Його ефективність може залежати від характеру вхідних даних та розміру алфавіту символів.
Ми також виміряли відношення розмірів вихідних та закодованих повідомлень для кожного з алгоритмів, щоб кількісно оцінити їхню ефективність стиснення. 
Ці дані можуть допомогти визначити найкращий алгоритм для конкретних умов застосування, де важливо балансувати між ступенем стиснення та вимогами до пам'яті.
