Diyelim ki for döngüsü yapcaksın ama 2 tane listeye yapman lazım ama bunu tek for döngüsü içinde halletmek istiyorsun işte burada zip() fonksiyonu devreye giriyor. kolayca 2 adet listeyi birleytirip for döngüsü içindeki 2 listeye atabilirsiniz.

<h3>Örnek Kullanım</h3>

```
liste1 = ["Bir","İki", "Üç", "Dört", "Beş"]
liste2 = ["1", "2", "3", "4", "5"]

for l1, l2 in zip(liste1, liste2):
    print(f"{l1} - {l2}")
```
