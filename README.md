# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <table style="border-collapse: collapse; width: 100%; height: 696px;" border="1">
        <tbody>
        <tr style="height: 24px;">
        <td style="width: 100%; height: 24px; text-align: center;" colspan="2"><strong><span class="bbc_u">Файловые команды</span></strong></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>ls</strong><strong><span class="bbc_u">
        </span></strong></td>
        <td style="width: 75%; height: 24px;">список файлов и каталогов</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>ls -al
        </strong></td>
        <td style="width: 75%; height: 24px;">форматированный список со скрытыми каталогами и файлами</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>cd dir</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">сменить директорию на dir</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>cd</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">сменить на домашний каталог</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>pwd</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">показать текущий каталог</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>mkdir dir</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">создать каталог dir</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>rm file</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">удалить file</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>rm -r dir</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">удалить каталог dir</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>rm -f file</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">удалить форсированно file</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>rm -rf dir</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">удалить форсированно каталог dir</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>cp file1 file2</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">скопировать file1 в file2</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>cp -r dir1 dir2</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">скопировать dir1 в dir2; создаст каталог dir2, если он не существует</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>mv file1 file2</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">переименовать или переместить file1 в file2. если file2 существующий каталог - переместить file1 в каталог file2</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>ln -s file link</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">создать символическую ссылку link к файлу file</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>touch file</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">создать file</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>cat &gt; file</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">направить стандартный ввод в file</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>more file</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">вывести содержимое file</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>head file</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">вывести первые 10 строк file</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>tail file</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">вывести последние 10 строк file</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>tail -f file</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">вывести содержимое file по мере роста, начинает с последних 10 строк</td>
        </tr>
        <tr style="height: 168px;">
        <td style="width: 25%; height: 168px;"><strong>chmod octal file</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 168px;">сменить права file на octal, раздельно для пользователя, группы и для всех добавлением:
        4 – чтение (r)
        2 – запись (w)
        1 – исполнение (x)<em>Примеры</em>:
        <strong>chmod 777</strong> – чтение, запись, исполнение для всех
        <strong>chmod 755</strong> – rwx для владельца, rx для группы и остальных.
        Дополнительные опции: <strong>man chmod</strong>.</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 25%; height: 24px;"><strong>iconv</strong><strong>
        </strong></td>
        <td style="width: 75%; height: 24px;">смена кодировки текстовых файлов</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.9275%;" border="1">
        <tbody>
        <tr>
        <td style="width: 99.9275%; text-align: center;" colspan="2"><strong>Просмотр содержимого файлов</strong></td>
        </tr>
        <tr>
        <td style="width: 20.6582%;"><strong>cat file1</strong></td>
        <td style="width: 79.2693%;">вывести содержимое файла file1 на стандартное устройство вывода</td>
        </tr>
        <tr>
        <td style="width: 20.6582%;"><strong>tac file1</strong></td>
        <td style="width: 79.2693%;">вывести содержимое файла file1 на стандартное устройство вывода в обратном порядке (последняя строка становиться первой и т.д.)</td>
        </tr>
        <tr>
        <td style="width: 20.6582%;"><strong>more file1</strong></td>
        <td style="width: 79.2693%;">постраничный вывод содержимого файла file1 на стандартное устройство вывода</td>
        </tr>
        <tr>
        <td style="width: 20.6582%;"><strong>less file1</strong></td>
        <td style="width: 79.2693%;">постраничный вывод содержимого файла file1 на стандартное устройство вывода, но с возможностью пролистывания в обе стороны (вверх-вниз), поиска по содержимому и т.п.</td>
        </tr>
        <tr>
        <td style="width: 20.6582%;"><strong>head -2 file1</strong></td>
        <td style="width: 79.2693%;">вывести первые две строки файла file1 на стандартное устройство вывода. По-умолчанию выводится десять строк</td>
        </tr>
        <tr>
        <td style="width: 20.6582%;"><strong>tail -2 file1</strong></td>
        <td style="width: 79.2693%;">вывести последние две строки файла file1 на стандартное устройство вывода. По-умолчанию выводится десять строк</td>
        </tr>
        <tr>
        <td style="width: 20.6582%;"><strong>tail -f /var/log/messages</strong></td>
        <td style="width: 79.2693%;">выводить содержимое файла /var/log/messages на стандартное устройство вывода по мере появления в нём текста.</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.9275%;" border="1">
        <tbody>
        <tr>
        <td style="width: 99.9275%; text-align: center;" colspan="2"><strong>Манипуляции с текстом</strong></td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>cat file_originale | [operation: sed, grep, awk, grep и т.п.] &gt; result.txt</strong></td>
        <td style="width: 71.5011%;">общий синтаксис выполнения действий по обработке содержимого файла и вывода результата в новый</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>cat file_originale | [operazione: sed, grep, awk, grepи т.п.] &gt;&gt; result.txt</strong></td>
        <td style="width: 71.5011%;">общий синтаксис выполнения действий по обработке содержимого файла и вывода результата в существующий файл. Если файл не существует, он будет создан</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>grep Aug /var/log/messages</strong></td>
        <td style="width: 71.5011%;">из файла '/var/log/messages' отобрать и вывести на стандартное устройство вывода строки, содержащие "Aug"</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>grep ^Aug /var/log/messages</strong></td>
        <td style="width: 71.5011%;">из файла '/var/log/messages' отобрать и вывести на стандартное устройство вывода строки, начинающиеся на "Aug"</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>grep [0-9] /var/log/messages</strong></td>
        <td style="width: 71.5011%;">из файла '/var/log/messages' отобрать и вывести на стандартное устройство вывода строки, содержащие цифры</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>grep Aug -R /var/log/*</strong></td>
        <td style="width: 71.5011%;">отобрать и вывести на стандартное устройство вывода строки, содержащие "Aug", во всех файлах, находящихся в директории /var/log и ниже</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sed 's/stringa1/stringa2/g' example.txt</strong></td>
        <td style="width: 71.5011%;">в файле example.txt заменить "string1" на "string2", результат вывести на стандартное устройство вывода.</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sed '/^$/d' example.txt</strong></td>
        <td style="width: 71.5011%;">удалить пустые строки из файла example.txt</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sed '/ *#/d; /^$/d' example.txt</strong></td>
        <td style="width: 71.5011%;">удалить пустые строки и комментарии из файла example.txt</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>echo 'esempio' | tr '[:lower:]' '[:upper:]'</strong></td>
        <td style="width: 71.5011%;">преобразовать символы из нижнего регистра в верхний</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sed -e '1d' result.txt</strong></td>
        <td style="width: 71.5011%;">удалить первую строку из файла example.txt</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sed -n '/string1/p'</strong></td>
        <td style="width: 71.5011%;">отобразить только строки содержашие "string1"</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sed -e 's/ *$//' example.txt</strong></td>
        <td style="width: 71.5011%;">удалить пустые символы в в конце каждой строки</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sed -e 's/string1//g' example.txt</strong></td>
        <td style="width: 71.5011%;">удалить строку "string1" из текста не изменяя всего остального</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sed -n '1,8p;5q' example.txt</strong></td>
        <td style="width: 71.5011%;">взять из файла с первой по восьмую строки и из них вывести первые пять</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sed -n '5p;5q' example.txt</strong></td>
        <td style="width: 71.5011%;">вывести пятую строку</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sed -e 's/0*/0/g' example.txt</strong></td>
        <td style="width: 71.5011%;">заменить последовательность из любого количества нулей одним нулём</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>cat -n file1</strong></td>
        <td style="width: 71.5011%;">пронумеровать строки при выводе содержимого файла</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>cat example.txt | awk 'NR%2==1'</strong></td>
        <td style="width: 71.5011%;">при выводе содержимого файла, не выводить чётные строки файла</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>echo a b c | awk '{print $1}'</strong></td>
        <td style="width: 71.5011%;">вывести первую колонку. Разделение, по-умолчанию, по проблелу/пробелам или символу/символам табуляции</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>echo a b c | awk '{print $1,$3}'</strong></td>
        <td style="width: 71.5011%;">вывести первую и треью колонки. Разделение, по-умолчанию, по проблелу/пробелам или символу/символам табуляции</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>paste file1 file2</strong></td>
        <td style="width: 71.5011%;">объединить содержимое file1 и file2 в виде таблицы: строка 1 из file1 = строка 1 колонка 1-n, строка 1 из file2 = строка 1 колонка n+1-m</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>paste -d '+' file1 file2</strong></td>
        <td style="width: 71.5011%;">объединить содержимое file1 и file2 в виде таблицы с разделителем "+"</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sort file1 file2</strong></td>
        <td style="width: 71.5011%;">отсортировать содержимое двух файлов</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sort file1 file2 | uniq</strong></td>
        <td style="width: 71.5011%;">отсортировать содержимое двух файлов, не отображая повторов</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sort file1 file2 | uniq -u</strong></td>
        <td style="width: 71.5011%;">отсортировать содержимое двух файлов, отображая только уникальные строки (строки, встречающиеся в обоих файлах, не выводятся на стандартное устройство вывода)</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>sort file1 file2 | uniq -d</strong></td>
        <td style="width: 71.5011%;">отсортировать содержимое двух файлов, отображая только повторяющиеся строки</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>comm -1 file1 file2</strong></td>
        <td style="width: 71.5011%;">сравнить содержимое двух файлов, не отображая строки принадлежащие файлу 'file1'</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>comm -2 file1 file2</strong></td>
        <td style="width: 71.5011%;">сравнить содержимое двух файлов, не отображая строки принадлежащие файлу 'file2'</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>comm -3 file1 file2</strong></td>
        <td style="width: 71.5011%;">сравнить содержимое двух файлов, удаляя строки встречающиеся в обоих файлах</td>
        </tr>
        <tr>
        <td style="width: 99.9275%; text-align: center;" colspan="2"><strong>Преобразование наборов символов и файловых форматов</strong></td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>dos2unix filedos.txt fileunix.txt</strong></td>
        <td style="width: 71.5011%;">конвертировать файл текстового формата из MSDOS в UNIX (разница в символах возврата каретки)</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>unix2dos fileunix.txt filedos.txt</strong></td>
        <td style="width: 71.5011%;">конвертировать файл текстового формата из UNIX в MSDOS (разница в символах возврата коретки)</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>recode ..HTML &lt; page.txt &gt; page.html</strong></td>
        <td style="width: 71.5011%;">конвертировать содержимое тестового файла page.txt в html-файл page.html</td>
        </tr>
        <tr>
        <td style="width: 28.4264%;"><strong>recode -l | more</strong></td>
        <td style="width: 71.5011%;">вывести список доступных форматов</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.8913%; height: 696px;" border="1">
        <tbody>
        <tr style="height: 24px;">
        <td style="width: 99.8913%; text-align: center; height: 24px;" colspan="2"><strong>Файлы и директории</strong></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>cd /home</strong></td>
        <td style="width: 79.4054%; height: 24px;">перейти в директорию '/home'</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>cd ..</strong></td>
        <td style="width: 79.4054%; height: 24px;">перейти в директорию уровнем выше</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>cd ../..</strong></td>
        <td style="width: 79.4054%; height: 24px;">перейти в директорию двумя уровнями выше</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>cd</strong></td>
        <td style="width: 79.4054%; height: 24px;">перейти в домашнюю директорию</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>cd ~user</strong></td>
        <td style="width: 79.4054%; height: 24px;">перейти в домашнюю директорию пользователя user</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>cd -</strong></td>
        <td style="width: 79.4054%; height: 24px;">перейти в директорию, в которой находились до перехода в текущую директорию</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>pwd</strong></td>
        <td style="width: 79.4054%; height: 24px;">показать текущую директорию</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>ls</strong></td>
        <td style="width: 79.4054%; height: 24px;">отобразить содержимое текущей директории</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>ls -F</strong></td>
        <td style="width: 79.4054%; height: 24px;">отобразить содержимое текущей директории с добавлением к именам символов, храктеризующих тип</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>ls -l</strong></td>
        <td style="width: 79.4054%; height: 24px;">показать детализированное представление файлов и директорий в текущей директории</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>ls -a</strong></td>
        <td style="width: 79.4054%; height: 24px;">показать скрытые файлы и директории в текущей директории</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>ls *[0-9]*</strong></td>
        <td style="width: 79.4054%; height: 24px;">показать файлы и директории содержащие в имени цифры</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>tree</strong></td>
        <td style="width: 79.4054%; height: 24px;">показать дерево файлов и директорий, начиная от корня (/)</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>mkdir dir1</strong></td>
        <td style="width: 79.4054%; height: 24px;">создать директорию с именем 'dir1'</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>mkdir dir1 dir2</strong></td>
        <td style="width: 79.4054%; height: 24px;">создать две директории одновременно</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>mkdir -p /tmp/dir1/dir2</strong></td>
        <td style="width: 79.4054%; height: 24px;">создать дерево директорий</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>rm -f file1</strong></td>
        <td style="width: 79.4054%; height: 24px;">удалить файл с именем 'file1'</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>rmdir dir1</strong></td>
        <td style="width: 79.4054%; height: 24px;">удалить директорию с именем 'dir1'</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>rm -rf dir1</strong></td>
        <td style="width: 79.4054%; height: 24px;">удалить директорию с именем 'dir1' и рекурсивно всё её содержимое</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>rm -rf dir1 dir2</strong></td>
        <td style="width: 79.4054%; height: 24px;">удалить две директории и рекурсивно их содержимое</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>mv dir1 new_dir</strong></td>
        <td style="width: 79.4054%; height: 24px;">переименовать или переместить файл или директорию</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>cp file1 file2</strong></td>
        <td style="width: 79.4054%; height: 24px;">скопировать файл file1 в файл file2</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>cp dir/* .</strong></td>
        <td style="width: 79.4054%; height: 24px;">копировать все файлы директории dir в текущую директорию</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>cp -a /tmp/dir1 .</strong></td>
        <td style="width: 79.4054%; height: 24px;">копировать директорию dir1 со всем содержимым в текущую директорию</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>cp -a dir1 dir2</strong></td>
        <td style="width: 79.4054%; height: 24px;">копировать директорию dir1 в директорию dir2</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>ln -s file1 lnk1</strong></td>
        <td style="width: 79.4054%; height: 24px;">создать символическую ссылку на файл или директорию</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>ln file1 lnk1</strong></td>
        <td style="width: 79.4054%; height: 24px;">создать "жёсткую" (физическую) ссылку на файл или директорию</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.4859%; height: 24px;"><strong>touch -t 0712250000 fileditest</strong></td>
        <td style="width: 79.4054%; height: 24px;">модифицировать дату и время создания файла, при его отсутствии, создать файл с указанными датой и временем (YYMMDDhhmm)</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.9275%;" border="1">
        <tbody>
        <tr>
        <td style="width: 99.9275%; text-align: center;" colspan="2"><strong>CDROM</strong></td>
        </tr>
        <tr>
        <td style="width: 36.5343%;"><strong>cdrecord -v gracetime=2 dev=/dev/cdrom -eject blank=fast -force</strong></td>
        <td style="width: 63.3932%;">clean a rewritable cdrom</td>
        </tr>
        <tr>
        <td style="width: 36.5343%;"><strong>mkisofs /dev/cdrom &gt; cd.iso</strong></td>
        <td style="width: 63.3932%;">create an iso image of cdrom on disk</td>
        </tr>
        <tr>
        <td style="width: 36.5343%;"><strong>mkisofs /dev/cdrom | gzip &gt; cd_iso.gz</strong></td>
        <td style="width: 63.3932%;">create a compressed iso image of cdrom on disk</td>
        </tr>
        <tr>
        <td style="width: 36.5343%;"><strong>mkisofs -J -allow-leading-dots -R -V "Label CD" -iso-level 4 -o ./cd.iso data_cd</strong></td>
        <td style="width: 63.3932%;">create an iso image of a directory</td>
        </tr>
        <tr>
        <td style="width: 36.5343%;"><strong>cdrecord -v dev=/dev/cdrom cd.iso</strong></td>
        <td style="width: 63.3932%;">burn an ISO image</td>
        </tr>
        <tr>
        <td style="width: 36.5343%;"><strong>gzip -dc cd_iso.gz | cdrecord dev=/dev/cdrom -</strong></td>
        <td style="width: 63.3932%;">burn a compressed ISO image</td>
        </tr>
        <tr>
        <td style="width: 36.5343%;"><strong>mount -o loop cd.iso /mnt/iso</strong></td>
        <td style="width: 63.3932%;">mount an ISO image</td>
        </tr>
        <tr>
        <td style="width: 36.5343%;"><strong>cd-paranoia -B</strong></td>
        <td style="width: 63.3932%;">rip audio tracks from a CD to wav files</td>
        </tr>
        <tr>
        <td style="width: 36.5343%;"><strong>cd-paranoia -- "-3"</strong></td>
        <td style="width: 63.3932%;">rip first three audio tracks from a CD to wav files</td>
        </tr>
        <tr>
        <td style="width: 36.5343%;"><strong>cdrecord --scanbus</strong></td>
        <td style="width: 63.3932%;">scan bus to identify the channel scsi</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.9275%;" border="1">
        <tbody>
        <tr>
        <td style="width: 99.9275%; text-align: center;" colspan="2"><strong>Специальные атрибуты файлов</strong></td>
        </tr>
        <tr>
        <td style="width: 20.8795%;"><strong>chattr +a file1</strong></td>
        <td style="width: 79.048%;">позволить открывать файл на запись только в режиме добавления</td>
        </tr>
        <tr>
        <td style="width: 20.8795%;"><strong>chattr +c file1</strong></td>
        <td style="width: 79.048%;">позволяет ядру автоматически сжимать/разжимать содержимое файла.</td>
        </tr>
        <tr>
        <td style="width: 20.8795%;"><strong>chattr +d file1</strong></td>
        <td style="width: 79.048%;">указавет утилите dump игнорировать данный файл во время выполнения backup'а</td>
        </tr>
        <tr>
        <td style="width: 20.8795%;"><strong>chattr +i file1</strong></td>
        <td style="width: 79.048%;">делает файл недоступным для любых изменений: редактирование, удаление, перемещение, создание линков на него.</td>
        </tr>
        <tr>
        <td style="width: 20.8795%;"><strong>chattr +s file1</strong></td>
        <td style="width: 79.048%;">позволяет сделать удаление файла безопасным, т.е. выставленный атрибут s говорит о том, что при удалении файла, место, занимаемое файлом на диске заполняется нулями, что предотвращяет возможность восстановления данных.</td>
        </tr>
        <tr>
        <td style="width: 20.8795%;"><strong>chattr +S file1</strong></td>
        <td style="width: 79.048%;">указывает, что, при сохранении изменений, будет произведена синхронизация, как при выполнении команды sync</td>
        </tr>
        <tr>
        <td style="width: 20.8795%;"><strong>chattr +u file1</strong></td>
        <td style="width: 79.048%;">данный атрибут указывает, что при удалении файла содержимое его будет сохранено и при необходимости пользователь сможет его восстановить</td>
        </tr>
        <tr>
        <td style="width: 20.8795%;"><strong>lsattr</strong></td>
        <td style="width: 79.048%;">показать атрибуты файлов</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.9274%; height: 456px;" border="1">
        <tbody>
        <tr style="height: 24px;">
        <td style="width: 99.9274%; text-align: center; height: 24px;" colspan="2"><strong>Выставление/изменение полномочий на файлы</strong></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>ls -lh</strong></td>
        <td style="width: 79.5311%; height: 24px;">просмотр полномочий на файлы и директории в текущей директории</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>ls /tmp | pr -T5 -W$COLUMNS</strong></td>
        <td style="width: 79.5311%; height: 24px;">вывести содержимое директории /tmp и разделить вывод на пять колонок</td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 20.3963%; height: 48px;"><strong>chmod ugo+rwx directory1</strong></td>
        <td style="width: 79.5311%; height: 48px;">добавить полномочия на директорию directory1 ugo(User Group Other)+rwx(Read Write eXecute) - всем полные права. Аналогичное можно сделать таким образом <em>chmod 777 directory1</em></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>chmod go-rwx directory1</strong></td>
        <td style="width: 79.5311%; height: 24px;">отобрать у группы и всех остальных все полномочия на директорию directory1.</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>chown user1 file1</strong></td>
        <td style="width: 79.5311%; height: 24px;">назначить владельцем файла file1 пользователя user1</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>chown -R user1 directory1</strong></td>
        <td style="width: 79.5311%; height: 24px;">назначить рекурсивно владельцем директории directory1 пользователя user1</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>chgrp group1 file1</strong></td>
        <td style="width: 79.5311%; height: 24px;">сменить группу-владельца файла file1 на group1</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>chown user1:group1 file1</strong></td>
        <td style="width: 79.5311%; height: 24px;">сменить владельца и группу владельца файла file1</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>find / -perm -u+s</strong></td>
        <td style="width: 79.5311%; height: 24px;">найти, начиная от корня, все файлы с выставленным SUID</td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 20.3963%; height: 48px;"><strong>chmod u+s /bin/binary_file</strong></td>
        <td style="width: 79.5311%; height: 48px;">назначить SUID-бит файлу /bin/binary_file. Это даёт возможность любому пользователю запускать на выполнение файл с полномочиями владельца файла.</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>chmod u-s /bin/binary_file</strong></td>
        <td style="width: 79.5311%; height: 24px;">снять SUID-бит с файла /bin/binary_file.</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>chmod g+s /home/public</strong></td>
        <td style="width: 79.5311%; height: 24px;">назначить SGID-бит директории /home/public.</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>chmod g-s /home/public</strong></td>
        <td style="width: 79.5311%; height: 24px;">снять SGID-бит с директории /home/public.</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>chmod o+t /home/public</strong></td>
        <td style="width: 79.5311%; height: 24px;">назначить STIKY-бит директории /home/public. Позволяет удалять файлы только владельцам</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3963%; height: 24px;"><strong>chmod o-t /home/public</strong></td>
        <td style="width: 79.5311%; height: 24px;">снять STIKY-бит с директории /home/public</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.9274%;" border="1">
        <tbody>
        <tr>
        <td style="width: 99.9274%; text-align: center;" colspan="2"><strong>Монтирование файловых систем</strong></td>
        </tr>
        <tr>
        <td style="width: 20.8294%;"><strong>mount /dev/hda2 /mnt/hda2</strong></td>
        <td style="width: 79.098%;">монтирует раздел 'hda2' в точку монтирования '/mnt/hda2'. Убедитесь в наличии директории-точки монтирования '/mnt/hda2'</td>
        </tr>
        <tr>
        <td style="width: 20.8294%;"><strong>umount /dev/hda2</strong></td>
        <td style="width: 79.098%;">размонтирует раздел 'hda2'. Перед выполнением, покиньте '/mnt/hda2'</td>
        </tr>
        <tr>
        <td style="width: 20.8294%;"><strong>fuser -km /mnt/hda2</strong></td>
        <td style="width: 79.098%;">принудительное размонтирование раздела. Применяется в случае, когда раздел занят каким-либо пользователем</td>
        </tr>
        <tr>
        <td style="width: 20.8294%;"><strong>umount -n /mnt/hda2</strong></td>
        <td style="width: 79.098%;">выполнить размонитрование без занесения информации в /etc/mtab. Полезно когда файл имеет атрибуты "только чтение" или недостаточно места на диске</td>
        </tr>
        <tr>
        <td style="width: 20.8294%;"><strong>mount /dev/fd0 /mnt/floppy</strong></td>
        <td style="width: 79.098%;">монтировать флоппи-диск</td>
        </tr>
        <tr>
        <td style="width: 20.8294%;"><strong>mount /dev/cdrom /mnt/cdrom</strong></td>
        <td style="width: 79.098%;">монтировать CD или DVD</td>
        </tr>
        <tr>
        <td style="width: 20.8294%;"><strong>mount /dev/hdc /mnt/cdrecorder</strong></td>
        <td style="width: 79.098%;">монтировать CD-R/CD-RW или DVD-R/DVD-RW(+-)</td>
        </tr>
        <tr>
        <td style="width: 20.8294%;"><strong>mount -o loop file.iso /mnt/cdrom</strong></td>
        <td style="width: 79.098%;">смонтировать ISO-образ</td>
        </tr>
        <tr>
        <td style="width: 20.8294%;"><strong>mount -t vfat /dev/hda5 /mnt/hda5</strong></td>
        <td style="width: 79.098%;">монтировать файловую систему Windows FAT32</td>
        </tr>
        <tr>
        <td style="width: 20.8294%;"><strong>mount -t smbfs -o username=user,password=pass //winclient/share /mnt/share</strong></td>
        <td style="width: 79.098%;">монтировать сетевую файловую систему Windows (SMB/CIFS)</td>
        </tr>
        <tr>
        <td style="width: 20.8294%;"><strong>mount -o bind /home/user/prg /var/ftp/user</strong></td>
        <td style="width: 79.098%;">"монтирует" директорию в директорию (binding). Доступна с версии ядра 2.4.0. Полезна, например, для предоставления содержимого пользовательской директории через ftp при работе ftp-сервера в "песочнице" (chroot), когда симлинки сделать невозможно. Выполнение данной команды сделает копию содержимого /home/user/prg в /var/ftp/user</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.9275%;" border="1">
        <tbody>
        <tr>
        <td style="width: 99.9275%; text-align: center;" colspan="2"><strong>Дисковое пространство</strong></td>
        </tr>
        <tr>
        <td style="width: 21.0904%;"><strong>df -h</strong></td>
        <td style="width: 78.8371%;">отображает информацию о смонтированных разделах с отображением общего, доступного и используемого пространства <em>(Прим.переводчика. ключ -h работает не во всех *nix системах)</em></td>
        </tr>
        <tr>
        <td style="width: 21.0904%;"><strong>ls -lSr |more</strong></td>
        <td style="width: 78.8371%;">выдаёт список файлов и директорий рекурсивно с сортировкой по возрастанию размера и позволяет осуществлять постраничный просмотр</td>
        </tr>
        <tr>
        <td style="width: 21.0904%;"><strong>du -sh dir1</strong></td>
        <td style="width: 78.8371%;">подсчитывает и выводит размер, занимаемый директорией 'dir1' <em>(Прим.переводчика. ключ -h работает не во всех *nix системах)</em></td>
        </tr>
        <tr>
        <td style="width: 21.0904%;"><strong>du -sk * | sort -rn</strong></td>
        <td style="width: 78.8371%;">отображает размер и имена файлов и директорий, с соритровкой по размеру</td>
        </tr>
        <tr>
        <td style="width: 21.0904%;"><strong>rpm -q -a --qf '%10{SIZE}t%{NAME}n' | sort -k1,1n</strong></td>
        <td style="width: 78.8371%;">показывает размер используемого дискового пространства, занимаемое файлами rpm-пакета, с сортировкой по размеру (fedora, redhat и т.п.)</td>
        </tr>
        <tr>
        <td style="width: 21.0904%;"><strong>dpkg-query -W -f='${Installed-Size;10}t${Package}n' | sort -k1,1n</strong></td>
        <td style="width: 78.8371%;">показывает размер используемого дискового пространства, занимаемое файлами deb-пакета, с сортировкой по размеру (ubuntu, debian т.п.)</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.9275%;" border="1">
        <tbody>
        <tr>
        <td style="width: 99.9275%; text-align: center;" colspan="2"><strong>Анализ файловых систем</strong></td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>badblocks -v /dev/hda1</strong></td>
        <td style="width: 67.0051%;">проверить раздел hda1 на наличие bad-блоков</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>fsck /dev/hda1</strong></td>
        <td style="width: 67.0051%;">проверить/восстановить целостность linux-файловой системы раздела hda1</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>fsck.ext2 /dev/hda1</strong></td>
        <td style="width: 67.0051%;">проверить/восстановить целостность файловой системы ext2 раздела hda1</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>e2fsck /dev/hda1</strong></td>
        <td style="width: 67.0051%;"></td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>e2fsck -j /dev/hda1</strong></td>
        <td style="width: 67.0051%;">проверить/восстановить целостность файловой системы ext3 раздела hda1 с указанием, что журнал расположен там же</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>fsck.ext3 /dev/hda1</strong></td>
        <td style="width: 67.0051%;">проверить/восстановить целостность файловой системы ext3 раздела hda1</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>fsck.vfat /dev/hda1</strong></td>
        <td style="width: 67.0051%;">проверить/восстановить целостность файловой системы fat раздела hda11</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>fsck.msdos /dev/hda1</strong></td>
        <td style="width: 67.0051%;"></td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>dosfsck /dev/hda1</strong></td>
        <td style="width: 67.0051%;"></td>
        </tr>
        <tr>
        <td style="width: 99.9275%; text-align: center;" colspan="2"><strong>Форматирование файловых систем</strong></td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>mkfs /dev/hda1</strong></td>
        <td style="width: 67.0051%;">создать linux-файловую систему на разделе hda1</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>mke2fs /dev/hda1</strong></td>
        <td style="width: 67.0051%;">создать файловую систему ext2 на разделе hda1</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>mke2fs -j /dev/hda1</strong></td>
        <td style="width: 67.0051%;">создать журналирующую файловую систему ext3 на разделе hda1</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>mkfs -t vfat 32 -F /dev/hda1</strong></td>
        <td style="width: 67.0051%;">создать файловую систему FAT32 на разделе hda1</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>fdformat -n /dev/fd0</strong></td>
        <td style="width: 67.0051%;">форматирование флоппи-диска без проверки</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>mkswap /dev/hda3</strong></td>
        <td style="width: 67.0051%;">создание swap-пространства на разделе hda3</td>
        </tr>
        <tr>
        <td style="width: 99.9275%; text-align: center;" colspan="2"><strong>swap-пространство</strong></td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>mkswap /dev/hda3</strong></td>
        <td style="width: 67.0051%;">создание swap-пространства на разделе hda3</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>swapon /dev/hda3</strong></td>
        <td style="width: 67.0051%;">активировать swap-пространство, расположенное на разделе hda3</td>
        </tr>
        <tr>
        <td style="width: 32.9224%;"><strong>swapon /dev/hda2 /dev/hdb3</strong></td>
        <td style="width: 67.0051%;">активировать swap-пространства, расположенные на разделах hda2 и hdb3</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 100%;" border="1">
        <tbody>
        <tr>
        <td style="width: 100%; text-align: center;" colspan="2"><strong><span class="bbc_u">Управление процессами</span></strong></td>
        </tr>
        <tr>
        <td style="width: 20.1233%;"><strong>ps</strong></td>
        <td style="width: 79.8767%;">вывести ваши текущие активные процессы</td>
        </tr>
        <tr>
        <td style="width: 20.1233%;"><strong>top</strong><strong>
        </strong></td>
        <td style="width: 79.8767%;">показать все запущенные процессы</td>
        </tr>
        <tr>
        <td style="width: 20.1233%;"><strong>kill pid</strong><strong>
        </strong></td>
        <td style="width: 79.8767%;">убить процесс с id pid</td>
        </tr>
        <tr>
        <td style="width: 20.1233%;"><strong>killall proc</strong><strong>
        </strong></td>
        <td style="width: 79.8767%;">убить все процессы с именем proc</td>
        </tr>
        <tr>
        <td style="width: 20.1233%;"><strong>bg</strong><strong>
        </strong></td>
        <td style="width: 79.8767%;">список остановленных и фоновых задач; продолжить выполнение остановленной задачи в фоне</td>
        </tr>
        <tr>
        <td style="width: 20.1233%;"><strong>fg</strong><strong>
        </strong></td>
        <td style="width: 79.8767%;">выносит на передний план последние задачи</td>
        </tr>
        <tr>
        <td style="width: 20.1233%;"><strong>fg n</strong><strong>
        </strong></td>
        <td style="width: 79.8767%;">вынести задачу n на передний план</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 100%; height: 72px;" border="1">
        <tbody>
        <tr style="height: 24px;">
        <td style="width: 100%; text-align: center; height: 24px;" colspan="2"><strong><span class="bbc_u">SSH</span></strong></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3408%; height: 24px;"><strong>ssh user@host</strong></td>
        <td style="width: 79.6592%; height: 24px;">подключится к <strong>host</strong> как <strong>user</strong></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.3408%; height: 24px;"><strong>ssh -p port user@host
        </strong></td>
        <td style="width: 79.6592%; height: 24px;">подключится к <strong>host</strong> на порт <strong>port</strong> как <strong>user</strong></td>
        </tr>
        <tr>
        <td style="width: 20.3408%;"><strong>ssh-copy-id user@host</strong><strong>
        </strong></td>
        <td style="width: 79.6592%;">добавить ваш ключ на host для user чтобы включить логин без пароля и по ключам</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 100%; height: 384px;" border="1">
        <tbody>
        <tr style="height: 24px;">
        <td style="width: 100%; text-align: center; height: 24px;" colspan="2"><strong><span class="bbc_u">Поиск</span></strong></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>grep pattern files</strong></td>
        <td style="width: 79.2241%; height: 24px;">искать pattern в files</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>grep -r pattern dir</strong><strong>
        </strong></td>
        <td style="width: 79.2241%; height: 24px;">искать рекурсивно pattern в dir</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>command | grep pattern</strong></td>
        <td style="width: 79.2241%; height: 24px;">искать pattern в выводе command</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>locate file</strong><strong>
        </strong></td>
        <td style="width: 79.2241%; height: 24px;">найти все файлы с именем file</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>find / -name file1</strong></td>
        <td style="width: 79.2241%; height: 24px;">найти файлы и директории с именем file1. Поиск начать с корня (/)</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>find / -user user1</strong></td>
        <td style="width: 79.2241%; height: 24px;">найти файл и директорию принадлежащие пользователю user1. Поиск начать с корня (/)</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>find /home/user1 -name "*.bin"</strong></td>
        <td style="width: 79.2241%; height: 24px;">Найти все файлы и директории, имена которых оканчиваются на '. bin'. Поиск начать с '/ home/user1'</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>find /usr/bin -type f -atime +100</strong></td>
        <td style="width: 79.2241%; height: 24px;">найти все файлы в '/usr/bin', время последнего обращения к которым  более 100 дней</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>find /usr/bin -type f -mtime -10</strong></td>
        <td style="width: 79.2241%; height: 24px;">найти все файлы в '/usr/bin', созданные или изменённые в течении последних 10 дней</td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 20.7759%; height: 48px;"><strong>find / -name *.rpm -exec chmod 755 '{}' \;</strong></td>
        <td style="width: 79.2241%; height: 48px;">найти все фалы и директории, имена которых оканчиваются на '.rpm', и изменить права доступа к ним</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>find / -xdev -name "*.rpm"</strong></td>
        <td style="width: 79.2241%; height: 24px;">найти все фалы и директории, имена которых оканчиваются на '.rpm', игнорируя съёмные носители, такие как cdrom, floppy и т.п.</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>locate "*.ps"</strong></td>
        <td style="width: 79.2241%; height: 24px;">найти все файлы, содержащие в имени '.ps'. Предварительно рекомендуется выполнить команду 'updatedb'</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>whereis halt</strong></td>
        <td style="width: 79.2241%; height: 24px;">показывает размещение бинарных файлов, исходных кодов и руководств, относящихся к файлу 'halt'</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 20.7759%; height: 24px;"><strong>which halt</strong></td>
        <td style="width: 79.2241%; height: 24px;">отображает полный путь к файлу 'halt'</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 100%; height: 792px;" border="1">
        <tbody>
        <tr style="height: 24px;">
        <td style="width: 100%; text-align: center; height: 24px;" colspan="2"><strong><span class="bbc_u">Системная информация</span></strong></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>date</strong></td>
        <td style="width: 78.934%; height: 24px;">вывести текущую дату и время</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>cal</strong> <strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">вывести календарь на текущий месяц</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>uptime</strong> <strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">показать текущий аптайм</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>w</strong> <strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">показать пользователей онлайн</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>whoami</strong> <strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">имя, под которым вы залогинены</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>finger user</strong><strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">показать информацию о user</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>uname -a</strong><strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">показать информацию о ядре</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>cat /proc/cpuinfo</strong><strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">информация ЦПУ</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>cat /proc/meminfo</strong><strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">информация о памяти</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>man command</strong><strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">показать мануал для command</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>df</strong> <strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">показать инф. о использовании дисков</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>du</strong> <strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">вывести “вес” текущего каталога</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>free</strong> <strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">использование памяти и swap</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>whereis app</strong><strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">возможное расположение программы app</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>which app</strong><strong>
        </strong></td>
        <td style="width: 78.934%; height: 24px;">какая app будет запущена по умолчанию</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>arch
        </strong></td>
        <td style="width: 78.934%; height: 24px;">отобразить архитектуру компьютера</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>uname -r</strong></td>
        <td style="width: 78.934%; height: 24px;">отобразить используемую версию ядра</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>dmidecode -q</strong></td>
        <td style="width: 78.934%; height: 24px;">показать аппаратные системные компоненты - (SMBIOS / DMI)</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>hdparm -i /dev/hda</strong></td>
        <td style="width: 78.934%; height: 24px;">вывести характеристики жесткого диска</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>hdparm -tT /dev/sda</strong></td>
        <td style="width: 78.934%; height: 24px;">протестировать производительность чтения данных с жесткого диска</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>cat /proc/interrupts</strong></td>
        <td style="width: 78.934%; height: 24px;">показать прерывания</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>cat /proc/meminfo</strong></td>
        <td style="width: 78.934%; height: 24px;">проверить использование памяти</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>cat /proc/swaps
        </strong></td>
        <td style="width: 78.934%; height: 24px;">показать файл(ы) подкачки</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>cat /proc/version</strong></td>
        <td style="width: 78.934%; height: 24px;">вывести версию ядра</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>cat /proc/net/dev</strong></td>
        <td style="width: 78.934%; height: 24px;">показать сетевые интерфейсы и статистику по ним</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>cat /proc/mounts</strong></td>
        <td style="width: 78.934%; height: 24px;">отобразить смонтированные файловые системы</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>lspci -tv</strong></td>
        <td style="width: 78.934%; height: 24px;">показать в виде дерева PCI устройства</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>lsusb -tv</strong></td>
        <td style="width: 78.934%; height: 24px;">показать в виде дерева USB устройства</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>cal 2007</strong></td>
        <td style="width: 78.934%; height: 24px;">вывести таблицу-календарь 2007-го года</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>date 041217002007.00</strong></td>
        <td style="width: 78.934%; height: 24px;">установить системные дату и время ММДДЧЧммГГГГ.СС (МесяцДеньЧасМинутыГод.Секунды)</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>clock -w</strong></td>
        <td style="width: 78.934%; height: 24px;">сохранить системное время в BIOS</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.066%; height: 24px;"><strong>shutdown -h now</strong></td>
        <td style="width: 78.934%; height: 24px;">остановить систему</td>
        </tr>
        <tr>
        <td style="width: 21.066%;"><strong>shutdown -h hours:minutes &amp;</strong></td>
        <td style="width: 78.934%;">запланировать остановку системы на указанное время</td>
        </tr>
        <tr>
        <td style="width: 21.066%;"><strong>shutdown -c</strong></td>
        <td style="width: 78.934%;">отменить запланированную по расписанию остановку системы</td>
        </tr>
        <tr>
        <td style="width: 21.066%;"><strong>shutdown -r now</strong></td>
        <td style="width: 78.934%;">перегрузить систему</td>
        </tr>
        <tr>
        <td style="width: 21.066%;"><strong>reboot</strong></td>
        <td style="width: 78.934%;">перегрузить систему</td>
        </tr>
        <tr>
        <td style="width: 21.066%;"><strong>logout</strong></td>
        <td style="width: 78.934%;">выйти из системы</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.9274%; height: 562px;" border="1">
        <tbody>
        <tr style="height: 24px;">
        <td style="width: 99.9274%; text-align: center; height: 24px;" colspan="2"><strong>Мониторинг и отладка</strong></td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 21.1651%; height: 48px;"><strong>top</strong></td>
        <td style="width: 78.7623%; height: 48px;">отобразить запущенные процессы, используемые ими ресурсы и другую полезную информацию (с автоматическим обновлением данных)</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>ps -eafw</strong></td>
        <td style="width: 78.7623%; height: 24px;">отобразить запущенные процессы, используемые ими ресурсы и другую полезную информацию (единожды)</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>ps -e -o pid,args --forest</strong></td>
        <td style="width: 78.7623%; height: 24px;">вывести PID'ы и процессы в виде дерева</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>pstree</strong></td>
        <td style="width: 78.7623%; height: 24px;">отобразить дерево процессов</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>kill -9 98989</strong></td>
        <td style="width: 78.7623%; height: 24px;">"убить" процесс с PID 98989 "на смерть" (без соблюдения целостности данных)</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>kill -KILL 98989</strong></td>
        <td style="width: 78.7623%; height: 24px;"></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>kill -TERM 98989</strong></td>
        <td style="width: 78.7623%; height: 24px;">Корректно завершить процесс с PID 98989</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>kill -1 98989</strong></td>
        <td style="width: 78.7623%; height: 24px;">заставить процесс с PID 98989 перепрочитать файл конфигурации</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>kill -HUP 98989</strong></td>
        <td style="width: 78.7623%; height: 24px;"></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>lsof -p 98989</strong></td>
        <td style="width: 78.7623%; height: 24px;">отобразить список файлов, открытых процессом с PID 98989</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>lsof /home/user1</strong></td>
        <td style="width: 78.7623%; height: 24px;">отобразить список открытых файлов из директории /home/user1</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>strace -c ls &gt;/dev/null</strong></td>
        <td style="width: 78.7623%; height: 24px;">вывести список системных вызовов, созданных и полученных процессом ls</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>strace -f -e open ls &gt;/dev/null</strong></td>
        <td style="width: 78.7623%; height: 24px;">вывести вызовы бибилотек</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>watch -n1 'cat /proc/interrupts'</strong></td>
        <td style="width: 78.7623%; height: 24px;">отображать прерывания в режиме реального времени</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>last reboot</strong></td>
        <td style="width: 78.7623%; height: 24px;">отобразить историю перезагрузок системы</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>last user1</strong></td>
        <td style="width: 78.7623%; height: 24px;">отобразить историю регистрации пользователя user1 в системе и время его нахождения в ней</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>lsmod</strong></td>
        <td style="width: 78.7623%; height: 24px;">вывести загруженные модули ядра</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>free -m</strong></td>
        <td style="width: 78.7623%; height: 24px;">показать состояние оперативной памяти в мегабайтах</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>smartctl -A /dev/hda</strong></td>
        <td style="width: 78.7623%; height: 24px;">контроль состояния жёсткого диска /dev/hda через SMART</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>smartctl -i /dev/hda</strong></td>
        <td style="width: 78.7623%; height: 24px;">проверить доступность SMART на жёстком диске /dev/hda</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.1651%; height: 24px;"><strong>tail /var/log/dmesg</strong></td>
        <td style="width: 78.7623%; height: 24px;">вывести десять последних записей из журнала загрузки ядра</td>
        </tr>
        <tr style="height: 10px;">
        <td style="width: 21.1651%; height: 10px;"><strong>tail /var/log/messages</strong></td>
        <td style="width: 78.7623%; height: 10px;">вывести десять последних записей из системного журнала</td>
        </tr>
        <tr>
        <td style="width: 21.1651%;"><strong>apropos <em>...keyword</em></strong></td>
        <td style="width: 78.7623%;">выводит список комманд, которые так или иначе относятся к ключевым словам. Полезно, когда вы знаете что делает программа, но не помните команду</td>
        </tr>
        <tr>
        <td style="width: 21.1651%;"><strong>man ping</strong></td>
        <td style="width: 78.7623%;">вызов руководства по работе с программой, в данном случае, - ping</td>
        </tr>
        <tr>
        <td style="width: 21.1651%;"><strong>whatis <em>...keyword</em></strong></td>
        <td style="width: 78.7623%;">отображает описание действий указанной программы</td>
        </tr>
        <tr>
        <td style="width: 21.1651%;"><strong>mkbootdisk --device /dev/fd0 `uname -r`</strong></td>
        <td style="width: 78.7623%;">создаёт загрузочный флоппи-диск</td>
        </tr>
        <tr>
        <td style="width: 21.1651%;"><strong>gpg -c file1</strong></td>
        <td style="width: 78.7623%;">шифрует файл file1 с помощью GNU Privacy Guard</td>
        </tr>
        <tr>
        <td style="width: 21.1651%;"><strong>gpg file1.gpg</strong></td>
        <td style="width: 78.7623%;">дешифрует файл file1 с помощью GNU Privacy Guard</td>
        </tr>
        <tr>
        <td style="width: 21.1651%;"><strong>wget -r </strong><a class="bbc_link" href="http://www.example.com/" target="_blank" rel="nofollow noopener"><strong>www.example.com</strong></a></td>
        <td style="width: 78.7623%;">загружает рекурсивно содержимое сайта <a class="bbc_link" href="http://www.example.com/" target="_blank" rel="nofollow noopener">www.example.com</a></td>
        </tr>
        <tr>
        <td style="width: 21.1651%;"><strong>wget -c </strong><a class="bbc_link" href="http://www.example.com/file.iso" target="_blank" rel="nofollow noopener"><strong>www.example.com/file.iso</strong></a></td>
        <td style="width: 78.7623%;">загрузить файл <a class="bbc_link" href="http://www.example.com/file.iso" target="_blank" rel="nofollow noopener">www.example.com/file.iso</a> с возможностью останова и продолжения в последствии</td>
        </tr>
        <tr>
        <td style="width: 21.1651%;"><strong>echo 'wget -c </strong><a class="bbc_link" href="http://www.example.com/files.iso" target="_blank" rel="nofollow noopener"><strong>www.example.com/files.iso</strong></a><strong>' | at 09:00</strong></td>
        <td style="width: 78.7623%;">начать закачку в указанное время</td>
        </tr>
        <tr>
        <td style="width: 21.1651%;"><strong>ldd /usr/bin/ssh</strong></td>
        <td style="width: 78.7623%;">вывести список библиотек, необходимых для работы ssh</td>
        </tr>
        <tr>
        <td style="width: 21.1651%;"><strong>alias hh='history'</strong></td>
        <td style="width: 78.7623%;">назначить алиас hh команде history</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.9275%; height: 456px;" border="1">
        <tbody>
        <tr style="height: 24px;">
        <td style="width: 99.9275%; text-align: center; height: 24px;" colspan="2"><strong>Пользователи и группы</strong></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.7543%; height: 24px;"><strong>groupadd group_name</strong></td>
        <td style="width: 78.1732%; height: 24px;">создать новую группу с именем group_name</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.7543%; height: 24px;"><strong>groupdel group_name</strong></td>
        <td style="width: 78.1732%; height: 24px;">удалить группу group_name</td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 21.7543%; height: 48px;"><strong>groupmod -n new_group_name old_group_name</strong></td>
        <td style="width: 78.1732%; height: 48px;">переименовать группу old_group_name в new_group_name</td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 21.7543%; height: 48px;"><strong>useradd -c "Nome Cognome" -g admin -d /home/user1 -s /bin/bash user1</strong></td>
        <td style="width: 78.1732%; height: 48px;">создать пользователя user1, назначить ему в качестве домашнего каталога /home/user1, в качестве shell'а /bin/bash, включить его в группу admin и добавить комментарий Nome Cognome</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.7543%; height: 24px;"><strong>useradd user1</strong></td>
        <td style="width: 78.1732%; height: 24px;">создать пользователя user1</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.7543%; height: 24px;"><strong>userdel -r user1</strong></td>
        <td style="width: 78.1732%; height: 24px;">удалить пользователя user1 и его домашний каталог</td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 21.7543%; height: 48px;"><strong>usermod -c "User FTP" -g system -d /ftp/user1 -s /bin/nologin user1</strong></td>
        <td style="width: 78.1732%; height: 48px;">изменить атрибуты пользователя</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.7543%; height: 24px;"><strong>passwd</strong></td>
        <td style="width: 78.1732%; height: 24px;">сменить пароль</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.7543%; height: 24px;"><strong>passwd user1</strong></td>
        <td style="width: 78.1732%; height: 24px;">сменить пароль пользователя user1 (только root)</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.7543%; height: 24px;"><strong>chage -E 2005-12-31 user1</strong></td>
        <td style="width: 78.1732%; height: 24px;">установить дату окончания действия учётной записи пользователя user1</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.7543%; height: 24px;"><strong>pwck</strong></td>
        <td style="width: 78.1732%; height: 24px;">проверить корректность системных файлов учётных записей. Проверяются файлы /etc/passwd и /etc/shadow</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 21.7543%; height: 24px;"><strong>grpck</strong></td>
        <td style="width: 78.1732%; height: 24px;">проверяет корректность системных файлов учётных записей. Проверяется файл/etc/group</td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 21.7543%; height: 48px;"><strong>newgrp [-] group_name</strong></td>
        <td style="width: 78.1732%; height: 48px;">изменяет первичную группу текущего пользователя. Если указать "-", ситуация будет идентичной той, в которой пользователь вышил из системы и снова вошёл. Если не указывать группу, первичная группа будет назначена из /etc/passwd</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 100%;" border="1">
        <tbody>
        <tr>
        <td style="width: 100%; text-align: center;" colspan="2"><strong><span class="bbc_u">Архивация</span></strong></td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar cf file.tar files</strong></td>
        <td style="width: 78.5714%;">создать tar-архив с именем file.tar содержащий file</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar xf file.tar</strong><strong>
        </strong></td>
        <td style="width: 78.5714%;">распаковать file.tar</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar czf file.tar.gz files</strong></td>
        <td style="width: 78.5714%;">создать архив tar с сжатием Gzip</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar xzf file.tar.gz</strong><strong>
        </strong></td>
        <td style="width: 78.5714%;">распаковать tar с Gzip</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar cjf file.tar.bz2</strong><strong>
        </strong></td>
        <td style="width: 78.5714%;">создать архив tar с сжатием Bzip2</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar xjf file.tar.bz2</strong><strong>
        </strong></td>
        <td style="width: 78.5714%;">распаковать tar с Bzip2</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>gzip file</strong><strong>
        </strong></td>
        <td style="width: 78.5714%;">сжать file и переименовать в file.gz</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>gzip -d file.gz</strong><strong>
        </strong></td>
        <td style="width: 78.5714%;">разжать file.gz в file</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>bunzip2 file1.bz2</strong></td>
        <td style="width: 78.5714%;">разжимает файл 'file1.gz'</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>gunzip file1.gz</strong></td>
        <td style="width: 78.5714%;"></td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>gzip file1</strong></td>
        <td style="width: 78.5714%;">сжимает файл 'file1'</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>bzip2 file1</strong></td>
        <td style="width: 78.5714%;"></td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>gzip -9 file1</strong></td>
        <td style="width: 78.5714%;">сжать файл file1 с максимальным сжатием</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>rar a file1.rar test_file</strong></td>
        <td style="width: 78.5714%;">создать rar-архив 'file1.rar' и включить в него файл test_file</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>rar a file1.rar file1 file2 dir1</strong></td>
        <td style="width: 78.5714%;">создать rar-архив 'file1.rar' и включить в него file1, file2 и dir1</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>rar x file1.rar</strong></td>
        <td style="width: 78.5714%;">распаковать rar-архив</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>unrar x file1.rar</strong></td>
        <td style="width: 78.5714%;"></td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar -cvf archive.tar file1</strong></td>
        <td style="width: 78.5714%;">создать tar-архив archive.tar, содержащий файл file1</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar -cvf archive.tar file1 file2 dir1</strong></td>
        <td style="width: 78.5714%;">создать tar-архив archive.tar, содержащий файл file1, file2 и dir1</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar -tf archive.tar</strong></td>
        <td style="width: 78.5714%;">показать содержимое архива</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar -xvf archive.tar</strong></td>
        <td style="width: 78.5714%;">распаковать архив</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar -xvf archive.tar -C /tmp</strong></td>
        <td style="width: 78.5714%;">распаковать архив в /tmp</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar -cvfj archive.tar.bz2 dir1</strong></td>
        <td style="width: 78.5714%;">создать архив и сжать его с помощью bzip2<em>(Прим.переводчика. ключ -j работает не во всех *nix системах)</em></td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar -xvfj archive.tar.bz2</strong></td>
        <td style="width: 78.5714%;">разжать архив и распаковать его<em>(Прим.переводчика. ключ -j работает не во всех *nix системах)</em></td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar -cvfz archive.tar.gz dir1</strong></td>
        <td style="width: 78.5714%;">создать архив и сжать его с помощью gzip</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>tar -xvfz archive.tar.gz</strong></td>
        <td style="width: 78.5714%;">разжать архив и распаковать его</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>zip file1.zip file1</strong></td>
        <td style="width: 78.5714%;">создать сжатый zip-архив</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>zip -r file1.zip file1 file2 dir1</strong></td>
        <td style="width: 78.5714%;">создать сжатый zip-архив и со включением в него нескольких файлов и/или директорий</td>
        </tr>
        <tr>
        <td style="width: 21.4286%;"><strong>unzip file1.zip</strong></td>
        <td style="width: 78.5714%;">разжать и распаковать zip-архив</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.9275%;" border="1">
        <tbody>
        <tr>
        <td style="width: 99.9275%; text-align: center;" colspan="2"><strong>Создание резервных копий (backup)</strong></td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>dump -0aj -f /tmp/home0.bak /home</strong></td>
        <td style="width: 72.4572%;">создать полную резервную копию директории /home в файл /tmp/home0.bak</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>dump -1aj -f /tmp/home0.bak /home</strong></td>
        <td style="width: 72.4572%;">создать инкрементальную резервную копию директории /home в файл /tmp/home0.bak</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>restore -if /tmp/home0.bak</strong></td>
        <td style="width: 72.4572%;">восстановить из резервной копии /tmp/home0.bak</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>rsync -rogpav --delete /home /tmp</strong></td>
        <td style="width: 72.4572%;">синхронизировать /tmp с /home</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>rsync -rogpav -e ssh --delete /home ip_address:/tmp</strong></td>
        <td style="width: 72.4572%;">синхронизировать через SSH-туннель</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>rsync -az -e ssh --delete ip_addr:/home/public /home/local</strong></td>
        <td style="width: 72.4572%;">синхронизировать локальную директорию с удалённой директорией через ssh-туннель со сжатием</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>rsync -az -e ssh --delete /home/local ip_addr:/home/public</strong></td>
        <td style="width: 72.4572%;">синхронизировать удалённую директорию с локальной директорией через ssh-туннель со сжатием</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>dd bs=1M if=/dev/hda | gzip | ssh user@ip_addr 'dd of=hda.gz'</strong></td>
        <td style="width: 72.4572%;">сделать "слепок" локального диска в файл на удалённом компьютере через ssh-туннель</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>tar -Puf backup.tar /home/user</strong></td>
        <td style="width: 72.4572%;">создать инкрементальную резервную копию директории '/home/user' в файл backup.tar с сохранением полномочий</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>( cd /tmp/local/ &amp;&amp; tar c . ) | ssh -C user@ip_addr 'cd /home/share/ &amp;&amp; tar x -p'</strong></td>
        <td style="width: 72.4572%;">копирование содержимого /tmp/local на удалённый компьютер через ssh-туннель в /home/share/</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>( tar c /home ) | ssh -C user@ip_addr 'cd /home/backup-home &amp;&amp; tar x -p'</strong></td>
        <td style="width: 72.4572%;">копирование содержимого /home  на удалённый компьютер через ssh-туннель в /home/backup-home</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>tar cf - . | (cd /tmp/backup ; tar xf - )</strong></td>
        <td style="width: 72.4572%;">копирование одной директории в другую с сохранением полномочий и линков</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>find /home/user1 -name '*.txt' | xargs cp -av --target-directory=/home/backup/ --parents</strong></td>
        <td style="width: 72.4572%;">поиск в /home/user1 всех файлов, имена которых оканчиваются на '.txt', и копирование их в другую директорию</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>find /var/log -name '*.log' | tar cv --files-from=- | bzip2 &gt; log.tar.bz2</strong></td>
        <td style="width: 72.4572%;">поиск в /var/log всех файлов, имена которых оканчиваются на '.log', и создание bzip-архива из них</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>dd if=/dev/hda of=/dev/fd0 bs=512 count=1</strong></td>
        <td style="width: 72.4572%;">создать копию MBR (Master Boot Record) с /dev/hda на флоппи-диск</td>
        </tr>
        <tr>
        <td style="width: 27.4703%;"><strong>dd if=/dev/fd0 of=/dev/hda bs=512 count=1</strong></td>
        <td style="width: 72.4572%;">восстановить MBR с флоппи-диска на /dev/hda</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 100%;" border="1">
        <tbody>
        <tr>
        <td style="width: 100%; text-align: center;" colspan="2"><strong><span class="bbc_u">Сеть</span></strong></td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>ping host</strong></td>
        <td style="width: 77.8463%;">пропинговать <em>host</em> и вывести результат</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>whois domain</strong><strong>
        </strong></td>
        <td style="width: 77.8463%;">получить информацию whois для domain</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>dig domain</strong><strong>
        </strong></td>
        <td style="width: 77.8463%;">получить DNS информацию domain</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>dig -x host</strong><strong>
        </strong></td>
        <td style="width: 77.8463%;">реверсивно искать host</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>wget file</strong><strong>
        </strong></td>
        <td style="width: 77.8463%;">скачать file</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>wget -c file</strong><strong>
        </strong></td>
        <td style="width: 77.8463%;">продолжить остановленную закачку</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>ifconfig</strong><strong>
        </strong></td>
        <td style="width: 77.8463%;">многогранная утилита конфигурирования параметров сетевых интерфейсов</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>ifconfig eth0</strong></td>
        <td style="width: 77.8463%;">показать конфигурацию сетевого интерфейса eth0</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>ifup eth0</strong></td>
        <td style="width: 77.8463%;">активировать (поднять) интерфейс eth0</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>ifdown eth0</strong></td>
        <td style="width: 77.8463%;">деактивировать (опустить) интерфейс eth0</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>ifconfig eth0 192.168.1.1 netmask 255.255.255.0</strong></td>
        <td style="width: 77.8463%;">выставить интерфейсу eth0 ip-адрес и маску подсети</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>ifconfig eth0 promisc</strong></td>
        <td style="width: 77.8463%;">перевести интерфейс eth0 в promiscuous-режим для "отлова" пакетов (sniffing)</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>ifconfig eth0 -promisc</strong></td>
        <td style="width: 77.8463%;">отключить promiscuous-режим на интерфейсе eth0</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>dhclient eth0</strong></td>
        <td style="width: 77.8463%;">активировать интерфейс eth0 в dhcp-режиме.</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>route -n</strong></td>
        <td style="width: 77.8463%;">вывести локальную таблицу маршрутизации</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>netstat -rn</strong></td>
        <td style="width: 77.8463%;"></td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>route add -net 0/0 gw IP_Gateway</strong></td>
        <td style="width: 77.8463%;">задать ip-адрес шлюза по умолчанию (default gateway)</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>route add -net 192.168.0.0 netmask 255.255.0.0 gw 192.168.1.1</strong></td>
        <td style="width: 77.8463%;">добавить статический маршрут в сеть 192.168.0.0/16 через шлюз с ip-адресом 192.168.1.1</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>route del 0/0 gw IP_gateway</strong></td>
        <td style="width: 77.8463%;">удалить ip-адрес шлюза по умолчанию (default gateway)</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>echo "1" &gt; /proc/sys/net/ipv4/ip_forward</strong></td>
        <td style="width: 77.8463%;">разрешить пересылку пакетов (forwarding)</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>hostname</strong></td>
        <td style="width: 77.8463%;">отобразить имя компьютера</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>host </strong><a class="bbc_link" href="http://www.linuxguide.it/" target="_blank" rel="nofollow noopener"><strong>www.linuxguide.it</strong></a></td>
        <td style="width: 77.8463%;">разрешить имя <a class="bbc_link" href="http://www.linuxguide.it/" target="_blank" rel="nofollow noopener">www.linuxguide.it</a> хоста в ip-адрес и наоборот</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>host 62.149.140.85</strong></td>
        <td style="width: 77.8463%;"></td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>ip link show</strong></td>
        <td style="width: 77.8463%;">отобразить состояние всех интерфейсов</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>mii-tool eth0</strong></td>
        <td style="width: 77.8463%;">отобразить статус и тип соединения для интерфейса eth0</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>ethtool eth0</strong></td>
        <td style="width: 77.8463%;">отображает статистику интерфеса eth0 с выводом такой информации, как поддерживаемые и текущие режимы соединения</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>netstat -tupn</strong></td>
        <td style="width: 77.8463%;">отображает все установленные сетевые соединения по протоколам TCP и UDP без разрешения имён в ip-адреса и PID'ы и имена процессов, обеспечивающих эти соединения</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>netstat -tupln</strong></td>
        <td style="width: 77.8463%;">отображает все сетевые соединения по протоколам TCP и UDP без разрешения имён в ip-адреса и PID'ы и имена процессов, слушающих порты</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>tcpdump tcp port 80</strong></td>
        <td style="width: 77.8463%;">отобразить весь трафик на TCP-порт 80 (обычно - HTTP)</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>iwlist scan</strong></td>
        <td style="width: 77.8463%;">просканировать эфир на предмет, доступности беспроводных точек доступа</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>iwconfig eth1</strong></td>
        <td style="width: 77.8463%;">показать конфигурацию беспроводного сетевого интерфейса eth1</td>
        </tr>
        <tr>
        <td style="width: 100%; text-align: center;" colspan="2"><strong>Microsoft Windows networks(SAMBA)</strong></td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>nbtscan ip_addr</strong></td>
        <td style="width: 77.8463%;">разрешить netbios-имя <em>nbtscan не во всех системах ставится по-умолчанию, возможно, придётся доустанавливать вручную. nmblookup включен в пакет samba.</em></td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>nmblookup -A ip_addr</strong></td>
        <td style="width: 77.8463%;"></td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>smbclient -L ip_addr/hostname</strong></td>
        <td style="width: 77.8463%;">отобразить ресурсы, предоставленные в общий доступ на windows-машине</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>smbget -Rr smb://ip_addr/share</strong></td>
        <td style="width: 77.8463%;">подобно wget может получить файлы с windows-машин через smb-протокол</td>
        </tr>
        <tr>
        <td style="width: 22.1537%;"><strong>mount -t smbfs -o username=user,password=pass //winclient/share /mnt/share</strong></td>
        <td style="width: 77.8463%;">смонтировать smb-ресурс, предоставленный на windows-машине, в локальную файловую систему</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 99.9275%; height: 456px;" border="1">
        <tbody>
        <tr style="height: 24px;">
        <td style="width: 99.9275%; text-align: center; height: 24px;" colspan="2"><strong>IPTABLES (firewall)</strong></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 33.0629%; height: 24px;"><strong>iptables -t filter -nL</strong></td>
        <td style="width: 66.8646%; height: 24px;">отобразить все цепочки правил</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 33.0629%; height: 24px;"><strong>iptables -nL</strong></td>
        <td style="width: 66.8646%; height: 24px;"></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 33.0629%; height: 24px;"><strong>iptables -t nat -L</strong></td>
        <td style="width: 66.8646%; height: 24px;">отобразить все цепочки правил в NAT-таблице</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 33.0629%; height: 24px;"><strong>iptables -t filter -F</strong></td>
        <td style="width: 66.8646%; height: 24px;">очистить все цепочки правил в filter-таблице</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 33.0629%; height: 24px;"><strong>iptables -F</strong></td>
        <td style="width: 66.8646%; height: 24px;"></td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 33.0629%; height: 24px;"><strong>iptables -t nat -F</strong></td>
        <td style="width: 66.8646%; height: 24px;">очистить все цепочки правил в NAT-таблице</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 33.0629%; height: 24px;"><strong>iptables -t filter -X</strong></td>
        <td style="width: 66.8646%; height: 24px;">удалить все пользовательские цепочки правил в filter-таблице</td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 33.0629%; height: 48px;"><strong>iptables -t filter -A INPUT -p tcp --dport telnet -j ACCEPT</strong></td>
        <td style="width: 66.8646%; height: 48px;">позволить входящее подключение telnet'ом</td>
        </tr>
        <tr style="height: 24px;">
        <td style="width: 33.0629%; height: 24px;"><strong>iptables -t filter -A OUTPUT -p tcp --dport http -j DROP</strong></td>
        <td style="width: 66.8646%; height: 24px;">блокировать исходящие HTTP-соединения</td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 33.0629%; height: 48px;"><strong>iptables -t filter -A FORWARD -p tcp --dport pop3 -j ACCEPT</strong></td>
        <td style="width: 66.8646%; height: 48px;">позволить "прокидывать" (forward) POP3-соединения</td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 33.0629%; height: 48px;"><strong>iptables -t filter -A INPUT -j LOG --log-prefix "DROP INPUT"</strong></td>
        <td style="width: 66.8646%; height: 48px;">включить журналирование ядром пакетов, проходящих через цепочку INPUT, и добавлением к сообщению префикса "DROP INPUT"</td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 33.0629%; height: 48px;"><strong>iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE</strong></td>
        <td style="width: 66.8646%; height: 48px;">включить NAT (Network Address Translate) исходящих пакетов на интерфейс eth0. Допустимо при использовании с динамически выделяемыми ip-адресами.</td>
        </tr>
        <tr style="height: 48px;">
        <td style="width: 33.0629%; height: 48px;"><strong>iptables -t nat -A PREROUTING -d 192.168.0.1 -p tcp -m tcp --dport 22 -j DNAT --to-destination 10.0.0.2:22</strong></td>
        <td style="width: 66.8646%; height: 48px;">перенаправление пакетов, адресованных одному хосту, на другой хост</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 100%;" border="1">
        <tbody>
        <tr>
        <td style="width: 100%; text-align: center;" colspan="2"><strong><span class="bbc_u">Установка пакетов</span></strong></td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>./configure</strong>
        <strong>make</strong>
        <strong>make install</strong></td>
        <td style="width: 77.2661%;">установка из исходников</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>dpkg -i pkg.deb</strong><strong>
        </strong></td>
        <td style="width: 77.2661%;">установить пакет (Debian)</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>rpm -Uvh pkg.rpm</strong> <strong>
        </strong></td>
        <td style="width: 77.2661%;">установить пакет (RPM)</td>
        </tr>
        <tr>
        <td style="width: 100%; text-align: center;" colspan="2"><strong>DEB пакеты (Debian, Ubuntu и тому подобное)</strong></td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>dpkg -i package.deb</strong></td>
        <td style="width: 77.2661%;">установить / обновить пакет</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>dpkg -r package_name</strong></td>
        <td style="width: 77.2661%;">удалить пакет из системы</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>dpkg -l</strong></td>
        <td style="width: 77.2661%;">показать все пакеты, установленные в систему</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>dpkg -l | grep httpd</strong></td>
        <td style="width: 77.2661%;">среди всех пакетов, установленных в системе, найти пакет содержащий в своём имени "httpd"</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>dpkg -s package_name</strong></td>
        <td style="width: 77.2661%;">отобразить инфрмацию о конкретном пакете</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>dpkg -L package_name</strong></td>
        <td style="width: 77.2661%;">вывести список файлов, входящих в пакет, установленный в систему</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>dpkg --contents package.deb</strong></td>
        <td style="width: 77.2661%;">отобразить список файлов, входящих в пакет, который ешё не установлен в систему</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>dpkg -S /bin/ping</strong></td>
        <td style="width: 77.2661%;">найти пакет, в который входит указанный файл.</td>
        </tr>
        <tr>
        <td style="width: 100%; text-align: center;" colspan="2"><strong>APT - средство управление пакетами (Debian, Ubuntu и тому подобное)</strong></td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>apt-get install package_name</strong></td>
        <td style="width: 77.2661%;">установить / обновить пакет</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>apt-cdrom install package_name</strong></td>
        <td style="width: 77.2661%;">установить / обновить пакет с cdrom'а</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>apt-get update</strong></td>
        <td style="width: 77.2661%;">получить обновлённые списки пакетов</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>apt-get upgrade</strong></td>
        <td style="width: 77.2661%;">обновить пакеты, установленные в систему</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>apt-get remove package_name</strong></td>
        <td style="width: 77.2661%;">удалить пакет, установленный в систему с сохранением файлов конфигурации</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>apt-get purge package_name</strong></td>
        <td style="width: 77.2661%;">удалить пакет, установленный в систему с удалением файлов конфигурации</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>apt-get check</strong></td>
        <td style="width: 77.2661%;">проверить целостность зависимостей</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>apt-get clean</strong></td>
        <td style="width: 77.2661%;">удалить загруженные архивные файлы пакетов</td>
        </tr>
        <tr>
        <td style="width: 22.7339%;"><strong>apt-get autoclean</strong></td>
        <td style="width: 77.2661%;">удалить старые загруженные архивные файлы пакетов</td>
        </tr>
        </tbody>
        </table>
        &nbsp;
        <table style="border-collapse: collapse; width: 100%;" border="1">
        <tbody>
        <tr>
        <td style="width: 100%; text-align: center;" colspan="2"><strong><span class="bbc_u">Клавиатурные сочетания</span></strong></td>
        </tr>
        <tr>
        <td style="width: 23.5315%;"><strong>Ctrl+C</strong></td>
        <td style="width: 76.4685%;">завершить текущую команду</td>
        </tr>
        <tr>
        <td style="width: 23.5315%;"><strong>Ctrl+Z</strong><strong>
        </strong></td>
        <td style="width: 76.4685%;">остановить текущую команду, продолжить с fg на переднем плане или bg в фоне</td>
        </tr>
        <tr>
        <td style="width: 23.5315%;"><strong>Ctrl+D</strong><strong>
        </strong></td>
        <td style="width: 76.4685%;">разлогиниться, тоже самое, что и exit</td>
        </tr>
        <tr>
        <td style="width: 23.5315%;"><strong>Ctrl+W</strong><strong>
        </strong></td>
        <td style="width: 76.4685%;">удалить одно слово в текущей строке</td>
        </tr>
        <tr>
        <td style="width: 23.5315%;"><strong>Ctrl+U</strong><strong>
        </strong></td>
        <td style="width: 76.4685%;">удалить строку</td>
        </tr>
        <tr>
        <td style="width: 23.5315%;"><strong>!!</strong><strong>
        </strong></td>
        <td style="width: 76.4685%;">повторить последнюю команду</td>
        </tr>
        <tr>
        <td style="width: 23.5315%;"><strong>exit</strong> <strong>
        </strong></td>
        <td style="width: 76.4685%;">разлогиниться</td>
        </tr>
        </tbody>
        </table>
&nbsp;
<table style="border-collapse: collapse; width: 100%; height: 3216px;" border="1">
<tbody>
<tr style="height: 24px;">
<td style="width: 100%; text-align: center; height: 24px;" colspan="2"><strong>Шаблоны типовых запросов SQL</strong></td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">mysqldump -u USER -pPASSWORD DATABASE &gt; /path/to/file/dump.sql</td>
<td style="width: 50%; height: 24px;">Делаем бекап</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">mysqldump --no-data - u USER -pPASSWORD DATABASE &gt; /path/to/file/schema.sql</td>
<td style="width: 50%; height: 24px;">Создаём структуру базы без данных</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">mysqldump -u USER -pPASSWORD DATABASE TABLE1 TABLE2 TABLE3 &gt; /path/to/file/dump_table.sql</td>
<td style="width: 50%; height: 48px;">Если нужно сделать дамп только одной или нескольких таблиц</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">mysqldump -u USER -pPASSWORD DATABASE | gzip &gt; /path/to/outputfile.sql.gz</td>
<td style="width: 50%; height: 24px;">Создаём бекап и сразу его архивируем</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">mysqldump -u USER -pPASSWORD DATABASE | gzip &gt; `date +/path/to/outputfile.sql.%Y%m%d.%H%M%S.gz</td>
<td style="width: 50%; height: 48px;">Создание бекапа с указанием его даты</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">mysql -u USER -pPASSWORD DATABASE &lt; /path/to/dump.sql</td>
<td style="width: 50%; height: 24px;">Заливаем бекап в базу данных</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">gunzip &lt; /path/to/outputfile.sql.gz | mysql -u USER -pPASSWORD DATABASE</td>
<td style="width: 50%; height: 24px;">Заливаем архив бекапа в базу</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">zcat /path/to/outputfile.sql.gz | mysql -u USER -pPASSWORD DATABASE</td>
<td style="width: 50%; height: 24px;">или так</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">mysqladmin -u USER -pPASSWORD create NEWDATABASE</td>
<td style="width: 50%; height: 24px;">Создаём новую базу данных</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">mysqlshow -u USER -pPASSWORD</td>
<td style="width: 50%; height: 24px;">Для просмотра списка баз данных</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">mysqlshow -u USER -pPASSWORD DATABASE</td>
<td style="width: 50%; height: 24px;">А так же можно посмотреть список таблиц базы</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">ssh -fNL LOCAL_PORT:localhost:3306 REMOTE_USER@REMOTE_HOST</td>
<td style="width: 50%; height: 24px;">Проброс портов</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">select поле1, поле2 from таблица1</td>
<td style="width: 50%; height: 48px;">Выборка записей из таблицы. Вместо списка полей может быть * — тогда выведудтся все поля</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">select поле1, поле2 from таблица1 order by поле1 asc</td>
<td style="width: 50%; height: 24px;">Выборка записей из таблицы с сортировкой по возрастанию</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">select поле1, поле2 from таблица1 order by поле1 desc</td>
<td style="width: 50%; height: 24px;">Выборка записей из таблицы с сортировкой по убыванию</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">select поле1, поле2 from таблица1 where поле1 = 777</td>
<td style="width: 50%; height: 48px;">Выборка записей из таблицы с условием на численное поле. Вместо = может быть &gt;, &lt;, &gt;=, &lt;=</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">select поле1, поле2 from таблица1 where поле1 = "777"</td>
<td style="width: 50%; height: 24px;">Выборка записей из таблицы с условием на строковое поле</td>
</tr>
<tr style="height: 72px;">
<td style="width: 50%; height: 72px;">select поле1, sum(поле2) from таблица1
group by поле1</td>
<td style="width: 50%; height: 72px;">Выборка с группировкой. Вместо sum может быть min, max, count и другие функции
все поля, к которым не применяются функции, должны быть перечислены в секции group by</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">select таб1.поле1, таб2.поле2 from таблица1 as таб1
join таблица2 as таб2 on таб2.поле3 = таб1.поле4</td>
<td style="width: 50%; height: 48px;">Выборка из двух таблиц. Вместо таблица2 может быть таблица1, если в таблице есть поле, ссылающееся на эту же таблицу</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">insert into таблица1 ([поле1], [поле2]) values (значениие1, значение2)</td>
<td style="width: 50%; height: 24px;">Вставка новой записи</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">update таблица1 set поле1 = значение1 where поле2 = значение2</td>
<td style="width: 50%; height: 24px;">Изменение записи</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">delete from таблица1 where поле1 = значение1</td>
<td style="width: 50%; height: 24px;">Удаление записи</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">create database имя_базы_данных;</td>
<td style="width: 50%; height: 24px;"></td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">use имя_базы_данных;</td>
<td style="width: 50%; height: 24px;"></td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">create table имя_таблицы (имя_первого_столбца тип, имя_второго_столбца тип, …, имя_последнего_столбца тип );</td>
<td style="width: 50%; height: 48px;"></td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">show databases;</td>
<td style="width: 50%; height: 24px;">Показать все имеющиеся БД</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">show tables;</td>
<td style="width: 50%; height: 48px;">показать список таблиц текущей БД (предварительно ее надо выбрать с помощью оператора use).</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">describe имя_таблицы;</td>
<td style="width: 50%; height: 24px;">показать описание столбцов указанной таблицы</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">drop database имя_базы данных;</td>
<td style="width: 50%; height: 24px;">удалить БД</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">drop table имя_таблицы;</td>
<td style="width: 50%; height: 24px;">удалить таблицу</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">AUTO_INCREMENT</td>
<td style="width: 50%; height: 48px;">высчитывает максимальное значение этого столбца, полученное значение увеличивает на 1 и заносит его в столбец</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">PRIMARY KEY ()</td>
<td style="width: 50%; height: 24px;"></td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">FOREIGN KEY (имя_столбца_которое_является_внешним_ключом) REFERENCES имя_таблицы_родителя (имя_столбца_родителя);</td>
<td style="width: 50%; height: 48px;"></td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">INSERT INTO имя_таблицы VALUES (‘значение_первого_столбца’, ‘значение_второго_столбца’, …, ‘значение_последнего_столбца’);</td>
<td style="width: 50%; height: 48px;"></td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">INSERT INTO имя_таблицы (‘имя_столбца’, ‘имя_столбца’) VALUES (‘значение_первого_столбца’,’значение_второго_столбца’);</td>
<td style="width: 50%; height: 48px;"></td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">SELECT что_выбрать FROM откуда_выбрать;</td>
<td style="width: 50%; height: 24px;"></td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">SELECT * FROM откуда_выбрать;</td>
<td style="width: 50%; height: 24px;">выбрать все столбцы таблицы</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">SELECT имя_столбца FROM имя_таблицы ORDER BY имя_столбца_сортировки;</td>
<td style="width: 50%; height: 24px;">сортировка</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">SELECT имя_столбца FROM имя_таблицы WHERE условие;</td>
<td style="width: 50%; height: 24px;"></td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">BETWEEN меньшее_число AND большее_число</td>
<td style="width: 50%; height: 24px;">отбираются значения, находящиеся между указанными</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">IS NOT NULL (IS NULL)</td>
<td style="width: 50%; height: 24px;">отбираются строки, (не) имеющие значения в указанном поле</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">IN (NOT IN)</td>
<td style="width: 50%; height: 24px;">отбираются значения, (кроме) соответствующие указанным</td>
</tr>
<tr style="height: 96px;">
<td style="width: 50%; height: 96px;">LIKE (NOT LIKE)</td>
<td style="width: 50%; height: 96px;">отбираются значения, (не) соответствующие образцу. Самый распространенный метасимвол — %. Он означает любые символы. Например, если нам надо найти слова, начинающиеся с букв «вел», то мы напишем LIKE ‘вел%’, а если мы хотим найти слова, которые содержат символы «клуб», то мы напишем LIKE ‘%клуб%’</td>
</tr>
<tr style="height: 72px;">
<td style="width: 50%; height: 72px;">SELECT имя_столбца FROM имя_таблицы WHERE часть условия IN (SELECT имя_столбца FROM имя_таблицы WHERE часть условия IN (SELECT имя_столбца FROM имя_таблицы WHERE условие) ) ;</td>
<td style="width: 50%; height: 72px;">подзапросы</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">SELECT имена_столбцов_таблицы_1, имена_столбцов_таблицы_2 FROM имя_таблицы_1, имя_таблицы_2;</td>
<td style="width: 50%; height: 48px;">объединение</td>
</tr>
<tr style="height: 120px;">
<td style="width: 50%; height: 120px;">SELECT имя_таблицы_1.имя_столбца1_таблицы_1, имя_таблицы_1.имя_столбца2_таблицы_1, имя_таблицы_2.имя_столбца1_таблицы_2, имя_таблицы_2.имя_столбца2_таблицы_2 FROM имя_таблицы_1, имя_таблицы_2 WHERE имя_таблицы_1.имя_столбца_по_которому_объединяем = имя_таблицы_2.имя_столбца_по_которому_объединяем;</td>
<td style="width: 50%; height: 120px;"></td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">SELECT имя_таблицы_1.имя_столбца, имя_таблицы_2.имя_столбца FROM имя_таблицы_1 ТИП ОБЪЕДИНЕНИЯ имя_таблицы_2 ON условие_объединения;</td>
<td style="width: 50%; height: 48px;">где ТИП ОБЪЕДИНЕНИЯ — либо LEFT OUTER JOIN, либо RIGHT OUTER JOIN. Чтобы взять все строки с таблицы, а не только полные</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">COUNT()</td>
<td style="width: 50%; height: 24px;">подсчет количества строк в таблице</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">SELECT COUNT(имя_столбца) FROM имя_таблицы;</td>
<td style="width: 50%; height: 24px;"></td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">SELECT имя_столбца COUNT(имя_столбца) FROM имя_таблицы GROUP BY имя_столбца;</td>
<td style="width: 50%; height: 48px;"></td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">SELECT имя_столбца COUNT(имя_столбца) FROM имя_таблицы GROUP BY имя_столбца HAVING COUNT условие;</td>
<td style="width: 50%; height: 48px;">HAVING исполняет функции</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">ALTER TABLE имя_таблицы ADD COLUMN имя_столбца тип;</td>
<td style="width: 50%; height: 24px;">добавление столбца</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">UPDATE имя_таблицы SET имя_столбца=значение_столбца WHERE условие</td>
<td style="width: 50%; height: 24px;">для обновления уже существующих данных</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">ALTER TABLE имя_таблицы CHANGE старое_имя_столбца новое_имя_столбца тип;</td>
<td style="width: 50%; height: 24px;">изменение названия столбца</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">ALTER TABLE имя_таблицы MODIFY имя_столбца новый_тип;</td>
<td style="width: 50%; height: 24px;">изменение типа данных столбца</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">DELETE FROM имя_таблицы WHERE условие;</td>
<td style="width: 50%; height: 24px;">удаление строк из столбца</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">AVG()</td>
<td style="width: 50%; height: 24px;">Функция возвращает среднее значение столбца</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">COUNT()</td>
<td style="width: 50%; height: 24px;">Функция возвращает число строк в столбце</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">MAX()</td>
<td style="width: 50%; height: 24px;">Функция возвращает самое большое значение в столбце</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">MIN()</td>
<td style="width: 50%; height: 24px;">Функция возвращает самое маленькое значение в столбце</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">SUM()</td>
<td style="width: 50%; height: 24px;">Функция возвращает сумму значений столбца</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">SELECT имя_таблицы_1.имя_столбца* имя_таблицы_2.имя_столбца AS имя _вычисляемого_столбца FROM имя_таблицы_1, имя_таблицы_2</td>
<td style="width: 50%; height: 48px;">создание дополнительного столбца для вывода данных. Ее нельзя использовать, так как она не находиться в какой-либо таблице. Для таких случаев существуют Представления</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">CREATE VIEW имя_представления AS запрос;</td>
<td style="width: 50%; height: 24px;">создание представления</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">CONCAT(str1,str2…)</td>
<td style="width: 50%; height: 48px;">Возвращает строку, созданную путем объединения аргументов (аргументы указываются в скобках — str1,str2…). Добавляем пробел » «, как аргумент, для читабельности.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">SELECT CONCAT_WS(‘ ‘, имя_столбца1, имя_столбца2) FROM имя_таблицы;</td>
<td style="width: 50%; height: 24px;">если аргументов много, используем этот синтаксис для рациональности. Первым аргументом ставим разделитель</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">INSERT(str, pos, len, new_str)</td>
<td style="width: 50%; height: 48px;">Возвращает строку str, в которой подстрока, начинающаяся с позиции pos и имеющая длину len символов, заменена подстрокой new_str.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">LPAD(str, len, dop_str)</td>
<td style="width: 50%; height: 24px;">Возвращает строку str, дополненную слева строкой dop_str до длины len.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">RPAD(str, len, dop_str)</td>
<td style="width: 50%; height: 24px;">Возвращает строку str, дополненную справа строкой dop_str до длины len.</td>
</tr>
<tr style="height: 72px;">
<td style="width: 50%; height: 72px;">LTRIM(str)</td>
<td style="width: 50%; height: 72px;">Возвращает строку str, в которой удалены все начальные пробелы. Эта строковая функция удобна для корректного отображения информации в случаях, когда при вводе данных допускаются случайные пробелы.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">RTRIM(str)</td>
<td style="width: 50%; height: 24px;">Возвращает строку str, в которой удалены все конечные пробелы.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">TRIM(str)</td>
<td style="width: 50%; height: 24px;">Возвращает строку str, в которой удалены все начальные и конечные пробелы.</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">LOWER(str)</td>
<td style="width: 50%; height: 48px;">Возвращает строку str, в которой все символы переведены в нижний регистр. С русскими буквами работает некорректно, поэтому лучше не применять.</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">UPPER(str)</td>
<td style="width: 50%; height: 48px;">Возвращает строку str, в которой все символы переведены в верхний регистр. С русскими буквами так же лучше не применять.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">LENGTH(str)</td>
<td style="width: 50%; height: 24px;">Возвращает длину строки str.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">LEFT(str, len)</td>
<td style="width: 50%; height: 24px;">Возвращает len левых символов строки str.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">RIGHT(str, len)</td>
<td style="width: 50%; height: 24px;">Возвращает len правых символов строки str.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">REPEAT(str, n)</td>
<td style="width: 50%; height: 24px;">Возвращает строку str n-количество раз.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">REPLACE(str, pod_str1, pod_str2)</td>
<td style="width: 50%; height: 24px;">Возвращает строку str, в которой все подстроки pod_str1 заменены подстроками pod_str2.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">REVERSE(str)</td>
<td style="width: 50%; height: 24px;">Возвращает строку str, записанную в обратном порядке.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">LOAD_FILE(file_name)</td>
<td style="width: 50%; height: 24px;">Эта функция читает файл file_name и возвращает его содержимое в виде строки.</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">CURDATE(), CURTIME() и NOW()</td>
<td style="width: 50%; height: 48px;">Первая функция возвращает текущую дату, вторая — текущее время, а третья — текущую дату и время.</td>
</tr>
<tr style="height: 96px;">
<td style="width: 50%; height: 96px;">ADDDATE(date, INTERVAL value)</td>
<td style="width: 50%; height: 96px;">Функция возвращает дату date, к которой прибавлено значение value. Значение value может быть отрицательным, тогда итоговая дата уменьшится. В качестве значения value могут выступать не только дни, но и недели (WEEK), месяцы (MONTH), кварталы (QUARTER) и годы (YEAR).</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">SUBDATE(date, INTERVAL value)</td>
<td style="width: 50%; height: 24px;">функция идентична предыдущей, но производит операцию вычитания, а не сложения.</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">PERIOD_ADD(period, n)</td>
<td style="width: 50%; height: 48px;">функция добавляет n месяцев к значению даты period. Нюанс: значение даты должно быть представлено в формате YYYYMM.</td>
</tr>
<tr style="height: 96px;">
<td style="width: 50%; height: 96px;">TIMESTAMPADD(interval, n, date)</td>
<td style="width: 50%; height: 96px;">функция добавляет к дате date временной интервал n, значения которого задаются параметром interval. Возможные значения параметра interval: FRAC_SECOND — микросекунды SECOND — секунды MINUTE — минуты HOUR — часы DAY — дни WEEK — недели MONTH — месяцы QUARTER — кварталы YEAR – годы.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">TIMEDIFF(date1, date2)</td>
<td style="width: 50%; height: 24px;">вычисляет разницу в часах, минутах и секундах между двумя датами.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">DATEDIFF(date1, date2)</td>
<td style="width: 50%; height: 24px;">вычисляет разницу в днях между двумя датами.</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">PERIOD_DIFF(period1, period2)</td>
<td style="width: 50%; height: 48px;">функция вычисляет разницу в месяцах между двумя датами, представленными в формате YYYYMM.</td>
</tr>
<tr style="height: 48px;">
<td style="width: 50%; height: 48px;">TIMESTAMPDIFF(interval, date1, date2)</td>
<td style="width: 50%; height: 48px;">функция вычисляет разницу между датами date2 и date1 в единицах, указанных в параметре interval.</td>
</tr>
<tr style="height: 24px;">
<td style="width: 50%; height: 24px;">SUBTIME(date, time)</td>
<td style="width: 50%; height: 24px;">функция вычитает из времени date время time.</td>
</tr>
<tr>
<td style="width: 50%;">DATE(datetime)</td>
<td style="width: 50%;">возвращает дату, отсекая время.</td>
</tr>
<tr>
<td style="width: 50%;">TIME(datetime)</td>
<td style="width: 50%;">возвращает время, отсекая дату.</td>
</tr>
<tr>
<td style="width: 50%;">TIMESTAMP(date)</td>
<td style="width: 50%;">функция принимает дату date и возвращает полный вариант со временем.</td>
</tr>
<tr>
<td style="width: 50%;">DAY(date) и DAYOFMONTH(date)</td>
<td style="width: 50%;">функции-синонимы, возвращают из даты порядковый номер дня месяца.</td>
</tr>
<tr>
<td style="width: 50%;">DAYNAME(date), DAYOFWEEK(date) и WEEKDAY(date)</td>
<td style="width: 50%;">функции возвращают день недели, первая — его название, вторая — номер дня недели (отсчет от 1 — воскресенье до 7 — суббота), третья — номер дня недели (отсчет от 0 — понедельник, до 6 – воскресенье.</td>
</tr>
<tr>
<td style="width: 50%;">WEEK(date), WEEKOFYEAR(datetime)</td>
<td style="width: 50%;">обе функции возвращают номер недели в году, первая для типа date, а вторая — для типа datetime, у первой неделя начинается с воскресенья, у второй — с понедельника.</td>
</tr>
<tr>
<td style="width: 50%;">MONTH(date) и MONTHNAME(date)</td>
<td style="width: 50%;">обе функции возвращают значения месяца. Первая — его числовое значение (от 1 до 12), вторая — название месяца.</td>
</tr>
<tr>
<td style="width: 50%;">QUARTER(date)</td>
<td style="width: 50%;">функция возвращает значение квартала года (от 1 до 4).</td>
</tr>
<tr>
<td style="width: 50%;">YEAR(date)</td>
<td style="width: 50%;">функция возвращает значение года (от 1000 до 9999).</td>
</tr>
<tr>
<td style="width: 50%;">DAYOFYEAR(date)</td>
<td style="width: 50%;">возвращает порядковый номер дня в году (от 1 до 366).</td>
</tr>
<tr>
<td style="width: 50%;">HOUR(datetime)</td>
<td style="width: 50%;">возвращает значение часа для времени (от 0 до 23).</td>
</tr>
<tr>
<td style="width: 50%;">MINUTE(datetime)</td>
<td style="width: 50%;">возвращает значение минут для времени (от 0 до 59).</td>
</tr>
<tr>
<td style="width: 50%;">SECOND(datetime)</td>
<td style="width: 50%;">возвращает значение секунд для времени (от 0 до 59).</td>
</tr>
<tr>
<td style="width: 50%;">EXTRACT(type FROM date)</td>
<td style="width: 50%;">возвращает часть date определяемую параметром type:

SELECT EXTRACT(YEAR FROM ‘2011-04-17 23:15:18’) AS year,

EXTRACT(MONTH FROM ‘2011-04-17 23:15:18’) AS mon,

EXTRACT(DAY FROM ‘2011-04-17 23:15:18’) AS day,

EXTRACT(HOUR FROM ‘2011-04-17 23:15:18’) AS hour,

EXTRACT(MINUTE FROM ‘2011-04-17 23:15:18’) AS min,

EXTRACT(SECOND FROM ‘2011-04-17 23:15:18’) AS sec;</td>
</tr>
<tr>
<td style="width: 50%;">TO_DAYS(date) и FROM_DAYS(n)</td>
<td style="width: 50%;">взаимообратные функции. Первая преобразует дату в количество дней, прошедших с нулевого года. Вторая, наоборот, принимает число дней, прошедших с нулевого года и преобразует их в дату.</td>
</tr>
<tr>
<td style="width: 50%;">UNIX_TIMESTAMP(date) и FROM_UNIXTIME(n)</td>
<td style="width: 50%;">взаимообратные функции. Первая преобразует дату в количество секунд, прошедших с 1 января 1970 года. Вторая, наоборот, принимает число секунд, с 1 января 1970 года и преобразует их в дату.</td>
</tr>
<tr>
<td style="width: 50%;">TIME_TO_SEC(time) и SEC_TO_TIME(n)</td>
<td style="width: 50%;">взаимообратные функции. Первая преобразует время в количество секунд, прошедших от начала суток. Вторая, наоборот, принимает число секунд с начала суток и преобразует их во время.</td>
</tr>
<tr>
<td style="width: 50%;">MAKEDATE(year, n)</td>
<td style="width: 50%;">функция принимает год и номер дня в году и преобразует их в дату.</td>
</tr>
</tbody>
</table>

</body>
</html>
