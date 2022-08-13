# Merge-Sort-Projesi
[16,21,11,8,12,22] -> Merge Sort
   Soru1)Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
         Adım 1: Dizimizi ortadan ikiye böldük
                 [16,21,11] [8,12,22]
          Adım 2: Tekrar 2'ye bölüyoruz
                 [16,21] [11] [8] [12,22]
          Adım3: Tek eleman kalıncaya kadar bölmemiz gerekiyor. O nedenle tekrar bölüyoruz
                 [16] [21] [11] [8] [12] [22]
          Adım4: Tek eleman kaldıktan sonra artık sıralı bir şekilde birleştirmeye başlamamız gerekiyor
                 [16,21] [8,11] [12,22]
          Adım5: Elimizde olan küçük sıralı dizileri yine sıralı olarak birleştiriyoruz
                 [8,11,16,21] [12,22]
          Adım6: Son adım artık dizimizi sıralı bir sonuca ulaştırmış oluyoruz bundan önce uyguladığımız mantığı tekrarlayarak
                 [8,11,12,16,21,22]
                 
      Soru2)Big-O gösterimini yazınız.
            Merge Sort'da Big-O Notation (nlogn)'dir. O(nlogn).
            
www.patika.dev 
