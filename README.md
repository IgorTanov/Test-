# Test-
Код необходимо написать максимально коротко и понятно. Прислать код нужно просто в вайбер, в формате <script> ....... </script>.
 

Адрес страницы с которой нужно взять HTML код:

https://www.autoparus.com/registration

Для простоты, там стили стоят прямо в коде.

 

Первый элемент ввода:

Только русские и английские буквы, цифры и пробел если какой-то другой символ то под полем ввода сообщение красным цветом: "Только буквы, цифры и пробел" и сам символ не набирается.

Если первая буква прописная (маленькая) - то она трансформируется в заглавную (большую).

Начинать ввод с пробела нельзя - просто первым пробел не набирается и никаких сообщений не надо.

Два пробела подряд нельзя, просто второй подряд пробел не набирается и никаких сообщений не надо.

После пробела если пользователь набирает букву прописную (маленькую) - то она трансформируется в заглавную (большую).

Максимальное количество символов для ввода 30, как только набирается 30 символ то под полем ввода сообщение красным цветом: Максимум 30 символов и 31символ не набирается и поле валидное для сохранения.

Если тридцатый символ удаляется то надпись-сообщение пропадает.

Если в поле 30 символов но курсор не в поле то надпись тоже не отображается. Если спустя несколько дейтсвий в это поле попадает курсор и тут 30 символов то опять надпись появляется, при удалении одного символа пропадает.

Второй элемент ввода:

Валидация на электронную почту: если поле пустое то валидация не выполняется, если курсор в поле то валидация не выполняется, когда курсор не в поле то проводится валидация на соответствие возможности E-mail адреса.

Если не подходит к условию, то под полем ввода сообщение красным цветом: "Не верный формат E-mail" Если подходит то никаких сообщений.

Третий элемент ввода:

Ввод только цифр и знака "+" : Знак "+" можно набрать только первым и только один раз.

Если набирается первым число, то спереди автоматически подставляется знак "+". максимальное количество цифр 15 - и никаких сообщений не надо - просто запрет на ввод 16 числа.

Четвертый и пятый элементы ввода паролей:

Первый блок ввода пароля, при появлении в нем активности курсора снизу надпись синим цветом: "Минимум 6 символов", при написании шестого и последующего символов надпись пропадает.

Второй блок ввода пароля, при заполнении таким же количеством символов как и в первом поле ввода пароля происходит сравнение значений, если они разные, то сообщение красным: "Некорректный повтор пароля", если они соответствуют друг другу, то сообщение синим: "Корректный повтор пароля" и далее запрет на дальнейший ввод.

Если пользователь кликнет на второе подтверждающее пароль поле, а первое поле пароля не заполнено - то курсор перепрыгивает в него ну и соответственно снизу надпись синяя.

Что-то предусмотреть если потом кто-то решит добавить в верхний еще одно значение (выбрать максимально простое решение)

Кнопка: Подтвердить:

Кнопка не активна пока не будут заполнены все поля. Пока все поля не заполнены и чек бокс не поставлен, кроме того что кнопка не активна , она еще и выглядит гораздо более блекло чем сейчас, как только все поля заполнены и чекбокс отмечен, кнопка становится активной и приобретает нынешний цвет.

Если в капче нет ничего или менее 4 символов - то кнопка не кликабельна.

Поля независимые (можно вначале телефон прописать потом почту, капчу, пароли и в конце имя), и только два поля ввода пароля работают в паре. 

В поле капчи возможность ввода только цифр при наборе пятой цифра красное сообщение;  Только 4 цифры. Пятая цифра не набирается

Во всех элементах отменить браузерное автозаполнение.
