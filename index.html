<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sistem Stok Barang</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #ffc0cb 0%, #ffb6c1 50%, #ff69b4 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }
        
        h1 {
            color: #ff1493;
            margin-bottom: 30px;
            text-align: center;
        }
        
        .stok-section {
            background: #fff0f5;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 30px;
        }
        
        .stok-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        
        .stok-header h2 {
            color: #ff1493;
        }
        
        .stok-item {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
            background: white;
            padding: 15px 50px 15px 20px;
            border-radius: 12px;
            box-shadow: 0 2px 8px rgba(255, 105, 180, 0.15);
            position: relative;
        }
        
        .stok-info {
            flex: 1;
        }
        
        .stok-name {
            font-size: 18px;
            font-weight: bold;
            color: #333;
            margin-bottom: 5px;
        }
        
        .stok-jumlah {
            font-size: 24px;
            color: #ff1493;
            font-weight: bold;
        }
        
        .stok-controls {
            display: flex;
            gap: 10px;
        }
        
        .btn-close {
            position: absolute;
            top: 10px;
            right: 10px;
            background: #ff1493;
            color: white;
            border: none;
            width: 28px;
            height: 28px;
            border-radius: 50%;
            cursor: pointer;
            font-size: 20px;
            font-weight: bold;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s;
            padding: 0;
            line-height: 1;
        }
        
        .btn-close:hover {
            background: #c71585;
            transform: scale(1.15);
        }
        
        button {
            padding: 10px 20px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s;
        }
        
        .btn-edit {
            background: #ffb6c1;
            color: white;
        }
        
        .btn-edit:hover {
            background: #ff69b4;
        }
        
        .btn-ambil {
            background: #ff69b4;
            color: white;
        }
        
        .btn-ambil:hover {
            background: #ff1493;
        }
        
        .btn-tambah {
            background: #ff69b4;
            color: white;
        }
        
        .btn-tambah:hover {
            background: #ff1493;
        }
        
        .btn-simpan {
            background: #ff69b4;
            color: white;
        }
        
        .btn-simpan:hover {
            background: #ff1493;
        }
        
        .btn-batal {
            background: #6c757d;
            color: white;
        }
        
        .btn-batal:hover {
            background: #5a6268;
        }
        
        .btn-hapus {
            background: #dc3545;
            color: white;
            padding: 5px 10px;
            font-size: 12px;
        }
        
        .btn-hapus:hover {
            background: #c82333;
        }
        
        input[type="number"] {
            padding: 8px;
            border: 2px solid #ffb6c1;
            border-radius: 6px;
            width: 100px;
            font-size: 16px;
        }
        
        input[type="text"] {
            padding: 8px;
            border: 2px solid #ffb6c1;
            border-radius: 6px;
            width: 100%;
            font-size: 16px;
        }
        
        input:focus {
            outline: none;
            border-color: #ff69b4;
        }
        
        select {
            padding: 8px;
            border: 2px solid #ffb6c1;
            border-radius: 6px;
            font-size: 16px;
            cursor: pointer;
        }
        
        select:focus {
            outline: none;
            border-color: #ff69b4;
        }
        
        .modal {
            display: none;
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.5);
        }
        
        .modal-content {
            background: white;
            margin: 10% auto;
            padding: 30px;
            border-radius: 15px;
            width: 90%;
            max-width: 400px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
        }
        
        .modal h2 {
            color: #ff1493;
            margin-bottom: 20px;
        }
        
        .form-group {
            margin-bottom: 15px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            color: #333;
        }
        
        .form-actions {
            display: flex;
            gap: 10px;
            margin-top: 20px;
        }
        
        .form-actions button {
            flex: 1;
        }
        
        .riwayat-section {
            background: #fff0f5;
            padding: 20px;
            border-radius: 10px;
        }
        
        .riwayat-section h2 {
            color: #ff1493;
            margin-bottom: 15px;
        }
        
        .riwayat-item {
            background: white;
            padding: 15px;
            border-radius: 12px;
            margin-bottom: 10px;
            box-shadow: 0 2px 8px rgba(255, 105, 180, 0.15);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .riwayat-info {
            flex: 1;
        }
        
        .riwayat-waktu {
            font-size: 12px;
            color: #6c757d;
            margin-top: 5px;
        }
        
        .empty-state {
            text-align: center;
            color: #6c757d;
            padding: 20px;
        }
        
        .tabs {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
        }
        
        .tab-button {
            flex: 1;
            padding: 12px;
            background: white;
            color: #ff1493;
            border: 2px solid #ffb6c1;
            border-radius: 8px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .tab-button:hover {
            background: #fff0f5;
        }
        
        .tab-button.active {
            background: #ff69b4;
            color: white;
            border-color: #ff69b4;
        }
        
        .tab-content {
            display: none;
        }
        
        .tab-content.active {
            display: block;
        }
        
        .total-cabang {
            background: linear-gradient(135deg, #ff69b4 0%, #ff1493 100%);
            color: white;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 15px;
            text-align: center;
            font-size: 18px;
            font-weight: bold;
        }
        
        .harga-info {
            font-size: 14px;
            color: #ff69b4;
            margin-top: 3px;
        }
    </style>
    
    <!-- Firebase SDK -->
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-app-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-database-compat.js"></script>
</head>
<body>
    <div class="container">
        <h1>📦 Sistem Stok Barang</h1>
        
        <div class="stok-section">
            <div class="stok-header">
                <h2>Stok Tersedia</h2>
                <button class="btn-tambah" onclick="bukaModalTambah()">+ Tambah Barang Baru</button>
            </div>
            <div id="stokList"></div>
        </div>
        
        <div class="riwayat-section">
            <h2>Riwayat Pengambilan Stok</h2>
            <div class="tabs">
                <button class="tab-button active" onclick="gantiTab('cabang1')">Cabang 1</button>
                <button class="tab-button" onclick="gantiTab('cabang2')">Cabang 2</button>
            </div>
            <div id="riwayatCabang1" class="tab-content active"></div>
            <div id="riwayatCabang2" class="tab-content"></div>
        </div>
    </div>
    
    <!-- Modal Edit Stok -->
    <div id="modalEdit" class="modal">
        <div class="modal-content">
            <h2>Edit Stok</h2>
            <div class="form-group">
                <label>Jumlah Stok Baru:</label>
                <input type="number" id="inputEditStok" min="0">
            </div>
            <div class="form-actions">
                <button class="btn-simpan" onclick="simpanEdit()">Simpan</button>
                <button class="btn-batal" onclick="tutupModal('modalEdit')">Batal</button>
            </div>
        </div>
    </div>
    
    <!-- Modal Ambil Stok -->
    <div id="modalAmbil" class="modal">
        <div class="modal-content">
            <h2>Ambil Stok</h2>
            <div class="form-group">
                <label>Jumlah yang Diambil:</label>
                <input type="number" id="inputAmbilStok" min="1">
            </div>
            <div class="form-group">
                <label>Pilih Cabang:</label>
                <select id="selectCabang">
                    <option value="Cabang 1">Cabang 1</option>
                    <option value="Cabang 2">Cabang 2</option>
                </select>
            </div>
            <div class="form-actions">
                <button class="btn-simpan" onclick="konfirmasiAmbil()">Ambil</button>
                <button class="btn-batal" onclick="tutupModal('modalAmbil')">Batal</button>
            </div>
        </div>
    </div>
    
    <!-- Modal Tambah Barang -->
    <div id="modalTambah" class="modal">
        <div class="modal-content">
            <h2>Tambah Barang Baru</h2>
            <div class="form-group">
                <label>Nama Barang:</label>
                <input type="text" id="inputNamaBarang" placeholder="Contoh: Bakso, Dumpling Ayam">
            </div>
            <div class="form-group">
                <label>Jumlah Stok:</label>
                <input type="number" id="inputStokAwal" min="0" value="0">
            </div>
            <div class="form-group">
                <label>Harga per Pcs:</label>
                <input type="number" id="inputHargaBarang" min="0" value="0" placeholder="Contoh: 5000">
            </div>
            <div class="form-actions">
                <button class="btn-simpan" onclick="tambahBarang()">Tambah</button>
                <button class="btn-batal" onclick="tutupModal('modalTambah')">Batal</button>
            </div>
        </div>
    </div>
    
    <script>
        // Konfigurasi Firebase
        const firebaseConfig = {
            apiKey: "AIzaSyAbCuzBbqp6uS_B36UEZqZRkw4cZA3GI1Q",
            authDomain: "chizathrift.firebaseapp.com",
            projectId: "chizathrift",
            storageBucket: "chizathrift.appspot.com",
            messagingSenderId: "45254081746",
            appId: "1:45254081746:web:5a51d8a4690d93d513810b",
            databaseURL: "https://chizathrift-default-rtdb.asia-southeast1.firebasedatabase.app/"
        };
        
        // Initialize Firebase
        firebase.initializeApp(firebaseConfig);
        const database = firebase.database();
        
        let stokBarang = {};
        let riwayatCabang1 = [];
        let riwayatCabang2 = [];
        let tabAktif = 'cabang1';
        let itemYangDiedit = null;
        let itemYangDiambil = null;
        
        // Fungsi untuk load data dari Firebase
        function loadData() {
            // Load stok barang
            database.ref('stok-barang').on('value', (snapshot) => {
                const data = snapshot.val();
                if (data) {
                    stokBarang = data;
                } else {
                    // Data default jika belum ada
                    stokBarang = {
                        "Dumpling Keju": { stok: 10, harga: 5000 }
                    };
                    saveStokBarang();
                }
                tampilkanStok();
            });
            
            // Load riwayat cabang 1
            database.ref('riwayat-cabang1').on('value', (snapshot) => {
                const data = snapshot.val();
                riwayatCabang1 = data ? data : [];
                tampilkanRiwayat();
            });
            
            // Load riwayat cabang 2
            database.ref('riwayat-cabang2').on('value', (snapshot) => {
                const data = snapshot.val();
                riwayatCabang2 = data ? data : [];
                tampilkanRiwayat();
            });
        }
        
        // Fungsi untuk save stok barang ke Firebase
        function saveStokBarang() {
            database.ref('stok-barang').set(stokBarang)
                .catch((error) => {
                    console.error('Gagal menyimpan stok:', error);
                    alert('Gagal menyimpan data. Coba lagi.');
                });
        }
        
        // Fungsi untuk save riwayat ke Firebase
        function saveRiwayat() {
            database.ref('riwayat-cabang1').set(riwayatCabang1)
                .catch((error) => {
                    console.error('Gagal menyimpan riwayat cabang 1:', error);
                });
            
            database.ref('riwayat-cabang2').set(riwayatCabang2)
                .catch((error) => {
                    console.error('Gagal menyimpan riwayat cabang 2:', error);
                });
        }
        
        function tampilkanStok() {
            const stokList = document.getElementById('stokList');
            stokList.innerHTML = '';
            
            for (let [nama, data] of Object.entries(stokBarang)) {
                const div = document.createElement('div');
                div.className = 'stok-item';
                div.innerHTML = `
                    <div class="stok-info">
                        <div class="stok-name">${nama}</div>
                        <div class="stok-jumlah">Stok: ${data.stok}</div>
                        <div class="harga-info">Harga: Rp ${data.harga.toLocaleString('id-ID')}/pcs</div>
                    </div>
                    <div class="stok-controls">
                        <button class="btn-edit" onclick="bukaModalEdit('${nama}')">Edit</button>
                        <button class="btn-ambil" onclick="bukaModalAmbil('${nama}')">Ambil</button>
                    </div>
                    <button class="btn-close" onclick="hapusBarang('${nama}')">×</button>
                `;
                stokList.appendChild(div);
            }
        }
        
        function tampilkanRiwayat() {
            tampilkanRiwayatCabang('cabang1', riwayatCabang1, 'riwayatCabang1');
            tampilkanRiwayatCabang('cabang2', riwayatCabang2, 'riwayatCabang2');
        }
        
        function tampilkanRiwayatCabang(cabang, riwayat, elementId) {
            const riwayatList = document.getElementById(elementId);
            
            if (riwayat.length === 0) {
                riwayatList.innerHTML = '<div class="empty-state">Belum ada riwayat pengambilan stok</div>';
                return;
            }
            
            let totalHarga = 0;
            riwayat.forEach(item => {
                totalHarga += item.totalHarga;
            });
            
            let html = `<div class="total-cabang">Total Nilai Barang: Rp ${totalHarga.toLocaleString('id-ID')}</div>`;
            
            riwayat.forEach((item, index) => {
                html += `
                    <div class="riwayat-item">
                        <div class="riwayat-info">
                            <strong>${item.nama}</strong> - ${item.jumlah} pcs × Rp ${item.harga.toLocaleString('id-ID')} = <strong>Rp ${item.totalHarga.toLocaleString('id-ID')}</strong>
                            <div class="riwayat-waktu">${item.waktu}</div>
                        </div>
                        <button class="btn-hapus" onclick="hapusRiwayat('${cabang}', ${index})">Hapus</button>
                    </div>
                `;
            });
            
            riwayatList.innerHTML = html;
        }
        
        function gantiTab(tab) {
            tabAktif = tab;
            
            document.querySelectorAll('.tab-button').forEach(btn => {
                btn.classList.remove('active');
            });
            document.querySelectorAll('.tab-content').forEach(content => {
                content.classList.remove('active');
            });
            
            if (tab === 'cabang1') {
                document.querySelectorAll('.tab-button')[0].classList.add('active');
                document.getElementById('riwayatCabang1').classList.add('active');
            } else {
                document.querySelectorAll('.tab-button')[1].classList.add('active');
                document.getElementById('riwayatCabang2').classList.add('active');
            }
        }
        
        function bukaModalEdit(nama) {
            itemYangDiedit = nama;
            document.getElementById('inputEditStok').value = stokBarang[nama].stok;
            document.getElementById('modalEdit').style.display = 'block';
        }
        
        function bukaModalTambah() {
            document.getElementById('inputNamaBarang').value = '';
            document.getElementById('inputStokAwal').value = 0;
            document.getElementById('inputHargaBarang').value = 0;
            document.getElementById('modalTambah').style.display = 'block';
        }
        
        function tambahBarang() {
            const namaBarang = document.getElementById('inputNamaBarang').value.trim();
            const stokAwal = parseInt(document.getElementById('inputStokAwal').value);
            const hargaBarang = parseInt(document.getElementById('inputHargaBarang').value);
            
            if (namaBarang === '') {
                alert('Nama barang tidak boleh kosong!');
                return;
            }
            
            if (stokBarang.hasOwnProperty(namaBarang)) {
                alert('Barang dengan nama ini sudah ada!');
                return;
            }
            
            if (stokAwal < 0) {
                alert('Jumlah stok tidak boleh negatif!');
                return;
            }
            
            if (hargaBarang < 0) {
                alert('Harga tidak boleh negatif!');
                return;
            }
            
            stokBarang[namaBarang] = {
                stok: stokAwal,
                harga: hargaBarang
            };
            saveStokBarang();
            tutupModal('modalTambah');
        }
        
        function simpanEdit() {
            const jumlahBaru = parseInt(document.getElementById('inputEditStok').value);
            
            if (jumlahBaru >= 0) {
                stokBarang[itemYangDiedit].stok = jumlahBaru;
                saveStokBarang();
                tutupModal('modalEdit');
            } else {
                alert('Jumlah stok tidak boleh negatif!');
            }
        }
        
        function bukaModalAmbil(nama) {
            itemYangDiambil = nama;
            document.getElementById('inputAmbilStok').value = 1;
            document.getElementById('inputAmbilStok').max = stokBarang[nama].stok;
            document.getElementById('modalAmbil').style.display = 'block';
        }
        
        function konfirmasiAmbil() {
            const jumlahAmbil = parseInt(document.getElementById('inputAmbilStok').value);
            const cabang = document.getElementById('selectCabang').value;
            
            if (jumlahAmbil > stokBarang[itemYangDiambil].stok) {
                alert('Jumlah yang diambil melebihi stok yang tersedia!');
                return;
            }
            
            if (jumlahAmbil <= 0) {
                alert('Jumlah yang diambil harus lebih dari 0!');
                return;
            }
            
            const hargaSatuan = stokBarang[itemYangDiambil].harga;
            const totalHarga = jumlahAmbil * hargaSatuan;
            
            stokBarang[itemYangDiambil].stok -= jumlahAmbil;
            
            const waktu = new Date().toLocaleString('id-ID', {
                day: '2-digit',
                month: '2-digit',
                year: 'numeric',
                hour: '2-digit',
                minute: '2-digit'
            });
            
            const riwayatItem = {
                nama: itemYangDiambil,
                jumlah: jumlahAmbil,
                harga: hargaSatuan,
                totalHarga: totalHarga,
                waktu: waktu
            };
            
            if (cabang === 'Cabang 1') {
                riwayatCabang1.unshift(riwayatItem);
            } else {
                riwayatCabang2.unshift(riwayatItem);
            }
            
            saveStokBarang();
            saveRiwayat();
            tutupModal('modalAmbil');
        }
        
        function hapusRiwayat(cabang, index) {
            if (confirm('Apakah Anda yakin ingin menghapus riwayat ini?')) {
                if (cabang === 'cabang1') {
                    riwayatCabang1.splice(index, 1);
                } else {
                    riwayatCabang2.splice(index, 1);
                }
                saveRiwayat();
            }
        }
        
        function hapusBarang(nama) {
            if (confirm(`Apakah Anda yakin ingin menghapus barang "${nama}"?\n\nSemua data stok dan harga akan dihapus permanen.`)) {
                delete stokBarang[nama];
                saveStokBarang();
            }
        }
        
        function tutupModal(modalId) {
            document.getElementById(modalId).style.display = 'none';
        }
        
        window.onclick = function(event) {
            if (event.target.classList.contains('modal')) {
                event.target.style.display = 'none';
            }
        }
        
        // Load data saat halaman pertama kali dibuka
        loadData();
    </script>
</body>
</html>
