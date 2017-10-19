# ANALISA DAN DESAIN PERANCANGAN SISTEM INFORMASI SOP PENGEMBANGAN APLIKASI
## ABSTRAK
Pengembangan aplikasi, atau bisa disebut sebagai pengembangan *software* atau desain *software*, kerap kali disalahartikan sebagai kegiatan dimana seorang *programmer* melakukan *coding*, tetapi sebenarnya yang dimaksud pengembangan aplikasi merupakan serangkaian proses yang dilakukan dari saat pembuatan kosep aplikasi hingga aplikasi tersebut selesai dan siap digunakan.
## DAFTAR ISI
**1. PENDAHULUAN**
**1.1 Latar Belakang**
1.2  Tujuan
**2. DESKRIPSI DAN RUANG LINGKUP**
**3. ANALISIS DAN PEMBAHASAN**
3.1 Kebutuhan *Software* dan *Hardware*
3.1.1 *Software*
3.1.2 *Hardware*
3.2 Analisis Permasalahan
3.3 Solusi
3.4 Perancangan Database
3.4.1 Tujuan Perancangan Dtabase
3.4.2 Proses Perancangan Database
3.5 Perancangan Sistem
3.5.1 Proses Pengajuan
3.5.1.1 Use Case Diagram
3.5.1.2 Activity Diagram
3.5.1.3 Sequence Diagram
3.5.1.4 State Chart Diagram
3.5.2 Proses Penganggaran
3.5.2.1 Use Case Diagram
3.5.2.2 Activity Diagram
3.5.2.3 Sequence Diagram
3.5.2.4 State Chart Diagram
3.5.3 Proses Pembuatan Aplikasi oleh Tim Internal
3.5.3.1 Use case Diagram
3.5.3.2 Activity Diagram
3.5.3.3 Sequence Diagram
3.5.3.4 State Chart Diagram
3.5.4 Prose pembuatan Apliksi oleh Pihak ke-3
3.5.4.1 Use Case Diagram
3.5.4.2 Activity Diagram
3.5.4.3 Sequence Diagram
3.5.4.4 State Chart Diagram

## 1.  PENDAHULUAN
### 1.1 Latar Belakang
Salah satu sasaran Dinas Komunikasi, Informasi, Statistika dan Persandian adalah membuat sebuah sistem yang terkelola rapi dalam segala hal, baik dalam bidang IT maupun bidang yang lainnya agar mampu menyelenggarakan seluruh kegiatannya secara mandiri dan sesuai dengan ketentuan yang berlaku.

Untuk mencapai hal tersebut, diperlukan suatu prosedur operasional yang jelas dan standar bagi semua pihak yang terlibat dalam mencapai sasaran tersebut. Praktik-praktik baik yang telah berlangsung di KOMINFO Banten perlu distandarisasi dan didokumentasikan agar menjadi acuan bagi manejemen dalam menjalankan tugas dan fungsinya serta menjamin keberlangsungan implementasi praktik-praktik tersebut.

Terkait dengan sasaran tersebut kami bertujuan akan membangun standarisasi sistem pengembangan apliaksi yang dapat meningkatkan efisiensi dan efektifitas kinerja dinas terkait serta mampu mebagikan informasi yang dibutuhkan oleh berbagai pihak untuk kepentingan proses pengambilan keputusan. Untuk menuju kepada standarisasi dalam pengembangan aplikasi perlu diciptakan terlebih dahulu sistem manual  terstandar atau semacam *Standar Operating Procedur* (SOP) untuk seluruh pengembangan aplikasi yang ada sehingga dapat dipahami oleh semua pihak yang terlibat.

