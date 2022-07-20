# proje2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.


                                                              [16,21,11,8,12,22]  
                                                              
                         [16,21,11]                                                                           [8,12,22]                        //3 er elemanlı 2 gruba ayrılır
                         
             [16]                        [21,11]                                                     [8]                          [12,22]      // tekrar kendi içinde gruplara ayrılır
             
             [16]               [21]                 [11]                                            [8]                   [12]            [22]// tekil olarak bulunurlar
             
             [16]                        [11,21]                                                     [8]                          [12,22]      // kendi içlerinde sıralanır 
             
                         [11,16,21]                                                                           [8,12,22]                        // diğer grup ile birleşerek sıralanır 
                         
                                                              [8,11,12,16,21,22]                                                               // son sıralama oluşur

# Big O gösterimi(nlogn)
