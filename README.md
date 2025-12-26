# porsche-customer.github.io
<!DOCTYPE html>
<html>
<head>
    <title>Porsche Bug Bounty - Subdomain Takeover PoC</title>
    <style>
        body { font-family: Arial; padding: 40px; }
        h1 { color: #d5001c; }
    </style>
</head>
<body>
    <h1>Subdomain Takeover Proof of Concept</h1>
    <p><strong>Vulnerability:</strong> api.porsche.com points to GitHub Pages but the repository doesn't exist</p>
    <p><strong>Impact:</strong> An attacker can host malicious content on Porsche's subdomain</p>
    <p><strong>PoC by:</strong> luci_lfer12</p>
    <p><strong>Potential attacks:</strong></p>
    <ul>
        <li>Phishing pages</li>
        <li>Stealing cookies via XSS</li>
        <li>Hosting malware</li>
        <li>Damaging brand reputation</li>
    </ul>
</body>
</html>
