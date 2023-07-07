# Nim
该存储库包含 NIM 编程


下面的源代码解释了如何输入数字，其结果在打印时将是一个大于 1 的数字（与实际数字相比）。例如，您输入数字 1，那么结果就是数字 2。

```nim

import strutils

import typetraits



stdout.write "Silahkan masukan angka yang di inginkan : "

var angka = stdin.readline.parseBiggestUInt

inc angka

echo "Angka yang anda masukan setelah di tambah 1 : ", angka


```




