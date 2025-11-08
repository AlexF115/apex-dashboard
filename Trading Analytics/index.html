<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Trade Dashboard</title>
<link href="https://fonts.googleapis.com/css?family=Montserrat:600,400&display=swap" rel="stylesheet" />
<script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
<style>
  :root {
    --bg-primary: #111217;
    --bg-secondary: #181924;
    --bg-card: #20212a;
    --text-primary: #f4f6fb;
    --accent-gold: #FFD25F;
    --accent-gold-bold: #ffc900;
    --profit-green: #21cf91;
    --loss-red: #ef4444;
    --border-color: #232432;
    --shadow: 0 5px 40px #000b;
  }
  body {
    background: var(--bg-primary);
    color: var(--text-primary);
    font-family: 'Montserrat', sans-serif;
    margin: 0;
    min-height: 100vh;
  }
  .top-bar {
    width: 100vw;
    display: flex;
    justify-content: flex-end;
    align-items: center;
    padding: 18px 52px 0 0;
    position: relative;
    z-index: 5;
    min-height: 22px;
  }
  .login-btn {
    background: #191b27;
    color: var(--accent-gold-bold);
    border: none;
    font-size: 1.09em;
    font-weight: 700;
    letter-spacing: .9px;
    padding: 8px 34px 8px 18px;
    border-radius: 16px 7px 7px 16px;
    box-shadow: 0 2px 12px #0008;
    cursor: pointer;
    transition: background .14s, box-shadow .15s;
    margin-right: 6px;
  }
  .login-btn:hover {
    background: #232434;
    filter: brightness(1.09);
    box-shadow: 0 2px 18px #ffc90955;
  }
  .logo-centered {
    display: flex;
    justify-content: center;
    margin-top: 18px;
    margin-bottom: 24px;
  }
  .logo-centered img {
    max-width: 88px; max-height: 88px;
    border-radius: 17px; background: #000; box-shadow: 0 2px 28px #000b;
  }
  .row-main {
    display: flex;
    gap: 36px;
    justify-content: center;
    align-items: stretch;
    margin: 0 auto 30px auto;
    max-width: 1080px;
    min-height: 350px;
  }
  .card-even {
    flex: 1 1 355px;
    min-width: 295px;
    max-width: 470px;
    background: var(--bg-card);
    border-radius: 20px;
    box-shadow: var(--shadow);
    padding: 30px 26px 32px 26px;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
  }

  /* Add trade form block styling */
  .trade-form {
    display: flex;
    flex-direction: column;
    gap: 8px;
  }
  .trade-form label {
    color: var(--accent-gold);
    font-weight: 700;
    margin-top: 8px;
    margin-bottom: 0;
  }
  .trade-form input,
  .trade-form select {
    width: 100%;
    background: var(--bg-secondary);
    border: 1.5px solid var(--border-color);
    color: var(--text-primary);
    border-radius: 6px;
    padding: 9px 10px;
    margin-top: 2px;
    font-size: 1em;
  }
  .add-trade-btn {
    margin-top: 17px;
    width: 100%;
    padding: 13px 0;
    border: none;
    border-radius: 10px;
    background: linear-gradient(87deg, var(--accent-gold-bold), #ff9500 85%);
    font-weight: 700;
    font-size: 1.08em;
    color: var(--bg-secondary);
    cursor: pointer;
    box-shadow: 0 2px 10px #ffc90033;
    letter-spacing: 0.03em;
    transition: filter 0.13s;
  }
  .add-trade-btn:hover { filter: brightness(1.07);}
  #resetDataBtn {
    display:block;
    margin:12px 0 0 0;
    background:#181b24;
    color:#FFC94A; border:none; padding:11px 0;
    font-size:1.07em; border-radius:9px;
    box-shadow:0 2px 8px #0008; cursor:pointer;
    transition: background .15s;
    width: 100%;
  }
  #resetDataBtn:hover { background: #222531; }
  .summary-bar-main {
    margin-bottom: 14px;
    padding-bottom: 12px;
    border-bottom: 1.3px solid #2324322b;
    width: 100%;
  }
  .summary-bar-main div {
    color: var(--accent-gold);
    font-weight:600;
    font-size:1.15em;
    margin: 7px 0 4px 1px;
    letter-spacing: .6px;
    text-shadow: 0 1px 3px #0004;
  }
  .summary-bar-main strong { color: var(--profit-green);}
  .summary-bar-main .losses { color: var(--loss-red);}
  .chart-col {
    width: 100%;
    min-height: 120px;
    margin-top: 6px;
    padding-top: 12px;
    border-top: 1px solid #2222;
    margin-bottom: 3px;
  }
  .trade-table-container {
    width: 100%;
    max-width: 990px;
    margin: 0 auto 19px auto;
    background: var(--bg-card); border-radius: 15px;
    box-shadow: 0 2px 15px #000A;
    padding: 18px 9px 19px 9px;
    display: flex; flex-direction: column; align-items: center;
  }
  table {
    width: 100%; border-collapse: collapse;
    background: none; color: var(--text-primary);
    border-radius: 11px;
    font-size: 1.0em;
    box-shadow: 0 0px 0px #0000;
  }
  th, td { padding: 11px 12px; border-bottom: 1px solid var(--border-color); text-align: center; }
  th { color: var(--accent-gold-bold); font-size:1.07em;}
  .profit { color: var(--profit-green); font-weight: 600; }
  .loss { color: var(--loss-red); font-weight: 600; }
  .thumbnail { max-width: 36px; max-height: 28px; cursor: pointer; border-radius: 6px; border: 2px solid var(--border-color);}
  .thumbnail:hover { border-color: var(--accent-gold-bold); }
  .hidden { display: none!important; }
  .modal {
    position: fixed;
    display: none; top:0; bottom:0; left:0; right:0;
    background: rgba(18,17,27,0.93);
    justify-content: center; align-items: center; z-index: 1000;
  }
  .modal.active { display: flex; }
  #loginForm {
    background: var(--bg-card); box-shadow: 0 2px 17px #0009;
    padding: 29px 33px 29px 33px; border-radius: 14px;
    display: flex; flex-direction: column; align-items: center;
    min-width: 250px;
  }
  #loginForm label { color: var(--accent-gold-bold); font-size: 1.09em; margin-bottom: 18px; font-weight: 800;}
  #loginForm input[type="password"] {
    width:180px; margin-bottom: 13px; padding: 11px; border-radius: 7px;
    font-size: 1.01em; background: var(--bg-secondary); color: var(--text-primary);
    border: 1px solid var(--border-color); outline: none;
  }
  #loginForm button {
    font-size: 1.03em; margin-top: 7px;
    background: linear-gradient(93deg, var(--accent-gold-bold), #ff9500 90%);
    color: var(--bg-secondary); border-radius: 9px; border: none;
    padding: 10px 29px; font-weight: 700; cursor: pointer; box-shadow: 0 2px 8px #ffc90044;
    transition: filter .13s;
  }
  #loginForm button:hover { filter: brightness(1.07);}
  .modal img { max-width: 91vw; max-height: 91vh; border-radius: 10px; box-shadow: 0 0 18px #000; }
  .main-center {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    margin-bottom: 34px;
    width: 100vw;
  }
  .card-viewer {
    width: 420px;
    max-width: 94vw;
    background: var(--bg-card);
    border-radius: 20px;
    box-shadow: var(--shadow);
    padding: 30px 26px 32px 26px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    min-height: 360px;
  }
</style>
</head>
<body>
<div class="top-bar">
  <button id="loginUnlockBtn" class="login-btn">Login</button>
</div>
<div class="logo-centered"><img src="apex-logo.jpeg" alt="Apex Crypto Club logo"></div>

<!-- Dashboard: ONLY show after login -->
<div class="row-main" id="rowMain" style="display:none;">
  <div class="card-even" id="inputCard">
    <form id="tradeForm" class="trade-form" autocomplete="off">
      <label for="symbol">Symbol</label>
      <input type="text" id="symbol" placeholder="BTCUSD" required />
      <label for="positionType">Position Type</label>
      <select id="positionType" required>
        <option value="Long">Long</option>
        <option value="Short">Short</option>
      </select>
      <label for="entryPrice">Entry Price</label>
      <input type="number" id="entryPrice" required step="any" />
      <label for="exitPrice">Exit Price</label>
      <input type="number" id="exitPrice" required step="any" />
      <label for="positionSize">Position Size (% of balance)</label>
      <input type="number" id="positionSize" min="0" max="100" step="0.01" required />
      <label for="leverage">Leverage (e.g., 75, 100)</label>
      <input type="number" id="leverage" min="1" max="1000" value="1" required />
      <label for="proofUpload">Upload Proof Image</label>
      <input type="file" id="proofUpload" accept="image/*" />
      <button type="submit" class="add-trade-btn">Add Trade</button>
      <button id="resetDataBtn" type="button">Reset All Data</button>
    </form>
  </div>
  <div class="card-even" id="analyticsCard">
    <div class="summary-bar-main">
      <div>Current Balance: <strong id="currentBalance">US$10,000.00</strong></div>
      <div>Trades Taken: <span id="totalTrades">0</span></div>
      <div>Wins/Losses: <span id="wins">0</span> / <span id="losses">0</span></div>
      <div>Win Rate: <span id="winRate">0.00%</span></div>
      <div>Total PnL: <span id="totalPnl">US$0.00</span></div>
    </div>
    <div class="chart-col">
      <canvas id="equityCurveChart" height="120"></canvas>
    </div>
  </div>
</div>

<!-- VIEWER: show if NOT logged in -->
<div class="main-center" id="viewOnlyArea">
  <div class="card-viewer">
    <div class="summary-bar-main">
      <div>Current Balance: <strong id="currentBalanceView">US$10,000.00</strong></div>
      <div>Trades Taken: <span id="totalTradesView">0</span></div>
      <div>Wins/Losses: <span id="winsView">0</span> / <span id="lossesView">0</span></div>
      <div>Win Rate: <span id="winRateView">0.00%</span></div>
      <div>Total PnL: <span id="totalPnlView">US$0.00</span></div>
    </div>
    <div class="chart-col">
      <canvas id="equityCurveChartView" height="120"></canvas>
    </div>
  </div>
</div>

<div class="trade-table-container" id="tradeTableContainer">
  <table>
    <thead>
      <tr>
        <th>Symbol</th><th>Position</th><th>Entry Price</th><th>Exit Price</th>
        <th>Leverage</th><th>Position %</th><th>Exposure (USD)</th>
        <th>Profit / Loss</th><th>Proof</th>
      </tr>
    </thead>
    <tbody id="tradeTableBody"></tbody>
  </table>
</div>

<!-- Login Modal -->
<div id="loginModal" class="modal">
  <form id="loginForm">
    <label for="password">Login</label>
    <input type="password" id="password" placeholder="Password" autocomplete="off" />
    <button type="submit">Login</button>
    <p id="loginError" style="color: var(--loss-red); margin-top: 9px; font-weight:600; visibility:hidden">Incorrect password</p>
  </form>
</div>

<div id="imageModal" class="modal"><img id="imageModalContent" alt="Proof image large preview" /></div>
<script>
  const PASSWORD = "apex115";
  let trades = JSON.parse(localStorage.getItem("trades")) || [];
  let currentBalance = 10000;
  let isLoggedIn = false;

  function fmtNum(n, decimals=2) {
    return Number(n).toLocaleString(undefined, {minimumFractionDigits: decimals, maximumFractionDigits: decimals});
  }
  function formatSymbol(input) {
    input = input.trim().toUpperCase();
    input = input.replace(/\//g,"");
    if (input.endsWith("USDT")) input = input.slice(0, -4);
    if (input.endsWith("USD")) input = input.slice(0, -3);
    return input + "/USD";
  }

  function renderViewOnly() {
    let curBal = 10000, equityArr = [10000], bal = 10000, wins = 0, losses = 0;
    trades.forEach(trade => {
      const positionSizeUsd = (trade.positionSizePercent / 100) * bal * trade.leverage;
      const pnl = (trade.exitPrice - trade.entryPrice) * positionSizeUsd * (trade.positionType === "Long" ? 1 : -1) / trade.entryPrice;
      bal += pnl;
      equityArr.push(bal);
      if (pnl > 0) wins++; else if (pnl < 0) losses++;
    });
    document.getElementById("currentBalanceView").textContent = `US$${fmtNum(bal)}`;
    document.getElementById("totalTradesView").textContent = trades.length;
    document.getElementById("winsView").textContent = wins;
    document.getElementById("lossesView").textContent = losses;
    document.getElementById("winRateView").textContent = trades.length ? ((wins / trades.length) * 100).toFixed(2) + '%' : '0.00%';
    document.getElementById("totalPnlView").textContent = `US$${fmtNum(bal-10000)}`;
    // Chart:
    const ctx = document.getElementById("equityCurveChartView").getContext("2d");
    if (window.viewerEquityCurveObj) window.viewerEquityCurveObj.destroy();
    window.viewerEquityCurveObj = new Chart(ctx, {
      type: "line",
      data: {
        labels: equityArr.map((_, i) => i === 0 ? "Start" : `Trade ${i}`),
        datasets: [{
          label: "",
          data: equityArr,
          tension: 0.38,
          borderWidth: 2.2,
          borderColor: "#FFC94A",
          backgroundColor: "rgba(255, 201, 74, 0.14)",
          pointRadius: 0,
          fill: true,
          clip: 8
        }]
      },
      options: {
        responsive: true,
        plugins: { legend: { display: false }},
        scales: {
          y: {
            beginAtZero: false,
            grid: { color: "rgba(255,210,95,0.09)" },
            ticks: { color: "#ffc900", font: { family: 'Montserrat', size: 11.5 }}
          },
          x: {
            grid: { display: false },
            ticks: { color: "#5f6170", font: { family: 'Montserrat', size: 11.2 }}
          }
        }
      }
    });
  }

  function renderAnalytics() {
    document.getElementById("rowMain").style.display = isLoggedIn ? "flex" : "none";
    document.getElementById("viewOnlyArea").style.display = !isLoggedIn ? "flex" : "none";
    if (isLoggedIn) {
      renderSummary();
      renderEquityCurve();
    } else {
      renderViewOnly();
    }
    renderTradeTable();
  }

  // Login logic
  document.getElementById("loginUnlockBtn").onclick = function() {
    document.getElementById("loginModal").classList.add("active");
    document.getElementById("loginError").style.visibility = "hidden";
  };

  document.getElementById("loginForm").addEventListener("submit", function(e){
    e.preventDefault();
    const pwd = document.getElementById("password").value.trim();
    if (pwd === PASSWORD) {
      isLoggedIn = true;
      document.getElementById("loginModal").classList.remove("active");
      renderAnalytics();
    } else {
      document.getElementById("loginError").style.visibility = "visible";
    }
    document.getElementById("loginForm").reset();
  });

  function finalizeTrade(trade) {
    trade.symbol = formatSymbol(trade.symbol);
    trades.push(trade);
    updateBalanceFromTrades();
    renderAnalytics();
    document.getElementById("tradeForm").reset();
  }

  document.getElementById("tradeForm").addEventListener("submit", (e) => {
    e.preventDefault();
    if (!isLoggedIn) {
      document.getElementById("loginModal").classList.add("active");
      return;
    }
    const newTrade = {
      symbol: document.getElementById("symbol").value.trim(),
      positionType: document.getElementById("positionType").value,
      entryPrice: parseFloat(document.getElementById("entryPrice").value),
      exitPrice: parseFloat(document.getElementById("exitPrice").value),
      positionSizePercent: parseFloat(document.getElementById("positionSize").value),
      leverage: parseInt(document.getElementById("leverage").value),
      date: new Date().toISOString(),
    };
    const proofInput = document.getElementById("proofUpload");
    if (proofInput.files.length > 0) {
      const file = proofInput.files[0];
      const reader = new FileReader();
      reader.onload = function(ev) {
        newTrade.proof = ev.target.result;
        finalizeTrade(newTrade);
      };
      reader.readAsDataURL(file);
    } else {
      finalizeTrade(newTrade);
    }
  });

  document.getElementById("resetDataBtn").onclick = function() {
    if (!isLoggedIn) {
      document.getElementById("loginModal").classList.add("active");
      return;
    }
    if(confirm('Are you sure you want to reset all trade data? This cannot be undone.')) {
      localStorage.removeItem("trades");
      trades = [];
      updateBalanceFromTrades();
      renderAnalytics();
    }
  };

  // Render table and analytics
  function renderSummary() {
    document.getElementById("currentBalance").textContent = `US$${fmtNum(currentBalance)}`;
    document.getElementById("totalTrades").textContent = trades.length;
    const wins = trades.filter((t) => t.pnl > 0).length;
    const losses = trades.length - wins;
    document.getElementById("wins").textContent = wins;
    document.getElementById("losses").textContent = losses;
    const winRate = trades.length ? ((wins / trades.length) * 100).toFixed(2) : 0;
    document.getElementById("winRate").textContent = `${winRate}%`;
    const totalPnl = trades.reduce((acc, t) => acc + t.pnl, 0);
    document.getElementById("totalPnl").textContent = `US$${fmtNum(totalPnl)}`;
  }
  function updateBalanceFromTrades() {
    currentBalance = 10000;
    for (let i = 0; i < trades.length; i++) {
      const trade = trades[i];
      const positionSizeUsd = (trade.positionSizePercent / 100) * currentBalance * trade.leverage;
      const pnl = (trade.exitPrice - trade.entryPrice) * positionSizeUsd * (trade.positionType === "Long" ? 1 : -1) / trade.entryPrice;
      currentBalance += pnl;
      trades[i].pnl = pnl;
      trades[i].positionSizeUsd = positionSizeUsd;
    }
    saveTrades();
  }
  function saveTrades() {
    localStorage.setItem("trades", JSON.stringify(trades));
  }
  function renderTradeTable() {
    const tbody = document.getElementById("tradeTableBody");
    tbody.innerHTML = "";
    trades.forEach((trade, i) => {
      const tr = document.createElement("tr");
      const proofTd = document.createElement("td");
      if (trade.proof) {
        const img = document.createElement("img");
        img.src = trade.proof;
        img.alt = "Proof Image";
        img.className = "thumbnail";
        img.tabIndex = 0;
        img.setAttribute("role", "button");
        img.setAttribute("aria-label", "Open proof image");
        img.addEventListener("click", () => { openModal(trade.proof); });
        proofTd.appendChild(img);
      }
      tr.innerHTML =
        `<td>${trade.symbol}</td>
        <td>${trade.positionType}</td>
        <td>${fmtNum(trade.entryPrice)}</td>
        <td>${fmtNum(trade.exitPrice)}</td>
        <td>${trade.leverage}x</td>
        <td>${fmtNum(trade.positionSizePercent, 2)}%</td>
        <td>US$${fmtNum(trade.positionSizeUsd)}</td>
        <td class="${trade.pnl >= 0 ? 'profit' : 'loss'}">US$${fmtNum(trade.pnl)}</td>`;
      tr.appendChild(proofTd);
      tbody.appendChild(tr);
    });
  }

  function renderEquityCurve() {
    const ctx = document.getElementById("equityCurveChart").getContext("2d");
    let equityArray = [10000];
    let balance = 10000;
    trades.forEach(trade => {
      const positionSizeUsd =
        (trade.positionSizePercent / 100) * balance * trade.leverage;
      const pnl = (trade.exitPrice - trade.entryPrice) * positionSizeUsd *
        (trade.positionType === "Long" ? 1 : -1) / trade.entryPrice;
      balance += pnl;
      equityArray.push(balance);
    });
    if (window.equityCurveChartObj) window.equityCurveChartObj.destroy();
    window.equityCurveChartObj = new Chart(ctx, {
      type: "line",
      data: {
        labels: equityArray.map((_, i) => i === 0 ? "Start" : `Trade ${i}`),
        datasets: [{
          label: "",
          data: equityArray,
          tension: 0.38,
          borderWidth: 2.2,
          borderColor: "#FFC94A",
          backgroundColor: "rgba(255, 201, 74, 0.14)",
          pointRadius: 0,
          fill: true,
          clip: 8
        }]
      },
      options: {
        responsive: true,
        plugins: { legend: { display: false }},
        scales: {
          y: {
            beginAtZero: false,
            grid: { color: "rgba(255,210,95,0.09)" },
            ticks: { color: "#ffc900", font: { family: 'Montserrat', size: 11.5 }}
          },
          x: {
            grid: { display: false },
            ticks: { color: "#5f6170", font: { family: 'Montserrat', size: 11.2 }}
          }
        }
      }
    });
  }
  function openModal(imgSrc) {
    document.getElementById("imageModalContent").src = imgSrc;
    document.getElementById("imageModal").classList.add("active");
  }
  document.getElementById("imageModal").addEventListener("click", function(){
    this.classList.remove("active");
  });

  window.onload = () => {
    isLoggedIn = false;
    renderAnalytics();
  }
</script>
</body>
</html>
