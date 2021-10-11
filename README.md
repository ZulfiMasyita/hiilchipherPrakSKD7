# hiilchipherPrakSKD7
sebelum import egcd perlu install terlebih dahulu pada prompt agar tidak eror
memasukkan alphabet a sampai z
menuliskan kode program enkripsi dan dekripsi
pada fungsi enkripsi memiliki rumus (message, K) yang mana message adalah kata yang akan dienkripsi sedangkan K adalah key matrix yang digunakan dengan memasukkan angka misalnya K = np.matrix ([[4, 3], [5, 6]]). ini merupakan kunci untuk merubah plaintext menjadi cipher text
sedangkan pada fungsi dekripsi memiliki rumus (encrypted_message, Kinv) yang mana encrypted_message adalah cipher text yang dihasilkan pada enkripsi. sedangkan Kinv adalah rumus untuk merubah cipher text menjadi plain text kembali. rumusnya adalah Kinv = matrix_mod_inv(K, len(alphabet)). ini merupakan kunci untuk mengubah menjadi plaintext kembali.
