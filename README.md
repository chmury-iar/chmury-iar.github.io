# chmury-iar.github.io
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privacy Policy - Namida Launcher</title>
    <style>
        :root {
            --bg-color: #1b1b1b;
            --card-bg: #ffffff;
            --text-main: #1e293b;
            --text-muted: #333333;
            --accent: #333333;
            --border-color: #333333;
            --highlight-bg: #eff6ff;
        }

        @media (prefers-color-scheme: dark) {
            :root {
                --bg-color: #0f172a;
                --card-bg: #1e293b;
                --text-main: #f1f5f9;
                --text-muted: #94a3b8;
                --accent: #60a5fa;
                --border-color: #334155;
                --highlight-bg: #1e3a8a33;
            }
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.65;
            padding: 2rem 1rem;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: var(--card-bg);
            padding: 2.5rem 3rem;
            border-radius: 12px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05), 0 2px 4px -2px rgba(0, 0, 0, 0.05);
            border: 1px solid var(--border-color);
        }

        header {
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 1.5rem;
            margin-bottom: 2rem;
        }

        h1 {
            font-size: 1.875rem;
            font-weight: 700;
            letter-spacing: -0.025em;
            margin-bottom: 0.5rem;
        }

        .meta {
            font-size: 0.875rem;
            color: var(--text-muted);
        }

        h2 {
            font-size: 1.25rem;
            font-weight: 600;
            margin-top: 2rem;
            margin-bottom: 0.75rem;
            color: var(--accent);
        }

        h3 {
            font-size: 1.05rem;
            font-weight: 600;
            margin-top: 1.25rem;
            margin-bottom: 0.5rem;
        }

        p {
            margin-bottom: 1rem;
        }

        ul {
            margin-left: 1.5rem;
            margin-bottom: 1rem;
        }

        li {
            margin-bottom: 0.4rem;
        }

        .note {
            background-color: var(--highlight-bg);
            border-left: 4px solid var(--accent);
            padding: 1rem 1.25rem;
            border-radius: 0 8px 8px 0;
            margin: 1.25rem 0;
            font-size: 0.95rem;
        }

        footer {
            margin-top: 3rem;
            padding-top: 1.5rem;
            border-top: 1px solid var(--border-color);
            font-size: 0.875rem;
            color: var(--text-muted);
            text-align: center;
        }

        a {
            color: var(--accent);
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        @media (max-width: 600px) {
            .container {
                padding: 1.5rem;
            }
            h1 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>Privacy Policy for Namida Launcher</h1>
        <p class="meta"><strong>Last updated:</strong> November 19, 2026</p>
    </header>

    <p>This Privacy Policy sets out the rules for processing and protecting the data of users of the <strong>Namida Launcher</strong> mobile application (hereinafter referred to as the "App"), which serves as a home screen (launcher) for Android.</p>

    <h2>1. Data Controller</h2>
    <p>The data controller is the creator of the App: <strong>chmury.iar</strong>, who can be contacted via email at: <a href="mailto:support.namida@gmail.com">support.namida@gmail.com</a>.</p>

    <h2>2. What Data We Collect and Why</h2>
    <p>The App is designed with user privacy in mind. We do not collect, profile, or sell personal data for marketing or analytics purposes.</p>

    <h3>A. Location Data (Weather Widget)</h3>
    <ul>
        <li><strong>Scope of data:</strong> Approximate or precise device location (GPS coordinates / network-based location).</li>
        <li><strong>Purpose of processing:</strong> Solely to display the current weather forecast in the weather widget built into the launcher.</li>
        <li><strong>How data is processed:</strong> The App requests location access only when the user chooses to use weather features. Location data is processed locally on the device and used exclusively to make a weather request — <strong>it is not sent to the Controller, stored in databases, or shared with third parties for tracking purposes.</strong></li>
    </ul>
    <div class="note">
        <strong>Technical note:</strong> Geographic coordinates are transmitted as an anonymous request solely to the weather API provider to retrieve current weather data.
    </div>

    <h3>B. Diagnostic Data and Log Files (Crash / Error Logs)</h3>
    <ul>
        <li><strong>Scope of data:</strong> Technical log files (application system logs), device model information, Android version, and the state of the App when an error occurred.</li>
        <li><strong>Purpose of processing:</strong> Solely to diagnose, analyze, and fix errors reported by the user.</li>
        <li><strong>How data is processed:</strong> The App <strong>does not collect or send error reports automatically</strong>. Sending a log file occurs solely at the user's initiative, after manually selecting the report error option, by sending an email to the Controller.</li>
    </ul>

    <h2>3. System Permissions Required by the App</h2>
    <p>As a launcher application, <strong>Namida Launcher</strong> may require access to certain Android system features (e.g., list of installed applications, displaying widgets, location access for the weather widget, notification access). These permissions are used locally on the device solely to ensure proper operation of the launcher interface.</p>

    <h2>4. Data Retention and Deletion</h2>
    <ul>
        <li><strong>Location:</strong> Location data is not stored by the Controller (it is processed exclusively in the device's active memory in real time).</li>
        <li><strong>Diagnostic data (logs):</strong> Emails containing log files and the technical data included in them are kept by the Controller only for as long as necessary to identify the cause of the error and deploy a fix. <strong>Immediately after the error is detected and fixed, the submitted diagnostic data is permanently deleted.</strong></li>
    </ul>

    <h2>5. Sharing Data with Third Parties</h2>
    <p>The Controller does not sell, rent, or share user data with any third parties, except where required by applicable law.</p>

    <h2>6. Data Security</h2>
    <p>The Controller makes every effort to protect transmitted information against unauthorized access. Because error reports are sent via the email client chosen by the user, we recommend not including sensitive personal data unrelated to the technical issue in the message body.</p>

    <h2>7. User Rights (GDPR)</h2>
    <p>In connection with sending an error report via email, users have the right to:</p>
    <ul>
        <li>access their data and receive a copy of it,</li>
        <li>request rectification or immediate erasure of submitted data (right to be forgotten),</li>
        <li>restrict data processing.</li>
    </ul>
    <p>To exercise these rights, please contact the Controller at: <a href="mailto:[Your Email Address]">[Your Email Address]</a>.</p>

    <h2>8. Changes to This Privacy Policy</h2>
    <p>The Controller reserves the right to make changes to this Privacy Policy (for example, if new features are added to the App). The current version of the document will always be available in the App's listing on Google Play and directly in the App settings.</p>

    <footer>
        &copy; 2026 Namida Launcher. All rights reserved.
    </footer>
</div>

</body>
</html>
