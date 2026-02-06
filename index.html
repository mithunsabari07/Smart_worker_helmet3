<!DOCTYPE html>
<html>
<head>
  <title>Smart Safety Helmet Dashboard</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body { font-family: Arial; background:#f4f6f8; padding:20px; }
    .card {
      background:white; padding:15px; margin-bottom:15px;
      border-radius:10px; box-shadow:0 0 10px rgba(0,0,0,0.1);
    }
    .danger { background:#ffcccc; }
    .safe { background:#ccffcc; }
    h2 { margin-top:0; }
  </style>
</head>
<body>

<h2>🪖 Smart Safety Helmet – Live Dashboard</h2>

<div id="statusCard" class="card safe">
  <h3>Status: <span id="status">Loading...</span></h3>
</div>

<div class="card">🌡 Temperature: <b id="temp">--</b> °C</div>
<div class="card">☁ Gas Level: <b id="gas">--</b></div>
<div class="card">❤️ Heart Rate: <b id="heart">--</b> BPM</div>
<div class="card">⏱ Last Updated: <b id="time">--</b></div>

<!-- Firebase -->
<script type="module">
import { initializeApp } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-app.js";
import { getFirestore, doc, onSnapshot } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js";

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
};

const app = initializeApp(firebaseConfig);
const db = getFirestore(app);

const helmetRef = doc(db, "helmet", "live");

onSnapshot(helmetRef, (docSnap) => {
  if (docSnap.exists()) {
    const d = docSnap.data();

    document.getElementById("temp").innerText = d.temperature;
    document.getElementById("gas").innerText = d.gas;
    document.getElementById("heart").innerText = d.heartRate;
    document.getElementById("status").innerText = d.status;
    document.getElementById("time").innerText =
      new Date(d.lastUpdated.seconds * 1000).toLocaleTimeString();

    const card = document.getElementById("statusCard");
    card.className = "card " + (d.status === "DANGER" ? "danger" : "safe");
  }
});
</script>

</body>
</html>
