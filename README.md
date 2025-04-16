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


## Удаленный в полноэкранном режиме комментарий продолжает отображаться в ленте

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


## Изменения комментария в полноэкранном режиме не отражаются в ленте

### Описание проблемы:
При редактировании комментария в полноэкранном режиме просмотра изображения изменения не синхронизируются с лентой - в ленте продолжает отображаться оригинальная версия комментария.

### Шаги воспроизведения:
1. В ленте: добавить новый комментарий к изображению
2. Открыть изображение в полноэкранном режиме
3. Нажать "Редактировать" у добавленного комментария
4. Изменить текст
5. Сохранить изменения
6. Закрыть полноэкранный режим

### Окружение: 
* **Платформа:** Web версия
* **ОС:** macOS
* **Браузер:** Yandex Browser 


### Фактический результат:
В полноэкранном режиме: комментарий измене, в ленте: остается первоначальная версия комментария  **[Файл third_bug]**

### Ожидаемый результат:
Во всех режимах отображается измененная версия комментария

https://github.com/user-attachments/assets/ded49170-7a4b-4b8b-aa8b-ac8b613b1540



