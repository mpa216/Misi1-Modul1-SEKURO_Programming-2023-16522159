### Git Branch and Merge

Ada Cara nyingkat proses git add dengan git commit (khusus file yang statusnya modified), yaitu dengan :

git commit -am "message"

![messageImage_1675477022719](https://user-images.githubusercontent.com/123876878/216741330-ccdff84a-1135-44f5-bafd-d5e60d56b9cf.jpg)

Membuat branch baru dilakukan dengan : 

git branch <branch_name>

![image](https://user-images.githubusercontent.com/123876878/216742313-1cd7ec08-c7a0-433a-8d2b-81738b492f86.png)

Membuat custon name untuk sebuah command dapat dilakukan dengan "alias"

![image](https://user-images.githubusercontent.com/123876878/216741661-04dec18e-2096-4102-a2d2-3e574576d8ba.png)

Pindah branch dapat dilakukan dengan : 

git checkout <nama_branch>

![image](https://user-images.githubusercontent.com/123876878/216741967-e25c9aac-e090-457e-a5f7-5439e4c83ad2.png)

Branch yg ditunuk oleh head Git akan berpengaruh pada keberadaan file di folder kita

![image](https://user-images.githubusercontent.com/123876878/216742184-7f25efce-6875-44b6-a242-eab8941f2142.png)

![image](https://user-images.githubusercontent.com/123876878/216742202-18fd2174-50b7-4b30-8ea1-dbf728d0316b.png)

Cara menggabungkan cabang atau merge adalah dengan :

git merge <nama_branch>

![image](https://user-images.githubusercontent.com/123876878/216743901-483a9d4a-d1a4-4fd6-992c-adc10f0c495a.png)

Menghapus branch dan mencek branch yg telah tergabung dengan :

git brach --merged
git branch -d <nama_branch>

![image](https://user-images.githubusercontent.com/123876878/216745373-f0dbcede-27a3-4bf0-bbd7-5ef40cace40f.png)

Merge itu ada 2 jenis, 

1. Fast Forward, klo yg mau di merge satu jalur dengan master
2. Three way Merge, klo yg mau di merge tidak satu jalur dengan master




