<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <header>
        <h1>Fireblocks Bug Bounty Vulnerability Report</h1>
    </header>
    <section>
        <h2>Summary</h2>
        <p>
            This report details a security vulnerability within the Fireblocks application that allows for unencrypted connections, posing a risk of traffic interception and modification by attackers. The application's lack of enforced HTTPS connections means that SSL/TLS encryption can be bypassed, potentially leading to exploitation via rewritten HTTPS links as HTTP. 
        </p>
    </section>
    <footer>
        <p>Report prepared by: Jordan</p>
        <p>Date: 2024-03-06 - 2024-03-06</p>
    </footer>
</body>
</html>
