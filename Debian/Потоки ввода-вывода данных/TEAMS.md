# Команды потока ввода-вывода данных

Команды для работы с файлами, записи, переадресация.


## CAT

`cat` **- (от concatenate) — это стандартная утилита в Linux/macOS/Unix для работы с текстовыми файлами.**
- `cat > <file>` - создание файла. Нам предлагает его заполнить данными. `CTRL+D` - выход.
<br>
<div align="center">
  <img src="./img/cat/1.JPG" alt="cat > <file>">
</div>


- `cat <file1> > <file2>` - создание файла file2 и копирование с file1 в file2.
<br>
<div align="center">
 <img src="./img/cat/2.JPG" alt="cat <file1> > <file2>">
</div>


- `cat >> <file>` - добавление в файл новых данных.
<br>
<div align="center">
 <img src="./img/cat/3.JPG" alt="cat >> <file>">
</div>


## GREP
`grep` **- (от global regular expression print) — утилита для поиска текста по шаблону (регулярному выражению) в файлах или потоке ввода.**

- `grep <reg> < <file>` - находит вхождение в файле и выводит ее.
<br>
<div align="center">
 <img src="./img/grep/1.JPG" alt="grep <reg> < <file>">
</div>