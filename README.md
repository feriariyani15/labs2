- pertama kita buat folder Lab2
- kemudian klik kanan tambah new text document dengan format .py
- kemudian di pyton shell, ketik coding:

def tes():
    a=int(input("bilangan1 ="))
    b=int(input("bilangan2 ="))
    c=int(input("bilangan3 ="))

    if a>b and a>c:
        print(a, 'terbesar')
    elif b>a and b>c:
        print(b, 'terbesar')
    else:
        print(c, 'terbesar')

tes()
- kemudian klik file => save.
- kemudian kita panggil python di cmd
- ketik d:==> cd Lab2 ==> Lab2.py
- kemudian kita input tiga angka bilangan bulat
	misal : bilangan1 = 38
		bilangan2 = 46
		bilangan3 = 26
- maka akan muncul bilangan terbesar = 46
