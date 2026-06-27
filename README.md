# drpepperenjoyer99-lang.github.io

<!DOCTYPE html>
<html>
<head>
    <title>Redirecting to Settings...</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body { font-family: sans-serif; text-align: center; padding: 50px; }
        .btn { display: inline-block; padding: 12px 24px; background: #007bff; color: white; text-decoration: none; border-radius: 4px; font-weight: bold; }
    </style>
</head>
<body>
    <h2>Opening Ulefone Settings...</h2>
    <p>If the settings app didn't open automatically, click the button below:</p>
    
    <!-- The modified, fully explicit Intent layout -->
    <a id="intentLink" class="btn" href="intent:#Intent;action=android.settings.SETTINGS;package=com.android.settings;end">
        Open Settings Panel
    </a>

    <script>
        window.onload = function() {
            // Force browser engine context execution execution
            var link = document.getElementById('intentLink');
            setTimeout(function() {
                link.click();
            }, 500);
        };
    </script>
</body>
</html>
