<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarah Lund - Liminal Hell Observer Log</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Caveat:wght@400;700&family=Inter:wght@400;600&display=swap');
        
        :root {
            --wiki-bg: #050505;
            --wiki-bg1: #0a0a0a;
            --wiki-text: #d1d1d1;
            --wiki-text1: #a0a0a0;
            --wiki-accent: #e61a1a;
            --wiki-accent1: #8b0000;
            --wiki-border: #331111;
            --wiki-glow: rgba(230, 26, 26, 0.4);
            --wiki-redacted: #000000;
        }
        
        body {
            background: var(--wiki-bg);
            color: var(--wiki-text);
            font-family: 'Inter', sans-serif;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        .wiki-page4-wiki-page-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .wiki-page-header-fragment {
            grid-column: 1 / -1;
            text-align: center;
            border: 2px solid var(--wiki-accent);
            background: linear-gradient(135deg, var(--wiki-bg1) 0%, #1a0a0a 100%);
            padding: 40px;
            position: relative;
        }

        .wiki-page4-wiki-page-title {
            font-size: 32px;
            color: var(--wiki-accent);
            text-transform: uppercase;
            letter-spacing: 3px;
            text-shadow: 0 0 10px var(--wiki-glow);
        }

        /* THE REDACTED HOVER EFFECT */
        .thq-wiki-page-redacted-elm {
            background: var(--wiki-redacted);
            color: transparent;
            padding: 2px 8px;
            cursor: help;
            transition: all 0.5s ease;
        }

        .thq-wiki-page-redacted-elm:hover {
            background: transparent;
            color: var(--wiki-accent);
        }

        /* THE NEW BUTTONS */
        .button-container {
            margin-top: 30px;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .wiki-button {
            display: inline-block;
            padding: 12px 30px;
            border: 1px solid var(--wiki-accent);
            color: var(--wiki-accent);
            text-decoration: none;
            text-transform: uppercase;
            font-weight: bold;
            letter-spacing: 2px;
            background: rgba(230, 26, 26, 0.05);
            transition: all 0.3s ease;
        }

        .wiki-button:hover {
            background: var(--wiki-accent);
            color: white;
            box-shadow: 0 0 15px var(--wiki-glow);
            transform: translateY(-2px);
        }

        /* GRID CARDS */
        .wiki-card {
            background: var(--wiki-bg1);
            border: 1px solid var(--wiki-border);
            padding: 20px;
        }

        .wiki-page-handwriting {
            font-family: 'Caveat', cursive;
            font-size: 20px;
            color: var(--wiki-text);
        }
    </style>
</head>
<body>

    <div class="wiki-page4-wiki-page-grid">
        <!-- HEADER BOX -->
        <div class="wiki-page-header-fragment">
            <h2 class="wiki-page4-wiki-page-title">SUBJECT: LUND, SARAH</h2>
            <p style="margin-top: 10px; color: var(--wiki-text1);">
                STATUS: <span class="thq-wiki-page-redacted-elm">OBSERVED</span>
            </p>

            <!-- BUTTONS ADDED HERE -->
            <div class="button-container">
                <a href="#" class="wiki-button">Access Logs</a>
                <a href="#" class="wiki-button">View Files</a>
            </div>
        </div>

        <!-- ADDITIONAL GRID CARDS -->
        <div class="wiki-card">
            <p class="wiki-page-handwriting">Note: Subject appears to be moving between layers. Initial contact was... [REDACTED].</p>
        </div>
        <div class="wiki-card">
            <p class="wiki-page-handwriting">The eyes. Don't look at the eyes in the corridor.</p>
        </div>
    </div>

</body>
</html>
