[16,21,11,8,12,22] -> Merge Sort <br>
1- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.<br>
               [16,21,11]  --   [8,12,22] <br>
      [16,21] - [11]        --       [8,12] - [22]<br>
[16] - [21] - [11]           --         [8] - [12] - [22]<br>
      [16,21] -  [11]       --        [8,12] - [22]<br>
           [11,16,21]      --     [8,12,22] <br>
                  [8,11,12,16,21,22]<br>
2- Big-O gösterimini yazınız.<br>
2^x=n <br>
O(nlogn)