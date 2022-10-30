# Project-1-Insertion-Sort
https://www.patika.dev/tr

1) Dizide sol baştan başlayarak tüm elemanlar sırasıyla karşılaştırılır. Küçük olan sol tarafa gelecek şekilde yer değiştirmeler yapılır. Karşılaştırmada kendinden daha küçük sayı bulunmayan dizi elemanı aynı yerde kalır.

(22,27,16,2,18,6) - n
(2,27,16,22,18,6) – n-1
(2,6,16,22,18,27) – n-2
(2,6,16,18,22,27) – n-3

2) Big-O gösterimi: Burada dizi işlem sayısı O(n^2) olmalıdır.
3)   Average case – Dizinin tam ortasında olan 18 sayısı için yapılacak işlem sayısını gösterecektir.
     Worst case - Dizinin sonundaki 27 sayısı için yapılacak işlem sayısını gösterecektir.
     Best case  -  Dizinin başındaki 2 sayısı için yapılacak işlem sayısını gösterecektir.
     Average case – 18 3. işlemin sonunda ortaya gelebildiği için dizi işlem sayısı O(3^2) olmalıdır.
     Worst case – 27 sayısı 2. İşlem sonunda son kısma gelmektedir. Bu nedenle işlem sayısı O(2^2) olacaktır.
     Best case  - 2 sayısı 1. İşlem sonunda başa gelmektedir. Bu nedenle işlem sayısı O(1^2) olacaktır.
4) Dizi sıralandıktan sonra 18 sayısı, dizinin ortasına denk geldiği için average case kapsamına girecektir.
