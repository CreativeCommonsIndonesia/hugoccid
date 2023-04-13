---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
featured_image: "/img/skyline.png"
author:
  name: Creative Commons Indonesia
  photo: /img/favicon.png
  link: https://creativecommons.or.id
additionalLinks: []
# additionalLinks: 
#   - title: Foto
#     link: https://google.com
#   - title: Salindia
#     link: https://drive.google.com
draft: true
---

## Menambahkan link youtube
Contoh menambahkan:
```
{{< youtube id="masukkan-id-video-youtube" class="w-sm-50 float-end" >}} Ini adalah kapsinya, ada urlnya juga lho <a href="https://creativecommons.or.id">CC-ID!</a>. {{< /youtube >}}
```
Contoh hasil:
{{< youtube id="tYODFSWTD8k" class="w-sm-50 float-end" >}} Video perkenalan <a href="https://creativecommons.or.id">CCID</a>. {{< /youtube >}}

## Menambahkan gambar berkapsi
Contoh menambahkan:
```
{{< gambar-kapsi src="lokasi-gambar-dalam-folder-static atau masukkan-alamat-web-lengkap-disini" class="w-50 float-end my-3" >}} Masukkan kapsinya di sini. {{< /gambar-kapsi >}}
```
Contoh hasil:
{{< gambar-kapsi src="/img/diskusi publik.jpg" class="w-50 float-end my-3" >}}Diskusi Terbatas Creative Common Indonesia, 7 Juli 2012.{{< /gambar-kapsi >}}

{{< gambar-kapsi src="https://upload.wikimedia.org/wikipedia/commons/0/05/Wikimedia-logo-id.svg" class="w-50 float-end my-3" >}} Gambar dari url web lengkap {{< /gambar-kapsi >}}