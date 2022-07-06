# Insertion Sort
## Patika.dev egitim kampi süresince yapilmis proje odevdir.



[22,27,16,2,18,6] -> Insertion Sort


### 1. Elemanlarin siralanmasi

* [2,27,16,22,18,6] -> 2 en kucuk eleman oldugu icin 22 ile yer degistririr.
* [2,6,16,22,18,27] -> 6 en kucuk 2. eleman oldugu icin 27 ile yer degistririr.
* [2,6,16,22,18,27] -> 16 sayısı sıralamaya uygun konumda oldugu icin bir yer degisikligi olmaz.
* [2,6,16,18,22,27] -> 18 en kucuk 4. eleman oldugu icin 22 ile yer degistirir ve diger elemanlar kurala uygun duruma geldigi icin siralama tamamlanmis olur.

### 2. Big-o gosterimi

Big-o notation : O(n^2); n=6 O(6^2)= O(36)

### Time Complexity

* Avarage Case: 16,18
* Worst Case: 27
* Best Case: 2

[7,3,5,8,2,9,4,15,16] -> Instertion Sort

## Dizisinin ilk 4 adiminin kurallar cercevesinde siralanmasi

* [2,3,5,8,7,9,4,15,16] -> 2, en kucuk eleman oldugu icin 7 ile yer degistirir.
* [2,3,5,8,7,9,4,15,16] -> 3, en kucuk 2. eleman oldugu icin yer degistirme yapilmaz.
* [2,3,4,8,7,9,5,15,16] -> 4, en kucuk 3. eleman oldugu icin 5 ile yer degistirilir.
* [2,3,4,5,7,9,8,15,16] -> 5, en kucuk 4. eleman oldugu icin 8 ile yer degistirilir.
