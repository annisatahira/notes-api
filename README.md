The `api\notes`

Plugin notes ini akan bertanggung jawab untuk menangani setiap permintaan yang mengarah ke url /notes.

The `services\inMemory`

untuk mengelola resource notes yang disimpan pada memory (array).
Pengelolaan resource bisa seperti menyimpan, membaca, mengubah, dan menghapus catatan. Pada implementasi di bawah ini, kita akan membuat:

- method addNote untuk menyimpan;
- method getNotes untuk mendaftar;
- getNoteById untuk membaca;
- method editNoteById untuk mengubah;
- dan method deleteNoteById untuk menghapus catatan.

(`Service akan fokus dalam menangani operasi CRUD pada resource, sedangkan handler akan fokus dalam menangani response pada client.`)
