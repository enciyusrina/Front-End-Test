# Front-End-Test 
general test
1.	What does a Doctype do?
Jawab : DOCTYPE adalah suatu deklerasi yang digunakan untuk mengidentifikasi jenis dokumen HTML yang digunakan sehingga browser dapat menentukan bagaimana memperlakukan kode tersebut, pda doctype juga terdapat berbagai macamnya.
2.	What are data- attributes good for?
Jawab: untuk menampilkan teks dan tooltip.
3.	Describe the difference between a cookie, sessionStorage and localStorage?
Jawab :  Cookie adalah serangkaian teks yang disimpan pada komputer Anda oleh situs
   web yang Anda kunjungi.
   localStorage  adalah menyimpan data tanpa tanggal kedaluwarsa
 		   sessionStorage adalah menyimpan data untuk satu sesi
4.	What is the difference between “resetting” and “normalizing” CSS? Which would you choose, and why?
Jawab:  
•	resetting CSS bertujuan menghapus semua gaya browser bawaan. Unsur-unsur standar seperti H1-6, p, strong, em, dan sebagainya akhirnya tampak persis sama, tidak memiliki hiasan sama sekali. Anda seharusnya menambahkan semua dekorasi dirimu sendiri.
•	normalizing  css bertujuan untuk membuat gaya peramban bawaan konsisten di semua browser. Elemen seperti H1-6 akan tampak tebal, lebih besar, dan sebagainya secara konsisten di seluruh browser. Anda seharusnya hanya menambahkan perbedaand alam mendekorasi kebutuhan desain Anda.
•	Yang saya memilih normalisasi css karena untuk mencapai audiens lebih cepat mencapa target audiens nya css pun lebih cepat untuk ditulis.
5.	When would you use document.write()?
Jawab: menggunakan document.write() ketika objek yang mewakili dokumen HTML di dalam Javascript yang berfungsi untuk menulis sesuatu pada document HTML.

slicing 
<!DOCTYPE HTML>
<html>
	<head>
		<title>pendaftaran awr</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />
		<link rel="stylesheet" href="assets/css/main.css" />
	</head>
	<body>
		<!-- One -->
			<section id="one" class="wrapper style1">
				<div class="inner" >
					<article class="feature left" style="background-color:#DEB887; ">
						<span class="image"><img src="assets/images/tablet.png" alt="" /></span>
						<div class="content">
							<H2>STEP 1</h2>
						  <h3>Klik tombol DAFTAR pada halaman Beranda atau Tentang AWR</h3>
						</div>
					</article>
          <article class="feature left" style="background-color:#DEB887;">
            <span class="image"><img src="assets/images/smartphone.png" alt=""/></span>
            <div class="content">
              <h1> STEP 2 </h1>
              <H3>Isi form data diri anda secara lengkap dan benar</H3>
            </div>
          </article>
          <article class="feature left" style="background-color:#FFDEAD;">
            <span class="image"><img src="assets/images/orang.png" alt="" style="margin-left:150px;"/></span>
            <div class="content">
              <h2>Allianz Wotd Run 2018</h2>
              <p>AWR adalah sebuah kegiatan lari yang di lakukan setiap tahun untuk kategori umum dan tahun sekarang merupakan ajang bergensi tersebuat agar masyarakat dapat mengikuti acara tersebut</p>
              <p style="color:blue;"> ->SHOW LESS DETAIL </p>
              <p>1. Lari Maraton <br>
                 2. Lari 500km &nbsp;<br>
                 3. Lari 1000km &nbsp;
              </p>
            </div>
          </article>
				</div>
			</section>
		<!-- Scripts -->
			<script src="assets/js/jquery.min.js"></script>

	</body>
</html>

javascript 
<script type="text/javascript" charset="utf-8">
 document.write("<b>Output</b><br><br>");
	 for (var i=1;i<=5;i++){
		 for(var a=1; a<=i;a++){
			 document.write(i);
			 }
			 document.write("<br>");
	 }
</script>

