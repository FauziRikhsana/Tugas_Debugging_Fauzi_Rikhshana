# Tugas_Debugging_
<ul>
  <li>Mata Kuliah:Pemograman Mobile 1 </li>
  <li>Dosen Pengampu: Nova Agustina, ST., M.Kom.</li>
</ul>

## Profil
<ul>
  <li>Nama: Fauzi Rikhshana</li>
  <li>NIM: 23552011030</li>
  <li>Kelas: TIF CNS C</li>
</ul>
## source code 
import android.util.Log
import android.widget.Toast

        val shareEdit: EditText = findViewById(R.id.share_edit_text)
        val shareTextButton: Button = findViewById(R.id.share_text_button)
        shareTextButton.setOnClickListener {
            val shareText = shareEdit.text.toString()
            Log.v("cek string", shareText)
            Toast.makeText(applicationContext, shareText, Toast.LENGTH_SHORT).show()
            shareText(shareText)

<p>
Implementasi tugas ini saya lakukan pada tugas materi implicit dimana pada MainActivity.kt saya tambahkan code diatas dan hasil nya seperti pada gambar di bawah 
</p>
