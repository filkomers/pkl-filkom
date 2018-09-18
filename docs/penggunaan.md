# Penggunaan

## Prasyarat

Anda direkomendasikan untuk memiliki instalasi TexLive 2018 atau
terbaru. Kami merekomendasikan anda untuk mengikuti panduan
[ini](https://tex.stackexchange.com/questions/1092/how-to-install-vanilla-texlive-on-debian-or-ubuntu/95373#95373).


## Memulai

Anda dapat mengunduh *repository* ini dengan cara manual atau
menggunakan `git clone`

``` bash
$ git clone https://gitlab.com/template-tugasakhir-latex/template-pkl-latex
```

Silahkan `checkout` *branch* yang anda inginkan. *untuk saat ini hanya
branch filkom yang tersedia*

## Pengisian Data

Isi data diri anda pada berkas `proposal.tex` pada bagian "Fill your
data here".

## Menambah Daftar Pustaka

Silahkan tambahkan daftar pustaka anda pada berkas
`daftar-pustaka.bib`

## Ekspor ke PDF

Anda dapat mengekspor ke PDF dengan cara:

``` bash
xelatex pkl.tex
```

Atau menggunakan *bash script* yang kami sediakan

``` bash
chmod +x compile-latex.sh
./compile-latex.sh
```

Anda dapat menghapus berkas aux yang dihasilkan latex dengan
`delete-aux.sh`



