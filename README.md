# CHECK-LIST

# Bug reports

## Черновик комментария не сохраняется при закрытии полноэкранного просмотра изображения

### Описание проблемы:
При вводе текста в поле комментария в режиме полноэкранного просмотра изображения и последующем закрытии этого режима, введенный текст не сохраняется.

### Шаги воспроизведения:
1. Открыть изображение в полноэкранном режиме
2. Ввести произвольный текст в поле ввода комментария
3. Закрыть полноэкранный режим (нажатием на крестик или кликом вне области изображения)
4. Открыть комментарии под этим же изображением в ленте

### Окружение: 
* **Платформа:** Web версия
* **ОС:** macOS
* **Браузер:** Yandex Browser 


### Фактический результат:
Поле ввода комментария пустое, введенный текст не сохраняется **[Файл first_bug.mp4]**

### Ожидаемый результат:
В поле ввода комментария отображается ранее введенный текст 

https://github.com/user-attachments/assets/4b2db7aa-1bb1-4f96-98cc-f8437377e0d3

## Несогласованность состояния комментариев между лентой и полноэкранным просмотром

### Описание проблемы:
При удалении комментария в полноэкранном просмотре изображения, изменение не синхронизируется с лентой - удаленный комментарий продолжает отображаться под постом.
### Шаги воспроизведения:
1. В ленте: открыть комментарии под изображением
2. Добавить новый комментарий
3. Открыть это же изображение в полноэкранном режиме
4. В полноэкранном режиме найти и удалить добавленный комментарий
5. Закрыть полноэкранный режим 

### Окружение: 
* **Платформа:** Web версия
* **ОС:** macOS
* **Браузер:** Yandex Browser 


### Фактический результат:
Комментарий отображается и видна подсказка "Ваш комментарий удалён"  **[Файл second_bug]**

### Ожидаемый результат:
Комментарий должен быть удален как в полноэкранном режиме, так и в ленте

https://github.com/user-attachments/assets/10cd521a-2e8a-40b7-98a1-4bbf973e6d42


