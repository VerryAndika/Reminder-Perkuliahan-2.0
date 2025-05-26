<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jadwal Kuliah</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      min-height: 100vh;
      padding: 20px;
      color: #333;
      line-height: 1.6;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
      background: rgba(255, 255, 255, 0.95);
      backdrop-filter: blur(10px);
      border-radius: 20px;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
      overflow: hidden;
    }

    .header {
      background: linear-gradient(135deg, #4f46e5, #7c3aed);
      color: white;
      text-align: center;
      padding: 2rem;
      position: relative;
    }

    .header h1 {
      font-size: 1.8rem;
      font-weight: 300;
      letter-spacing: 1px;
    }

    .admin-btn {
      position: absolute;
      top: 1rem;
      right: 1rem;
      background: rgba(255, 255, 255, 0.2);
      color: white;
      border: 1px solid rgba(255, 255, 255, 0.3);
      padding: 0.5rem 1rem;
      border-radius: 8px;
      text-decoration: none;
      font-size: 0.9rem;
      transition: all 0.3s ease;
    }

    .admin-btn:hover {
      background: rgba(255, 255, 255, 0.3);
      transform: translateY(-1px);
    }

    .schedule-section {
      padding: 2rem;
    }

    .schedule-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      background: linear-gradient(135deg, #f8fafc, #e2e8f0);
      padding: 1.5rem;
      border-radius: 15px;
      margin-bottom: 2rem;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
    }

    .nav-btn {
      background: #4f46e5;
      color: white;
      border: none;
      width: 40px;
      height: 40px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      transition: all 0.3s ease;
      font-size: 1.2rem;
    }

    .nav-btn:hover {
      background: #3730a3;
      transform: scale(1.1);
    }

    .date-title {
      font-size: 1.2rem;
      font-weight: 600;
      color: #374151;
      text-align: center;
      flex: 1;
    }

    .schedule-content {
      min-height: 200px;
    }

    .schedule-item {
      background: #fff;
      border: 1px solid #e5e7eb;
      border-radius: 15px;
      padding: 1.5rem;
      margin-bottom: 1rem;
      transition: all 0.3s ease;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
    }

    .schedule-item:hover {
      transform: translateY(-2px);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
    }

    .schedule-item:last-child {
      margin-bottom: 0;
    }

    .course-name {
      font-size: 1.1rem;
      font-weight: 600;
      color: #4f46e5;
      margin-bottom: 0.8rem;
    }

    .schedule-details {
      display: grid;
      gap: 0.5rem;
    }

    .schedule-detail {
      display: flex;
      align-items: center;
      font-size: 0.9rem;
      color: #6b7280;
    }

    .detail-label {
      font-weight: 500;
      min-width: 80px;
      color: #374151;
    }

    .no-schedule {
      text-align: center;
      color: #9ca3af;
      font-style: italic;
      padding: 3rem;
      font-size: 1.1rem;
    }

    .today-indicator {
      display: inline-block;
      background: #10b981;
      color: white;
      font-size: 0.7rem;
      padding: 0.2rem 0.5rem;
      border-radius: 10px;
      margin-left: 0.5rem;
      font-weight: 500;
    }

    .quick-nav {
      display: flex;
      justify-content: center;
      gap: 0.5rem;
      margin-bottom: 1.5rem;
      flex-wrap: wrap;
    }

    .quick-nav-btn {
      background: #f8fafc;
      border: 1px solid #e2e8f0;
      color: #374151;
      padding: 0.5rem 1rem;
      border-radius: 8px;
      cursor: pointer;
      transition: all 0.3s ease;
      font-size: 0.9rem;
    }

    .quick-nav-btn:hover {
      background: #4f46e5;
      color: white;
    }

    .quick-nav-btn.active {
      background: #4f46e5;
      color: white;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .container {
        margin: 10px;
        border-radius: 15px;
      }

      .header {
        padding: 1.5rem;
      }

      .header h1 {
        font-size: 1.5rem;
      }

      .admin-btn {
        position: static;
        margin-top: 1rem;
      }

      .schedule-section {
        padding: 1.5rem;
      }

      .schedule-header {
        flex-direction: column;
        gap: 1rem;
        text-align: center;
      }

      .nav-btn {
        width: 35px;
        height: 35px;
      }

      .date-title {
        font-size: 1rem;
      }

      .schedule-item {
        padding: 1rem;
      }

      .quick-nav {
        justify-content: stretch;
      }

      .quick-nav-btn {
        flex: 1;
        text-align: center;
      }
    }

    @media (max-width: 480px) {
      body {
        padding: 10px;
      }

      .header h1 {
        font-size: 1.3rem;
      }

      .schedule-section {
        padding: 1rem;
      }

      .schedule-header {
        padding: 1rem;
      }
    }

    /* Animation */
    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .schedule-item {
      animation: fadeIn 0.5s ease-out;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <h1>Jadwal Kuliah</h1>
      <a href="#" class="admin-btn" onclick="bukaAdmin()">Admin</a>
    </div>

    <div class="schedule-section">
      <div class="quick-nav">
        <button class="quick-nav-btn" onclick="navigateToToday()">Hari Ini</button>
        <button class="quick-nav-btn" onclick="navigateToTomorrow()">Besok</button>
        <button class="quick-nav-btn" onclick="navigateToWeek()">Minggu Ini</button>
      </div>

      <div class="schedule-header">
        <button class="nav-btn" onclick="ubahHari(-1)">‹</button>
        <div class="date-title" id="judulTanggal"></div>
        <button class="nav-btn" onclick="ubahHari(1)">›</button>
      </div>
      <div class="schedule-content" id="jadwalHariIni"></div>
    </div>
  </div>

  <script>
    // Sample data - in real implementation, this would come from localStorage or API
    let jadwalData = {
      '2025-05-26': [
        {
          matkul: 'Algoritma dan Pemrograman',
          jam: 'A – C [07:30 - 10:30]',
          dosen: 'Dr. phil. Dessy Seri Wahyuni, S.Kom., M.Eng.',
          ruangan: 'FTK.F.3.06.L - Lab Komputer TI 1 JD',
          mode: 'Luring',
          ket: 'Praktikum'
        },
        {
          matkul: 'Sistem Informasi',
          jam: 'G – H [13:30 - 15:30]',
          dosen: 'I Gede Bendesa Subawa, S.Pd., M.Kom.',
          ruangan: 'FTK.G.2.05 - Ruang Kuliah TPRL JD',
          mode: 'Luring',
          ket: ''
        }
      ],
      '2025-05-27': [
        {
          matkul: 'Basis Data',
          jam: 'B – D [08:30 - 11:30]',
          dosen: 'I Gusti Ayu Agung Diatri Indrawati, S.Kom., M.T.',
          ruangan: 'FTK.F.3.08.L - Lab Komputer TI 3 JD',
          mode: 'Luring',
          ket: 'Lab Session'
        }
      ]
    };

    let currentDate = new Date();

    function formatDate(date) {
      const yyyy = date.getFullYear();
      const mm = String(date.getMonth() + 1).padStart(2, '0');
      const dd = String(date.getDate()).padStart(2, '0');
      return `${yyyy}-${mm}-${dd}`;
    }

    function getHariTanggal(tanggalStr) {
      const hariList = ["Minggu", "Senin", "Selasa", "Rabu", "Kamis", "Jumat", "Sabtu"];
      const now = new Date();
      const besok = new Date(now);
      besok.setDate(now.getDate() + 1);
      const d = new Date(tanggalStr);
      const hari = hariList[d.getDay()];
      const tgl = `${String(d.getDate()).padStart(2, '0')}-${String(d.getMonth()+1).padStart(2,'0')}-${d.getFullYear()}`;

      let indicator = '';
      if (formatDate(now) === tanggalStr) {
        indicator = '<span class="today-indicator">HARI INI</span>';
        return `${hari}, ${tgl} ${indicator}`;
      }
      if (formatDate(besok) === tanggalStr) {
        indicator = '<span class="today-indicator">BESOK</span>';
        return `${hari}, ${tgl} ${indicator}`;
      }
      return `${hari}, ${tgl}`;
    }

    function tampilkanJadwal(tanggalStr) {
      const container = document.getElementById('jadwalHariIni');
      const header = document.getElementById('judulTanggal');
      header.innerHTML = getHariTanggal(tanggalStr);
      container.innerHTML = "";

      // Load data from localStorage if available
      const savedData = localStorage.getItem('jadwalKuliah');
      if (savedData) {
        jadwalData = JSON.parse(savedData);
      }

      const data = jadwalData[tanggalStr];
      if (!data || data.length === 0) {
        container.innerHTML = '<div class="no-schedule">Tidak ada jadwal kuliah</div>';
        return;
      }

      data.forEach((item) => {
        const div = document.createElement('div');
        div.className = "schedule-item";
        
        let detailsHtml = '';
        if (item.jam !== "Tidak Ditampilkan") {
          detailsHtml += `<div class="schedule-detail"><span class="detail-label">Waktu:</span> ${item.jam}</div>`;
        }
        detailsHtml += `<div class="schedule-detail"><span class="detail-label">Dosen:</span> ${item.dosen}</div>`;
        if (item.ruangan && item.ruangan !== "Tidak Ditampilkan") {
          detailsHtml += `<div class="schedule-detail"><span class="detail-label">Ruangan:</span> ${item.ruangan}</div>`;
        }
        if (item.mode) {
          detailsHtml += `<div class="schedule-detail"><span class="detail-label">Mode:</span> ${item.mode}</div>`;
        }
        if (item.ket) {
          detailsHtml += `<div class="schedule-detail"><span class="detail-label">Ket:</span> ${item.ket}</div>`;
        }

        div.innerHTML = `
          <div class="course-name">${item.matkul}</div>
          <div class="schedule-details">${detailsHtml}</div>
        `;
        container.appendChild(div);
      });
    }

    function ubahHari(offset) {
      currentDate.setDate(currentDate.getDate() + offset);
      const newTanggal = formatDate(currentDate);
      tampilkanJadwal(newTanggal);
    }

    function navigateToToday() {
      currentDate = new Date();
      const tanggalStr = formatDate(currentDate);
      tampilkanJadwal(tanggalStr);
    }

    function navigateToTomorrow() {
      currentDate = new Date();
      currentDate.setDate(currentDate.getDate() + 1);
      const tanggalStr = formatDate(currentDate);
      tampilkanJadwal(tanggalStr);
    }

    function navigateToWeek() {
      // Navigate to start of current week (Monday)
      const today = new Date();
      const dayOfWeek = today.getDay();
      const daysToMonday = dayOfWeek === 0 ? -6 : 1 - dayOfWeek;
      currentDate = new Date(today);
      currentDate.setDate(today.getDate() + daysToMonday);
      const tanggalStr = formatDate(currentDate);
      tampilkanJadwal(tanggalStr);
    }

    function bukaAdmin() {
      // In a real application, this would navigate to admin page
      // For demo purposes, we'll show an alert
      if (confirm('Buka halaman admin? (Dalam implementasi nyata, ini akan membuka halaman terpisah)')) {
        // This would normally be: window.location.href = 'admin.html';
        alert('Halaman admin akan dibuka di tab/window baru');
      }
    }

    // Auto-refresh every minute to update "today" indicators
    setInterval(() => {
      const currentTanggalStr = formatDate(currentDate);
      tampilkanJadwal(currentTanggalStr);
    }, 60000);

    window.onload = () => {
      const tanggalStr = formatDate(currentDate);
      tampilkanJadwal(tanggalStr);
    };
  </script>
</body>
</html>
