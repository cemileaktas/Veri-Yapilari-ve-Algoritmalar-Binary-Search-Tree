# Proje 3 
## [7,5,1,8,3,6,0,9,4,2] dizisinin Binary Search Tree aşamalarını yazınız.
 Root belirlenir. Roottan büyük olanlar sol tarafta büyük olanlar sağ tarafta toplanır.

1.adım: Root:7
2.adım: 5 < 7                

             7 
            /
           5
    
3.adım:  1 < 7

             7
            / 
           5
          /
         1
         
4.adım: 8 > 7

               7
              / \
             5   8
            /
          1
          
5.adım: 3 < 7 

              7
             / \
            5   8
           /
          1
           \
             3
            
6.adım: 6 < 7

               7
              / \
             5   8
            / \
           1   6
           \
             3
            
7.adım: 0 < 7

               7
              / \
             5   8
            / \
           1   6
          / \
         0   3
        
8.adım: 9 > 7 

                7
               / \
              5   8
             / \    \
            1   6    9
           / \
          0   3
         
9.adım: 4 < 7
         
                 7
                / \
               5    8
              / \     \
             1   6     9
            / \
           0   3
                \
                 4
                
10 .adım: 2 < 7

                   7
                  / \
                 5   8
                / \    \
               1   6    9
              / \
             0   3
                 / \
                2    4
                

