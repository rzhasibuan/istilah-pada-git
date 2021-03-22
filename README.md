# INI ADALAH ISTILAH-ISTILAH PADA GIT
```
git init 
```
berfungsi untuk membuat repository local yang nantinya akan membuat sebuah directory .git  

```
git add namafile
git add .
```
git add berfungsi untuk menambahkan sebuah file kedalam repo 

```
git clone ssh://user@domain.com/repo.git
git clone https://github.com/user/repo.git
```
git clone berfungsi untuk mengcloning atau mengandakan sebuah repository 

```
git commit -m "ketik pesan disini"
```
git commit berfungsi untuk membuat sebuah commit -m berfungsi untuk membuat sebuah massage/pesan pada saat melakukan commit 

## membuat percabangan pada git pada git mengunakan git branch 

```
git branch namabranch 
<!-- berfungsi untuk membuat branch baru -->

git branch -av
<!-- berfungsi untuk melihat branch yang aktif dengan penanda * -->

git branch -M namabranch
<!-- berfungsi untuk membuat branch menjadi branch master dengan mengunakan parameter -M -->

git branch -d namabranch
<!-- berfungsi  menghapus sebuah branch dengan mengunakan parameter -d sebelum nama branch-->

```
## pengunaan git remote to github 

```
git remote add namaremote https://github.com/username/repo.git

git remote add origin https://github.com/rzhasibuan/istilah-pada-git.git


```
git remote berfungsi untuk meremote repository github kedalam repository local komputer kita 



## pengunaan git status

```
git status 

```
git status berfungsi untuk melihat status dari file pada repo contohnya seperti melihat perubahan pada file didalam repo dan jika kita telah melakukan commit maka pada git status sudah tidak ada lagi 


## pengunaan git push
```
git push -f origin main

```
git push berfungsi untuk push data yang berada di repo local ke dalam repo github kita 

## berpindah branch 
```
git checkout namabranch

git checkout fiturbaru

```
untuk melakukan perpindahan branch mengunakan perintah git checkout 

 ## mengabungkan branch 

 ```
  git marge 

 ```