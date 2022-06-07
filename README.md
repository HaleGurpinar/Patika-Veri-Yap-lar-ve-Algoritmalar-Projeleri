# Patika//Veri-Yapilari-ve-Algoritmalar-Projeleri
> [Hale .](https://app.patika.dev/halegrpnr)
## Insertion Sort Projesi
[22,27,16,2,18,6] -> Insertion Sort
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  1. [22,27,16,2,18,6]
  2. [16,22,27,2,18,6]
  3. [2,16,22,27,18,6]
  4. [2,16,18,22,27,6]
  5. [2,6,16,18,22,27]

2.Big-O gösterimini yazınız.

Big-O Notation: O(n^2)

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

    -Best Case: Dizinin zaten sıralı olması: O(n)
    
    -Worst Case: Dizinin ters sıralı olamsı: n.(n-1)/2= O(n^2)
    
    -Average Case : O(n^2)
    
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

18 dizinin oratsında yer aldığı için average case kapsamına girebilir.

  [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.[3,7,5,8,2,9,4,15,6]

2.[3,5,7,8,2,9,4,15,6]

3.[2,3,5,7,8,9,4,15,6]

4.[2,3,4,5,7,8,9,15,6]

## Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
  
|16, 21, 11, 8, 12, 22|

  |16, 21, 11|   --             |8, 12, 22|

|16|  --   |21, 11|    --     |8|   --    |12, 22|

|16|  --   |21| --   |11| --  |8| --   |12|  --  |22|

|16|  --   |11, 21|   --      |8|   --    |12, 22|

  |11, 16, 21|          --      |8, 12, 22|

|8, 11, 12, 16, 21, 22|

* Big-O gösterimini yazınız.

Dizinin her elemanı tek kalana kadar 2'ye bölünerek dizi altdizilere ayrılır. 2^x = n => logn

n eleman birbirlerine göre karşılaştırması yapılarak birleştirilir. n

Big-O Notation: (nlogn)



