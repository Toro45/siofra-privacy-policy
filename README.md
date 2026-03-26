<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Síofra Keyboard - Privacy Policy</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
        }
        h1 { color: #2c3e50; border-bottom: 2px solid #3498db; padding-bottom: 10px; }
        h2 { color: #34495e; margin-top: 30px; }
        h3 { color: #555; margin-top: 20px; }
        .last-updated { color: #7f8c8d; font-style: italic; margin-bottom: 30px; }
        .highlight { background-color: #fff3cd; padding: 15px; border-left: 4px solid #ffc107; margin: 20px 0; }
        ul { padding-left: 25px; }
        li { margin-bottom: 8px; }
        a { color: #3498db; text-decoration: none; }
        a:hover { text-decoration: underline; }
        .contact-section { background: #f8f9fa; padding: 20px; border-radius: 8px; margin-top: 30px; }
    </style>
</head>
<body>
    <h1>Privacy Policy for Síofra Keyboard</h1>
    <p class="last-updated">Last Updated: February 10, 2026</p>

    <div class="highlight">
        <strong>Privacy-First Design:</strong> Síofra Keyboard is built with your privacy as a top priority. You have complete control over what data is shared, and AI features only work when you explicitly grant consent.
    </div>

    <h2>1. Introduction</h2>
    <p>Síofra Keyboard ("we", "our", or "the app") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our mobile keyboard application.</p>

    <h2>2. Information We Collect</h2>

    <h3>2.1 Text Input Data (With Your Consent)</h3>
    <p>When you enable AI-powered features (text enhancement, translation, auto-response), the app may transmit text to our Síofra LLM service for processing. This includes:</p>
    <ul>
        <li>Text you select for enhancement or translation</li>
        <li>Conversation messages for context-aware auto-response</li>
        <li>Calculator and calendar queries</li>
    </ul>
    <p><strong>Important:</strong> Text input is only transmitted when you explicitly use AI features AND have granted privacy consent. In Privacy Mode, no text is sent to external servers.</p>

    <h3>2.2 Audio Data (Voice Input)</h3>
    <p>If you use the voice input feature, the app requests permission to access your device's microphone (<code>android.permission.RECORD_AUDIO</code>). Audio data is:</p>
    <ul>
        <li>Processed locally on your device when possible</li>
        <li>Only transmitted to speech recognition services when you actively use voice input</li>
        <li>Not stored or recorded by the app</li>
        <li>Deleted immediately after transcription</li>
    </ul>
    <p><strong>You control:</strong> Voice input is optional and can be disabled in Settings. Audio recording only occurs when you press and hold the microphone button.</p>

    <h3>2.3 App Usage Data</h3>
    <p>We may collect anonymous usage statistics to improve the app:</p>
    <ul>
        <li>Feature usage frequency (e.g., how often AI features are used)</li>
        <li>Crash reports and error logs (no personal data included)</li>
        <li>Performance metrics (app speed, battery usage)</li>
        <li>Device type and Android version</li>
    </ul>
    <p>This data is anonymized and cannot be tied to individual users.</p>

    <h3>2.4 Subscription & Billing Data</h3>
    <p>If you purchase a subscription through Google Play, billing information is handled by Google. We receive:</p>
    <ul>
        <li>Your subscription tier (Basic, Premium, Ultimate)</li>
        <li>Purchase verification tokens</li>
        <li>Subscription status (active, expired, canceled)</li>
    </ul>
    <p>We do NOT see or store your credit card information, payment details, or full name.</p>

    <h2>3. How We Use Your Information</h2>
    <p>Information collected is used solely for:</p>
    <ul>
        <li><strong>AI Features:</strong> Processing text for enhancement, translation, and smart replies</li>
        <li><strong>Voice Input:</strong> Converting speech to text for keyboard input</li>
        <li><strong>App Functionality:</strong> Providing calculator, calendar, and toolbox features</li>
        <li><strong>Service Improvement:</strong> Analyzing anonymous usage patterns to enhance user experience</li>
        <li><strong>Subscription Management:</strong> Verifying entitlements and managing feature access</li>
        <li><strong>Bug Fixes:</strong> Diagnosing and resolving technical issues</li>
    </ul>

    <h2>4. Data Sharing & Third Parties</h2>
    
    <h3>4.1 Síofra LLM Service</h3>
    <p>When you use AI features, text is sent to our Síofra LLM service via encrypted HTTPS connections. This service:</p>
    <ul>
        <li>Processes requests in real-time</li>
        <li>Does not store your text after processing (ephemeral processing)</li>
        <li>Uses industry-standard encryption (TLS 1.3)</li>
        <li>Complies with GDPR and data protection regulations</li>
    </ul>

    <h3>4.2 Google Play Services</h3>
    <p>The app integrates with Google Play for:</p>
    <ul>
        <li>Subscription billing and license verification</li>
        <li>Crash reporting through Google Play Console</li>
    </ul>
    <p>Google's privacy policy applies to data processed by Google Play Services: <a href="https://policies.google.com/privacy" target="_blank">https://policies.google.com/privacy</a></p>

    <h3>4.3 No Third-Party Advertising</h3>
    <p>We do NOT share your data with advertisers or sell it to third parties. The app contains no advertising SDKs or tracking pixels.</p>

    <h2>5. Data Security</h2>
    <p>We implement robust security measures to protect your information:</p>
    <ul>
        <li><strong>Encryption in Transit:</strong> All network communications use HTTPS/TLS 1.3</li>
        <li><strong>Encrypted Storage:</strong> User preferences and API keys are stored using Android's EncryptedSharedPreferences</li>
        <li><strong>Certificate Pinning:</strong> Prevents man-in-the-middle attacks on API connections</li>
        <li><strong>No Plaintext Logs:</strong> Sensitive data is never logged to device logs</li>
        <li><strong>Secure Key Storage:</strong> API keys are obfuscated and stored in secure storage</li>
    </ul>

    <h2>6. Data Retention</h2>
    <ul>
        <li><strong>Text Inputs:</strong> Not stored by the app or Síofra LLM service (processed in real-time only)</li>
        <li><strong>Audio Data:</strong> Deleted immediately after transcription</li>
        <li><strong>User Preferences:</strong> Stored on-device until you uninstall the app</li>
        <li><strong>Crash Reports:</strong> Retained for 90 days for debugging purposes</li>
        <li><strong>Subscription Data:</strong> Retained as long as your subscription is active, plus 1 year for billing records</li>
    </ul>

    <h2>7. Your Privacy Rights</h2>
    <p>You have the following rights regarding your data:</p>
    <ul>
        <li><strong>Access:</strong> Request information about data we've collected</li>
        <li><strong>Deletion:</strong> Request deletion of your data (uninstalling removes all local data)</li>
        <li><strong>Opt-Out:</strong> Disable AI features and switch to Privacy Mode at any time</li>
        <li><strong>Revoke Consent:</strong> Withdraw privacy consent in Settings → Privacy & Data</li>
        <li><strong>Data Portability:</strong> Request export of your settings and preferences</li>
    </ul>
    <p>To exercise these rights, contact us at the email below.</p>

    <h2>8. Children's Privacy</h2>
    <p>Síofra Keyboard is not directed to children under 13 years of age. We do not knowingly collect personal information from children. If you believe we have inadvertently collected data from a child, please contact us immediately.</p>

    <h2>9. International Users</h2>
    <p>If you are accessing the app from outside your country, your information may be transferred to and processed in regions with different data protection laws. By using the app, you consent to such transfers in accordance with this Privacy Policy.</p>

    <h2>10. Changes to This Privacy Policy</h2>
    <p>We may update this Privacy Policy from time to time. Changes will be reflected by the "Last Updated" date at the top. Material changes will be communicated through:</p>
    <ul>
        <li>In-app notifications</li>
        <li>Prompts to review the updated policy</li>
        <li>Updates to this webpage</li>
    </ul>
    <p>Continued use of the app after changes indicates acceptance of the updated policy.</p>

    <h2>11. Permissions Explanation</h2>
    <p>The app requests the following Android permissions:</p>
    <ul>
        <li><strong>RECORD_AUDIO:</strong> Required for optional voice input feature. You control when audio is recorded (only when microphone button is pressed).</li>
        <li><strong>INTERNET:</strong> Required for AI features to communicate with Síofra LLM service.</li>
        <li><strong>ACCESS_NETWORK_STATE:</strong> Checks internet connectivity before making API calls.</li>
        <li><strong>VIBRATE:</strong> Provides haptic feedback for key presses (optional, configurable in Settings).</li>
        <li><strong>SET_ALARM:</strong> Allows calendar/reminder toolbox features to integrate with your device's alarm system.</li>
    </ul>

    <div class="contact-section">
        <h2>12. Contact Us</h2>
        <p>If you have questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:</p>
        <p>
            <strong>Email:</strong> <a href="mailto:privacy@siofrakeyboard.com">privacy@siofrakeyboard.com</a><br>
            <strong>App Name:</strong> Síofra Keyboard<br>
            <strong>Developer:</strong> Síofra Development Team<br>
            <strong>Last Updated:</strong> February 10, 2026
        </p>
        <p><strong>Response Time:</strong> We aim to respond to all privacy inquiries within 48 hours.</p>
    </div>

    <hr style="margin: 40px 0; border: none; border-top: 1px solid #ddd;">
    <p style="text-align: center; color: #7f8c8d; font-size: 14px;">
        © 2026 Síofra Keyboard. All rights reserved. | 
        <a href="#top">Back to Top</a>
    </p>
</body>
</html>