### 1.2 Tujuan
*Standard Operating Prosedur (SOP)* pada dasarnya adalah pedoman yang berisi prosedur-prosedur operasioanl standar yang ada dalam suatu instansi yang digunakan untuk memastikan bahwa semua keputusan  dan tindakan, sertapenggunaan fasilitas-fasilitas proses yang dilakukan oleh orang-orang dalam instansi  berjalan dengan efisien dan efektif , konsisten, standar dan sistematis. Dengan adanya sistem manual standar atau (SOP) diharapkan dapat meningkatkan efisiensi dan efektifitas kinerja dalam pengembangan aplikasi yang diberikan oleh KOMINFO. Dengan adanya instruksi kerja yang terstandarisasi  maka semua kegiatan pengembangan aplikasi dapat dilakukan secara konsisten oleh siapapun yang sedang mengajukan pengembangan aplikasi. Hal ini dapat meningkatkan efisien dan efektifitas kerja serta meminimalisir prosedur operasi yang tidak jelas. Dengan demikian dapat dipastikan melalui SOP ini akan dapat meningkatkan efisiensi dan efektifitas kerja pihak-pihak yang terkait.

## 2. DESKRIPSI DAN RUANG LINGKUP
Pengembangan aplikasi ini dapat dipisah menjadi 4 proses yang dimulai dari proses pengajuan, proses penganggaran, proses pembuatan aplikasi dari tim internal dan proses pembuatan aplikasi oleh pihak ke-3. SOP yang dihasilkan adalah SOP pengajuan pengembangan aplikasi, SOP penganggaran pengembangan aplikasi, SOP pembuatan aplikasi dari tim internal dan SOP pembuatan aplikasi oleh pihak ke-3.

