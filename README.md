# LicDataExtractor

Извлечение регистрационных данных клиента из файла программной лицензии 1С Предприятия.

Утилита пишется по просьбе коллег.

Назначение: извлечение регистрационных данных клиента из файла программной лицензии системы 1С Предприятия.

Технология: Java, JavaFX.

Описание механизма получения данных: http://gogprog.ru/rabota_s_licenziyami_i_klyuchami_1s/license-info-1c.html

По сути, используется консольная утилита ring, распространяемая в составе дистрибутива платформы 1С: Предприятие.

LicDataExtractor служит лишь оберткой над этой утилитой, добавляя следующие удобства:

- нет необходимости использовать командную строку для получения данных;
- регистрационные данные, извлеченные из файла лицензии, показываются в окне на экране, откуда могут быть скопированы;
- регистрационные данные также сохраняются в текстовый файл рядом с файлом лицензии.

Системные требования и ограничения:

- для работы утилиты необходим установленный JRE 1.8 или выше.
- рекомендуется создать временную папку, куда нужно скопировать исследуемый файл лицензии. В папке одновременно может находиться только
  один файл лицензии. Возможно, в будущем это ограничение будет устранено, но пока так.
  
Замеченные проблемы:

- путь к папке не должен содержать пробелов. Если путь содержит пробелы, LicDataExtractor выведет ошибку, хотя сам файл лицензии           корректен. Будет исправлено в следующих релизах.
  
Подготовка к работе:

- выполнить инструкции из статьи http://gogprog.ru/rabota_s_licenziyami_i_klyuchami_1s/license-info-1c.html (шаги 1-4);
- создать временные папки на диске, куда скопировать файлы программных лицензий. В каждой папке должен быть один файл лицензии.
- запустить LicDataExtractor, нажать на кнопку выбора директории и выбрать папку со скопированным файлом лицензии.

Статус: релиз 1.02.

Отказ от ответственности: утилита предоставляется "как есть", автор не несет ответственности за любые проблемы, связанные 
с ее использованием. Хотя и не может такие проблемы себе представить.

Утилита разрабатывается в свободное время, любые замечания и пожелания будут с вниманием/благодарностью выслушаны/прочитаны, 
но не факт, что к чему-то приведут.

Замечания и пожелания пишите на адрес: miller777@mail.ru

Downloads: https://github.com/miller7777777/LicDataExtractor/releases/latest
