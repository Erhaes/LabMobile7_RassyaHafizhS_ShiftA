# LabMobile7_RassyaHafizhS_ShiftA

Nama    : Rassya Hafizh Suharjo

NIM     : H1D022068

Shift Baru : A

Shift Lama : D

## Penjelasan Komponen Ionic

Framework javascript yang digunakan adalah Vue
Template ionic yang digunakan sidemenu

Contoh komponen pada ionic tersedia di documentation ionic yang dapat diakses dengan mengklik link yang ada di starter template ionic. Programmer dapat mengambil contoh kode kemudian dimodifikasi sesuai kebutuhan.

Dalam vue, component harus diimport terlebih dahulu sebelum digunakan. Contoh pada 'ToDoListPage.vue'
```vue
<script setup lang="ts">
import { IonButtons, IonContent, IonHeader, IonMenuButton, IonPage, IonTitle, IonToolbar, IonSearchbar,
  IonCard, IonCardContent, IonCardHeader, IonCardSubtitle, IonCardTitle
 } from '@ionic/vue';
</script>
```

Component yang ditambahkan ke dalam kode ini :
 ### 1. Searchbar
    ![Searchbar](gambar/searchbar.png)

    Langkah - langkah :
    Dalam halaman dokumentasi komponen ionic ke halaman searchbar kemudian pilih searchbar mana yang ingin digunakan setelah itu pilih vue.
    Saya menggunakan searchbar dengan clear button. Terdapat kode untuk berbagai search bar dan pilih sesuai kebutuhan.
    ![Pilihan Searchbar](gambar/pilihansearch.png)

    Dalam dokumentasi dicontohkan searchbar dalam berbagai jenis. Pilih sesuai kebutuhan untuk dimasukkan ke dalam kode yang dibuat. Di sini saya memilih yang resetbutton focus
    ![Pilihan Kode Searchbar](gambar/pilihankodesearch.png)

    Setelah mendapatkan kode yang dibutuhkan masukkan kode ke dalam kode yang dibuat dan modifikasi komponen sesuai kebutuhan
    ```vue
    <div id="container">
            <ion-searchbar show-clear-button="focus"></ion-searchbar>
    ```

    Lakukan import komponen pada halaman tersebut dalam <script>
    ```vue
    <script setup lang="ts">
    import { IonButtons, IonContent, IonHeader, IonMenuButton, IonPage, IonTitle, IonToolbar, IonSearchbar,
    IonCard, IonCardContent, IonCardHeader, IonCardSubtitle, IonCardTitle
    } from '@ionic/vue';
    </script>
```
selesai



