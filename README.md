[pool_party_invitation_with_number.html](https://github.com/user-attachments/files/27737890/pool_party_invitation_with_number.html)

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pool Party Invitation</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@300;400;600;700&display=swap');

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: linear-gradient(135deg, #00c6ff 0%, #0072ff 100%);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: 'Poppins', sans-serif;
    padding: 20px;
  }

  .invitation {
    background: rgba(255, 255, 255, 0.95);
    border-radius: 24px;
    max-width: 520px;
    width: 100%;
    padding: 40px 35px;
    text-align: center;
    box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
    position: relative;
    overflow: hidden;
  }

  .invitation::before {
    content: '';
    position: absolute;
    top: -50%;
    left: -50%;
    width: 200%;
    height: 200%;
    background: radial-gradient(circle, rgba(0,198,255,0.08) 0%, transparent 70%);
    animation: float 8s ease-in-out infinite;
  }

  @keyframes float {
    0%, 100% { transform: translate(0, 0); }
    50% { transform: translate(-20px, -20px); }
  }

  .hero-img {
    width: 140px;
    height: 140px;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 10px;
    animation: bounce 2s ease infinite;
    box-shadow: 0 8px 25px rgba(0,0,0,0.15);
    position: relative;
    z-index: 1;
  }

  @keyframes bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-12px); }
  }

  h1 {
    font-family: 'Pacifico', cursive;
    font-size: 42px;
    color: #0072ff;
    margin-bottom: 8px;
    position: relative;
    z-index: 1;
  }

  .subtitle {
    font-size: 18px;
    color: #555;
    margin-bottom: 30px;
    font-weight: 300;
    position: relative;
    z-index: 1;
  }

  .divider {
    width: 60px;
    height: 4px;
    background: linear-gradient(90deg, #00c6ff, #0072ff);
    border-radius: 2px;
    margin: 0 auto 30px;
  }

  .details {
    display: flex;
    flex-direction: column;
    gap: 16px;
    margin-bottom: 35px;
    position: relative;
    z-index: 1;
  }

  .detail-item {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
    font-size: 16px;
    color: #333;
  }

  .detail-icon {
    font-size: 22px;
    width: 36px;
    text-align: center;
  }

  .detail-text {
    font-weight: 600;
    min-width: 240px;
    text-align: left;
  }

  .rsvp {
    background: linear-gradient(135deg, #00c6ff, #0072ff);
    color: white;
    padding: 14px 40px;
    border-radius: 50px;
    font-size: 18px;
    font-weight: 600;
    display: inline-block;
    text-decoration: none;
    box-shadow: 0 8px 25px rgba(0, 114, 255, 0.4);
    transition: transform 0.3s, box-shadow 0.3s;
    position: relative;
    z-index: 1;
    border: none;
    cursor: pointer;
  }

  .rsvp:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 35px rgba(0, 114, 255, 0.5);
  }

  .footer {
    margin-top: 25px;
    font-size: 14px;
    color: #888;
    font-weight: 300;
    position: relative;
    z-index: 1;
  }

  .waves {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 60px;
    opacity: 0.15;
    z-index: 0;
  }

  .wave {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 200%;
    height: 100%;
    background: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1440 320'%3E%3Cpath fill='%2300c6ff' fill-opacity='1' d='M0,192L48,197.3C96,203,192,213,288,229.3C384,245,480,267,576,250.7C672,235,768,181,864,181.3C960,181,1056,235,1152,234.7C1248,235,1344,181,1392,154.7L1440,128L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z'%3E%3C/path%3E%3C/svg%3E") repeat-x;
    background-size: 50% 100%;
    animation: waveMove 6s linear infinite;
  }

  @keyframes waveMove {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }
</style>
</head>
<body>
  <div class="invitation">
    <img src="baby-meme-transparent.png" alt="Pool Party" class="hero-img">
    <h1>Pool Party!</h1>
    <p class="subtitle">House music, good vibes, and cold drinks</p>
    <div class="divider"></div>

    <div class="details">
      <div class="detail-item">
        <span class="detail-icon">📅</span>
        <span class="detail-text">Thursday, May 14, 2026</span>
      </div>
      <div class="detail-item">
        <span class="detail-icon">⏰</span>
        <span class="detail-text">1:00 PM – Late</span>
      </div>
      <div class="detail-item">
        <span class="detail-icon">📍</span>
        <span class="detail-text">3899 Fifth Ave NW, Naples, FL</span>
      </div>
      <div class="detail-item">
        <span class="detail-icon">🎵</span>
        <span class="detail-text">DJ spinning house music all night</span>
      </div>
      <div class="detail-item">
        <span class="detail-icon">🍔</span>
        <span class="detail-text">Food provided</span>
      </div>
      <div class="detail-item">
        <span class="detail-icon">🍻</span>
        <span class="detail-text">BYOB</span>
      </div>
      <div class="detail-item">
        <span class="detail-icon">👙</span>
        <span class="detail-text">Bring a swimsuit & towel</span>
      </div>
    </div>

    <a href="sms:+12396879192" class="rsvp">📱 Text Me</a>
    <p style="margin-top:12px; font-size:15px; color:#0072ff; font-weight:600; position:relative; z-index:1;">(239) 687-9192</p>

    <p class="footer">See you on the dance floor (and in the pool)! 🏖️☀️</p>

    <div class="waves">
      <div class="wave"></div>
    </div>
  </div>
</body>
</html>
