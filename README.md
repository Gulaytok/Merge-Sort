# [16,21,11,8,12,22] Merge Sort aşamalarını yazalım
1) İlk önce elimizdeki diziyi ratstgele 2'ye bölelim
#merge sort'ta amaç dizileri parçalara bölerek ayırmaktır# biz de öyle yapacağız
2) Tekrar 2'ye bölelim dizi elemanları 2 veya dahah az kalana kadar bölme yapılır
3) Sıralama bitince en uygun biçimde 2'şerli şekilde birleştirilir
       [16,21,11,8,12,22]
         /             \
     [16,21,11]     [8,12,22]
      /      \       /      \
  [16,21]   [11]   [8,12]   [22]
      \      /       \      /
     [11,16,21]     [8,12,22]
          \             /
        [8,11,12,16,21,22]
#Big O gösterimini yapalım

Best Case = O(n*logn)
Avarage Case = O(n*logn)
Worst Case = O(n*logn)

https://app.patika.dev/gulayy
