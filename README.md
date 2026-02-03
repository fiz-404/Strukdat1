# Tugas Kelompok
laporan; ADT( .h,.c, main.c)
// array
// array statis(alokasi fix)
// pointer
// array dinamis(alokasi tak ditentukam/tak terdefininsi))
// ptr_y = (int *) malloc (sizeof(int) * n)

// karakterisitik
// kontigu, makan 1 blok memorib dan tak terpi=utus
// bagus untuk menyimpan data yang sudah tau besarnya
// cepat ketika diakses karena langsung menuju indeks dari array
// --> random access ` O(1)/konstan
// sulit dalam meng increase size array

// linked list
// definisi: linked list boleh kosong,
//  jika berisi 1, linked list hanya berisi head dengan nextnya
//  jika lebih dari satu maka setiap node berantai menurut pointer next dengan node terakhir nextnya null
// dengan elemen list
//- berantai. setiap node
// lebih dari 1 setiap elmlist berantai menurut pointer next, denga elmnlist nextnya null
//  addition, insertsion, removal, deletion
// search: nilai atau adress ~ menelusuri dari awal
// linear/sekuensial
// elmtnlist struktirnya [info, next]
//  NULL -- stdlib.h

// Variasi [prev, info, next]

// #include <stdio.h>
// #include <stdlib.h>
// struct Node{
//     int info;
//     ElmntList *next;
// }ElmntList;
// typedef ElmtList

// struct Node{
//     int info;
//     ElmntList *next;
// }ElmntList;
// variasi [head, size]
// typedef struct {
//     ElmntList* head;
//     int size;
// }
- [ ] init/create
- [ ] isEmpty
- [ ] allocate
- [ ] deallocate
- [ ] add/insert
- [ ] search
- [ ] del/remove
- [ ] destroy
- [ ] length
