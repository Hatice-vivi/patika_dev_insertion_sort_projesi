# patika_dev_insertion_sort_projesi

# [22,27,16,2,18,6] dizisi için; 
# 1) [22,27,16,2,18,6] -> [2,27,16,22,18,6] -> [2,6,16,22,18,27] -> [2,6,16,18,22,27]
# 2) Yukarıdaki seriyi n elemanlı kabul edersek sırayla n,(n-1),(n-2),....,1 işlem yapacağımızdan toplam işlem sayısı
#  [n*(n+1)]/2 = [(n^2)+n]/2 olacağından Big O gösterimi O(n^2)'dir.
# 3) Average Case: Aradığımız sayının 16 olmasıdır.
#    Worst Case: Aradığımız sayının 27 olmasıdır.
#    Best Case: Aradığımız sayının 2 olmasıdır.
# 4) Dizi sıralandıktan sonra 18 sayısı Average Case kapsamına girer. Çünkü en sonda ya da en başta değil.

# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı:
# 1. [7,3,5,8,2,9,4,15,6]
# 2. [2,3,5,8,7,9,4,15,6]
# 3. [2,3,4,8,7,9,5,15,6]
# 4. [2,3,4,5,7,9,8,15,6]
 
