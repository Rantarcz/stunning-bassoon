<!doctype html>
<html lang="cs">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Farmař — Kontakt pro Tap to Pay</title>
  <style>
    body { font-family: system-ui, -apple-system, "Segoe UI", Roboto, sans-serif; margin:0; padding:0;
           display:flex; align-items:center; justify-content:center; min-height:100vh; background:#f6f6f6; }
    .card { background:white; padding:24px; border-radius:12px; box-shadow:0 6px 20px rgba(0,0,0,0.08); width:min(720px,95%); }
    h1{ margin:0 0 8px; font-size:22px; }
    p{ margin:6px 0; color:#333; }
    .big{ font-weight:700; font-size:18px; }
    .btn{ display:inline-block; margin-top:12px; padding:10px 14px; border-radius:8px; text-decoration:none;
          background:#2b7cff; color:white; font-weight:600; }
    footer{ margin-top:14px; color:#666; font-size:13px; }
    .logo{ width:60px; height:60px; border-radius:8px; background:#e6f2ff; display:inline-flex;
           align-items:center; justify-content:center; font-weight:700; color:#1565d8; margin-right:12px; }
    .row{ display:flex; align-items:center; }
  </style>
</head>
<body>
  <div class="card">
    <div class="row">
      <div class="logo">F</div>
      <div>
        <h1>Farmař — Registrace pro Tap to Pay</h1>
        <p class="big">Kontakt k provozovateli: <span id="owner">Farmař</span></p>
      </div>
    </div>

    <p><strong>Adresa:</strong> (doplň) — např. Tvůj statek</p>
    <p><strong>Telefon:</strong> +420 777 000 000 (doplň)</p>
    <p><strong>Email:</strong> info@tvoje-farma.cz (doplň)</p>

    <p>Popis: Tato stránka slouží pro ověření provozovny při registraci služby Tap to Pay. Provozovatel přijímá platby kartou u zákazníků přímo na místě.</p>

    <a class="btn" href="mailto:info@tvoje-farma.cz?subject=Registrace%20Tap%20to%20Pay">Kontaktovat přes e-mail</a>

    <footer>Soukromí: žádné citlivé údaje tu nejsou. Jen kontaktní informace pro registraci.</footer>
  </div>
</body>
</html>
