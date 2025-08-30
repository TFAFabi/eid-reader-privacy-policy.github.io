<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover" />
  <meta name="theme-color" content="#ffffff" />
  <title>Privacy Policy · eID Reader</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #5b68ff;
      --on-primary: #ffffff;
      --bg: #ffffff;
      --surface: #ffffff;
      --text: #1f1f1f;
      --subtle: #5f6368;
      --border: #e9eef3;
      --radius: 16px;
      --shadow: 0 1px 2px rgba(16, 24, 40, .04), 0 8px 28px rgba(16, 24, 40, .08);
      --shadow-soft: 0 1px 2px rgba(16, 24, 40, .03), 0 4px 16px rgba(16, 24, 40, .06);
    }

    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0;
      font-family: Roboto, system-ui, -apple-system, Segoe UI, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
      color: var(--text);
      background: var(--bg);
      line-height: 1.65;
      -webkit-font-smoothing: antialiased;
      text-rendering: optimizeLegibility;
      color-scheme: light;
    }

    .container { max-width: 720px; margin: 12px auto 96px; padding: 0 16px; }
    .hero { display: grid; gap: 6px; margin: 8px 0 10px; }
    .title { font-size: clamp(24px, 6vw, 36px); line-height: 1.15; margin: 0; }
    .subtitle { color: var(--subtle); margin: 0; font-size: clamp(14px, 3.8vw, 16px); }
    .meta { color: var(--subtle); font-size: 13px; margin-top: 6px; }

    details.card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      box-shadow: var(--shadow-soft);
      margin: 12px 0;
      overflow: hidden;
    }
    details[open].card { box-shadow: var(--shadow); }
    summary {
      list-style: none; cursor: pointer;
      display: flex; align-items: center; justify-content: space-between;
      gap: 12px; padding: 14px 16px;
      font-weight: 600; font-size: 16px;
    }
    summary::-webkit-details-marker { display:none; }
    .chev { transition: transform .2s ease; }
    details[open] .chev { transform: rotate(180deg); }
    .content { padding: 0 16px 14px; font-size: 15px; }
    .content ul { margin: 8px 0 0 18px; }

    a { color: var(--primary); text-decoration: none; }
    a:hover { text-decoration: underline; }

    footer { text-align: center; color: var(--subtle); padding: 24px 16px 40px; }

    @media (prefers-reduced-motion: reduce) {
      * { animation: none !important; transition: none !important; }
    }
  </style>
</head>
<body>
  <main class="container">
    <div class="hero">
      <h1 class="title">Privacy Policy</h1>
      <p class="subtitle">Privacy by design. Clear, simple, on-device.</p>
      <div class="meta">Last updated: <time id="updated">[Insert Date]</time></div>
    </div>

    <details class="card" open>
      <summary>
        1. Data We Collect
        <svg class="chev" width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 15.5l-6-6h12l-6 6z" fill="currentColor"/></svg>
      </summary>
      <div class="content">
        <ul>
          <li><strong>Electronic ID Data</strong>: The app reads personal information from electronic IDs.</li>
          <li><strong>In‑App Purchases (IAP)</strong>: Only data strictly necessary to process and verify purchases.</li>
          <li><strong>Advertising</strong>: Third‑party ad providers may collect device identifiers and ad interaction data for ad delivery.</li>
        </ul>
        <p>We do <strong>not</strong> collect, store, or process your electronic ID data in the cloud. All data read from the ID remains <strong>solely on your device</strong>.</p>
      </div>
    </details>

    <details class="card">
      <summary>
        2. Data Storage & Processing
        <svg class="chev" width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 15.5l-6-6h12l-6 6z" fill="currentColor"/></svg>
      </summary>
      <div class="content">
        <ul>
          <li><strong>On‑Device Only</strong>: Electronic ID data is stored and processed locally on your device.</li>
          <li><strong>No Cloud Storage</strong>: We do not transfer or store ID data on our servers.</li>
        </ul>
      </div>
    </details>

    <details class="card">
      <summary>
        3. Use of APIs
        <svg class="chev" width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 15.5l-6-6h12l-6 6z" fill="currentColor"/></svg>
      </summary>
      <div class="content">
        <ul>
          <li><strong>User Choice</strong>: If data is transmitted to an API, that API is chosen and configured by you.</li>
          <li><strong>Disclaimer</strong>: TFA Studios, TFA Games, HEX Instruments, and their affiliates assume no responsibility for data once sent to an external API.</li>
        </ul>
      </div>
    </details>

    <details class="card">
      <summary>
        4. Ads and Third‑Party Services
        <svg class="chev" width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 15.5l-6-6h12l-6 6z" fill="currentColor"/></svg>
      </summary>
      <div class="content">
        <p>The app may use third‑party advertising networks. These providers may collect limited technical data (e.g., device model, IP address, ad interactions) in compliance with GDPR, but <strong>never your ID data</strong>.</p>
      </div>
    </details>

    <details class="card">
      <summary>
        5. Legal Basis for Processing (GDPR)
        <svg class="chev" width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 15.5l-6-6h12l-6 6z" fill="currentColor"/></svg>
      </summary>
      <div class="content">
        <p>Under the GDPR, we rely on the following legal bases for processing:</p>
        <ul>
          <li><strong>Consent</strong>: By using the app, you consent to the handling of data as described in this policy.</li>
          <li><strong>Legitimate Interest</strong>: To ensure IAP functionality and deliver ads.</li>
        </ul>
      </div>
    </details>

    <details class="card">
      <summary>
        6. Your Rights (GDPR)
        <svg class="chev" width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 15.5l-6-6h12l-6 6z" fill="currentColor"/></svg>
      </summary>
      <div class="content">
        <p>As a user in the European Union, you have the right to:</p>
        <ul>
          <li>Access the personal data processed on your device.</li>
          <li>Request deletion of app data stored locally on your device.</li>
          <li>Withdraw consent by uninstalling the app.</li>
          <li>Contact us regarding any privacy concerns.</li>
        </ul>
      </div>
    </details>

    <details class="card">
      <summary>
        7. Liability Disclaimer
        <svg class="chev" width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 15.5l-6-6h12l-6 6z" fill="currentColor"/></svg>
      </summary>
      <div class="content">
        <p>We do not accept liability for any consequences of your data being transmitted to third‑party APIs or services you configure. Once the data leaves your device, its handling is subject to that third party’s policies.</p>
      </div>
    </details>

    <details class="card">
      <summary>
        8. Changes to This Policy
        <svg class="chev" width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 15.5l-6-6h12l-6 6z" fill="currentColor"/></svg>
      </summary>
      <div class="content">
        <p>We may update this Privacy Policy from time to time. Continued use of the app after changes means you accept the revised policy.</p>
      </div>
    </details>

    <details class="card">
      <summary>
        9. Contact
        <svg class="chev" width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden="true"><path d="M12 15.5l-6-6h12l-6 6z" fill="currentColor"/></svg>
      </summary>
      <div class="content">
        <p>For privacy questions, contact <a href="mailto:fabian.tipa@gmail.com">fabian.tipa@gmail.com</a>.</p>
      </div>
    </details>
  </main>

  <footer>
    &copy; 2025 TFA Studios · TFA Games · HEX Instruments
  </footer>

  <script>
    (function(){
      var el = document.getElementById('updated');
      if(el && /Insert Date/i.test(el.textContent)){
        var d = new Date();
        el.textContent = d.toLocaleDateString(undefined, {year:'numeric', month:'short', day:'2-digit'});
      }
    })();
  </script>
</body>
</html>