Dalam jurnal ini akan mengembangkan standarisasi pengembangan aplikasi dari mulai proses pengajuan pengembangan aplikasi hingga proses pembuatan aplikasi menggunakan alur prototyping.
* Ilustrasi Alur Prototyping
[![Ilustrasi Alur Prototyping](http://img.bangunbanten.com/potret/jalur-proses-dan-perancangan-data-base-use-case/20171018_alur-prototype.png)](http://img.bangunbanten.com/potret/jalur-proses-dan-perancangan-data-base-use-case/20171018_alur-prototype.png)

## 3. ANALISIS DAN PEMBAHASAN 
### 3.1 Kebutuhan Software dan Hardware
Adapun alat bantu *software* dan *hardware* dalam melakukan analisis dan desain perancanangan ini adalah sebagai berikut:

#### 3.1.1 *Software*
* Ubuntu 17.04
* Typora (markdown)
* Gliffy Diagram
* 
#### 3.1.2 *Hardware*
Laptop dengan spesifikasi sebagai berikut:
* Intel Celeron N2830 *Speed* 2.16 Ghz *Turbo Boost* 2.41 Ghz
* Memori DDR3 2Gb
* Hard disk 500 Gb

### 3.2 Analisis Permasalahan
Permasalahan yang terjadi saat ini adalah sebagai berikut:
1. Belum adanya standarisasi dalam perancangan pengembangan aplikasi
2. Belum tertatanya proses dalam pengembangan aplikasi

### 3.3 Solusi
Solusi yang kami tawarkan adalah pembuatan desain perancangan sistem informasi SOP pengembangan aplikasi adalah:
1. Menstandarisasi perancangan pengembangan aplikasi
2. Menata proses pengembangan aplikasi mulai proses pengajuan sampai proses pembuatan aplikasi

### 3.4 Perancangan Database
pada database yang digunakan oleh single user atau hanya beberapa user saja, perancangan database tidak sulit. tetapi jika ukuran database yang sedang atau besar ( 25 - ratusan user yang berisikan jutaan bytes informasi dan melibatkan ratusan query dan program program aplikasi) perancangan database menjadi sangat komplek. Oleh karena itu para pemakai mengharapkan penggunaan database yang sedemikian rupa sehingga sistem harus dapat memenuhi kebutuhan-kebutuhan seluruh user tersebut.

#### 3.4.1 Tujuan perancangan database:
* Untuk memenuhi informasi yang diberisikan kebutuhan-kebutuhan user secara khusus dan aplikasi-aplikasinya.
* Memudahkan pengertian struktur informasi
* Mendukung kebutuhan-kebutuhan pemrosesan dan beberapa obyek penampilan (*response time, processing time dan storage space*)

#### 3.4.2 Proses Perancangan Database
proses perancangan database terdiri dari 6 tahap:
* Tahap 1, Pengumpulan data dan analisis
* Tahap 2, Perancangan database secara konseptual
* tahap 3, Pemilihan DBMS
* Tahap 4, Perancangan Database secara logika (*data model mapping*)
* Tahap 5, Perancangan database secara fisik
* Tahap 6, Implementasi sistem database

### 3.5 Perancangan Sistem
Permodelan rancangan sistem yang digunakan adalah UML (*Unified Modeling Language*). Menurut Whitten dan Bentley , *Unified Modeling Language* adalah kumpulan rancangan diagram untuk membangun sebuah sistem atau aplikasi yang dimana setiap diagram menyediakan sistem informasi kepada tim pengembang dengan berbagai sudut pandang yang berbeda-beda. UML yang digunakan terdiri dari *use case diagram, activity diagram, sequence diagram* dan *state chart diagram*.

#### 3.5.1 Proses Pengajuan
##### 3.5.1.1. *Use Case Diagram*
* *Use Case Diagram* Proses Pengajuan
[![Layout Tampilan Form Update](http://img.bangunbanten.com/sop/proses-pengajuan/use-case-diagram/20171010-use-case-diagram-proses-pengajuan)](http://img.bangunbanten.com/sop/proses-pengajuan/use-case-diagram/20171010-use-case-diagram-proses-pengajuan)

* *Use Case Diagram* Staff OPD
[![Use Case Diagram Staff OPD](http://img.bangunbanten.com/sop/proses-pengajuan/use-case-diagram/20171009-use-case-diagram-staff-opd)](http://img.bangunbanten.com/sop/proses-pengajuan/use-case-diagram/20171009-use-case-diagram-staff-opd)

* *Use Case Diagram* Kepala Seksi OPD
[![Use Case Diagram Kepala Seksi OPD](http://img.bangunbanten.com/sop/proses-pengajuan/use-case-diagram/20171010-use-case-diagram-kepala-seksi-opd)](http://img.bangunbanten.com/sop/proses-pengajuan/use-case-diagram/20171010-use-case-diagram-kepala-seksi-opd)

* *Use Case Diagram* Kepala Dinas OPD
[![Use Case Diagram Kepala Dinas OPD](http://img.bangunbanten.com/sop/proses-pengajuan/use-case-diagram/20171010-use-case-diagram-kepala-dinas-opd)](http://img.bangunbanten.com/sop/proses-pengajuan/use-case-diagram/20171010-use-case-diagram-kepala-dinas-opd)

* *Use Case Diagram* Kepala Dinas KISP
[![Use Case Diagram Kepala Dinas KISP](http://img.bangunbanten.com/sop/proses-pengajuan/use-case-diagram/20171010-use-case-diagram-kepala-dinas-kisp)](http://img.bangunbanten.com/sop/proses-pengajuan/use-case-diagram/20171010-use-case-diagram-kepala-dinas-kisp)

* *Use Case Diagram* Kepala Seksi Pengembangan Aplikasi Dinas KISP
[![Use Case Diagram Kepala Seksi Pengembangan Aplikasi Dinas KISP](http://img.bangunbanten.com/sop/proses-pengajuan/use-case-diagram/20171010-use-case-diagram-kepala-seksi-pengembangan-aplikasi-dinas-kisp)](http://img.bangunbanten.com/sop/proses-pengajuan/use-case-diagram/20171010-use-case-diagram-kepala-seksi-pengembangan-aplikasi-dinas-kisp)

##### 3.5.1.2 *Activity Diagram*
* *Activity Diagram* Proses Pengajuan
[![Activity Diagram Proses Pengajuan](http://img.bangunbanten.com/sop/proses-pengajuan/activity-diagram/20171010-activity-diagram-proses-pengajuan)](http://img.bangunbanten.com/sop/proses-pengajuan/activity-diagram/20171010-activity-diagram-proses-pengajuan)

##### 3.5.1.3 *Sequence Diagram*
* *Sequence Diagram* Proses Pengajuan
[![Sequence Diagram Proses Pengajuan](http://img.bangunbanten.com/sop/proses-pengajuan/sequence-diagram/20171009-sequence-diagram-proses-pengajuan)](http://img.bangunbanten.com/sop/proses-pengajuan/sequence-diagram/20171009-sequence-diagram-proses-pengajuan)

##### 3.5.1.4 *State Chart Diagram*
* *State Chart Diagram* Staff OPD
[![State Chart Diagram Staff OPD](http://img.bangunbanten.com/sop/proses-pengajuan/state-chart-diagram/20171010-state-chart-diagram-staff-opd)](http://img.bangunbanten.com/sop/proses-pengajuan/state-chart-diagram/20171010-state-chart-diagram-staff-opd)

* *State Chart Diagram* Kepala Seksi OPD
[![State Chart Diagram Kepala Seksi OPD](http://img.bangunbanten.com/sop/proses-pengajuan/state-chart-diagram/20171010-state-chart-diagram-kepala-seksi-opd)](http://img.bangunbanten.com/sop/proses-pengajuan/state-chart-diagram/20171010-state-chart-diagram-kepala-seksi-opd)

* *State Chart Diagram* Kepala Dinas OPD
[![State Chart Diagram Kepala Dinas OPD](http://img.bangunbanten.com/sop/proses-pengajuan/state-chart-diagram/20171010-state-chart-diagram-kepala-dinas-opd)](http://img.bangunbanten.com/sop/proses-pengajuan/state-chart-diagram/20171010-state-chart-diagram-kepala-dinas-opd)

* *State Chart Diagram* Kepala Dinas KISP
[![State Chart Diagram Kepala Dinas KISP](http://img.bangunbanten.com/sop/proses-pengajuan/state-chart-diagram/20171010-state-chart-diagram-kepala-dinas-kisp)](http://img.bangunbanten.com/sop/proses-pengajuan/state-chart-diagram/20171010-state-chart-diagram-kepala-dinas-kisp)

* *State Chart Diagram* Kepala Seksi Pengembangan Aplikasi Dinas KISP
[![State Chart Diagram Kepala Seksi Pengembangan Aplikasi Dinas KISP](http://img.bangunbanten.com/sop/proses-pengajuan/state-chart-diagram/20171010-state-chart-diagram-kepala-seksi-pengembangan-aplikasi-dinas-kisp)](http://img.bangunbanten.com/sop/proses-pengajuan/state-chart-diagram/20171010-state-chart-diagram-kepala-seksi-pengembangan-aplikasi-dinas-kisp)

#### 3.5.2 Proses Penganggaran
##### 3.5.2.1 *Use Case Diagram*
* *Use Case Diagram* Seksi pengembangan Aplikasi Dinas KISP / OPD
[![Use Case Diagram Seksi pengembangan Aplikasi Dinas KISP / OPD](http://img.bangunbanten.com/sop/proses-penganggaran/use-case/use-case)](http://img.bangunbanten.com/sop/proses-penganggaran/use-case/use-case)

* *Use Case Diagram* Bappeda
[![Use Case Diagram Bappeda](http://img.bangunbanten.com/sop/proses-penganggaran/use-case/20171016_use-case-diagram-bappeda.jpg)](http://img.bangunbanten.com/sop/proses-penganggaran/use-case/20171016_use-case-diagram-bappeda.jpg)

* *Use Case Diagram* BPKAD
[![Use Case Diagram BPKAD](http://img.bangunbanten.com/sop/proses-penganggaran/use-case/20171016_use-case-diagram-bpkad.jpg)](http://img.bangunbanten.com/sop/proses-penganggaran/use-case/20171016_use-case-diagram-bpkad.jpg)

* *Use Case Diagram* Adpem
[![Use Case Diagram Adpem](http://img.bangunbanten.com/sop/proses-penganggaran/use-case/20171016_use-case-diagram-adpem.jpg)](http://img.bangunbanten.com/sop/proses-penganggaran/use-case/20171016_use-case-diagram-adpem.jpg)

##### 3.5.2.2 Activity Diagram
* *Activity Diagram* Proses Penganggaran
[![Activity Diagram Proses Penganggaran](http://img.bangunbanten.com/sop/proses-penganggaran/activity-diagram/jpg/20171016_activity-diagram-proses-pengajuan.jpg)](http://img.bangunbanten.com/sop/proses-penganggaran/activity-diagram/jpg/20171016_activity-diagram-proses-pengajuan.jpg)

##### 3.5.2.3 Sequence Diagaram
* *Sequence Diagram* Proses Penganggaran
[![Sequence Diagram Proses Penganggaran](http://img.bangunbanten.com/sop/proses-penganggaran/sequence-diagram/20171018_sequence-diagram-proses-penganggaran.png)](http://img.bangunbanten.com/sop/proses-penganggaran/sequence-diagram/20171018_sequence-diagram-proses-penganggaran.png)

##### 3.5.2.4 State Chart Diagram
* *State Chart Diagram* Seksi Pengembangan Aplikasi Dinas KISP / OPD
[![State Chart Diagram Seksi Pengembangan Aplikasi Dinas KISP / OPD](http://img.bangunbanten.com/sop/proses-penganggaran/state-chart-diagram-penganggaran/20171018_state-chart-diagram-seksi-dinas-kisp-opd)](http://img.bangunbanten.com/sop/proses-penganggaran/state-chart-diagram-penganggaran/20171018_state-chart-diagram-seksi-dinas-kisp-opd)

* *State Chart Diagram* Bappeda
[![State Chart Diagram Bappeda](http://img.bangunbanten.com/sop/proses-penganggaran/state-chart-diagram-penganggaran/20171018_state-chart-diagram-dinas-bappeda)](http://img.bangunbanten.com/sop/proses-penganggaran/state-chart-diagram-penganggaran/20171018_state-chart-diagram-dinas-bappeda)

* *State Chart Diagram* BPKAD
[![State Chart Diagram BPKAD](http://img.bangunbanten.com/sop/proses-penganggaran/state-chart-diagram-penganggaran/20171018_state-chart-diagram-dinas-bpkad)](http://img.bangunbanten.com/sop/proses-penganggaran/state-chart-diagram-penganggaran/20171018_state-chart-diagram-dinas-bpkad)

* *State Chart Diagram* Adpem
[![State Chart Diagram Adpem](http://img.bangunbanten.com/sop/proses-penganggaran/state-chart-diagram-penganggaran/20171018_state-chart-diagram-dinas-adpem)](http://img.bangunbanten.com/sop/proses-penganggaran/state-chart-diagram-penganggaran/20171018_state-chart-diagram-dinas-adpem)

#### 3.5.3 Proses Pembuatan Aplikasi oleh Tim Internal
##### 3.5.3.1 Use Case Diagram
* *Use Case Diagram* Proses Pembuatan Aplikasi oleh Tim Internal
[![Use Case Diagram Proses Pembuatan Aplikasi oleh Tim Internal](http://img.bangunbanten.com/sop/proses-perancangan-oleh-tim-internal/20171010-use-case-proses-pembuatan-aplikasi-oleh-tim-internal)](http://img.bangunbanten.com/sop/proses-perancangan-oleh-tim-internal/20171010-use-case-proses-pembuatan-aplikasi-oleh-tim-internal)

##### 3.5.3.2 Activity Diagram
* *Activity Diagram* Proses Pembuatan Aplikasi oleh Tim Internal
[![Activity Diagram Proses Pembuatan Aplikasi oleh Tim Internal](http://img.bangunbanten.com/sop/proses-perancangan-oleh-tim-internal/20171010-activity-diagram-proses-pengerjaan-pihak-internal)](http://img.bangunbanten.com/sop/proses-perancangan-oleh-tim-internal/20171010-activity-diagram-proses-pengerjaan-pihak-internal)

##### 3.5.3.3 Sequence Diagram
* *Sequence Diagram* Proses Pembuatan Aplikasi oleh Tim Internal
[![Sequence Diagram Proses Pembuatan Aplikasi oleh Tim Internal](http://img.bangunbanten.com/sop/proses-perancangan-oleh-tim-internal/20171010-sequence-diagram-proses-pembuatan-aplikasi-oleh-pihak-internal)](http://img.bangunbanten.com/sop/proses-perancangan-oleh-tim-internal/20171010-sequence-diagram-proses-pembuatan-aplikasi-oleh-pihak-internal)

##### 3.5.3.4 State Chart Diagram
* *State Chart Diagram* Seksi Pengembangan Aplikasi Dinas KISP
[![State Chart Diagram Seksi Pengembangan Aplikasi Dinas KISP](http://img.bangunbanten.com/sop/proses-perancangan-oleh-tim-internal/20171011-state-chart-diagram-seksi-pengembangan-aplikasi-dinas-kisp)](http://img.bangunbanten.com/sop/proses-perancangan-oleh-tim-internal/20171011-state-chart-diagram-seksi-pengembangan-aplikasi-dinas-kisp)

* *State Chart Diagram* OPD
[![State Chart Diagram OPD](http://img.bangunbanten.com/sop/proses-perancangan-oleh-tim-internal/20171011-state-chart-diagram-opd)](http://img.bangunbanten.com/sop/proses-perancangan-oleh-tim-internal/20171011-state-chart-diagram-opd)

#### 3.5.4 Proses Pembuatan Aplikasi oleh Pihak Ke-3
##### 3.5.4.1 Use Case Diagram
* *Use Case Diagram* Proses Pembuatan Aplikasi oleh Pihak Ke-3
[![Use Case Diagram Proses Pembuatan Aplikasi oleh Pihak Ke-3](http://img.bangunbanten.com/sop/proses-pembuatan-aplikasi-oleh-pihak-ke-3/use-case/20171018_proses-pembuatan-aplikasi-oleh-pihak-ke-3)](http://img.bangunbanten.com/sop/proses-pembuatan-aplikasi-oleh-pihak-ke-3/use-case/20171018_proses-pembuatan-aplikasi-oleh-pihak-ke-3)

##### 3.5.4.2 Activity Diagram
* *Activity Diagram* Proses Pembuatan Aplikasi oleh Pihak Ke-3
[![Activity Diagram Proses Pembuatan Aplikasi oleh Pihak Ke-3](http://img.bangunbanten.com/sop/proses-pembuatan-aplikasi-oleh-pihak-ke-3/activity-diagram/20171016_activity-diagram)](http://img.bangunbanten.com/sop/proses-pembuatan-aplikasi-oleh-pihak-ke-3/activity-diagram/20171016_activity-diagram)

##### 3.5.4.3 Sequence Diagram
* *Sequence Diagram* Proses Pembuatan Aplikasi oleh Pihak Ke-3
[![Sequence Diagram Proses Pembuatan Aplikasi oleh Pihak Ke-3](http://img.bangunbanten.com/sop/proses-pembuatan-aplikasi-oleh-pihak-ke-3/sequence-diagram/20171019_sequence-diagram-pembuatan-aplikasi-oleh-pihak-ke-3.png)](http://img.bangunbanten.com/sop/proses-pembuatan-aplikasi-oleh-pihak-ke-3/sequence-diagram/20171019_sequence-diagram-pembuatan-aplikasi-oleh-pihak-ke-3.png)

##### 3.5.4.4 State Chart Diagram
* *State Chart Diagram* Seksi Pengembangan Aplikasi Dinas KISP
[![State Chart Diagram Seksi Pengembangan Aplikasi Dinas KISP](http://img.bangunbanten.com/sop/proses-pembuatan-aplikasi-oleh-pihak-ke-3/state-chart-diagram/20171016_state-chart-pengembangan-aplikasi-dinas-kisp)](http://img.bangunbanten.com/sop/proses-pembuatan-aplikasi-oleh-pihak-ke-3/state-chart-diagram/20171016_state-chart-pengembangan-aplikasi-dinas-kisp)

* *State Chart Diagram* Pihak Ke-3
[![State Chart Diagram Pihak Ke-3](http://img.bangunbanten.com/sop/proses-pembuatan-aplikasi-oleh-pihak-ke-3/state-chart-diagram/20171018_state-chart-diagram-pihak-ke-3)](http://img.bangunbanten.com/sop/proses-pembuatan-aplikasi-oleh-pihak-ke-3/state-chart-diagram/20171018_state-chart-diagram-pihak-ke-3)

* *State Chart Diagram* OPD
[![State Chart Diagram OPD](http://img.bangunbanten.com/sop/proses-pembuatan-aplikasi-oleh-pihak-ke-3/state-chart-diagram/20171018_state-chart-diagram-opd)](http://img.bangunbanten.com/sop/proses-pembuatan-aplikasi-oleh-pihak-ke-3/state-chart-diagram/20171018_state-chart-diagram-opd)
