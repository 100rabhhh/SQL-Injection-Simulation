<h1>🛡️ SQL Injection Simulation 🧑‍💻</h1>

<h2>📋 Introduction</h2>
<p>This project demonstrates a <strong>SQL Injection</strong> attack using the <strong>Damn Vulnerable Web Application (DVWA)</strong>. It explores how attackers can exploit vulnerabilities in SQL queries to gain unauthorized access to databases.</p>

<h2>🛠️ Steps & Outputs</h2>
<ol>
    <li><strong>Download & Setup:</strong>
        <ul>
            <li>🖥️ Install <strong>XAMPP</strong> and run <strong>MySQL</strong> and <strong>Apache Server</strong>.</li>
            <li>📦 Download <strong>DVWA</strong> in ZIP form, extract it, and move the folder to <code>C:/xampp/htdocs/</code>.</li>
            <li>🛠️ Rename the <code>config.inc.php</code> file in the <strong>DVWA</strong> folder and set the username to <code>'root'</code> and password to <code>''</code>.</li>
            <li>🌐 Open <code>localhost/DVWA/setup.php</code> in a browser and click <strong>'create/reset DB'</strong>.</li>
        </ul>
    </li>
    <li><strong>Login to DVWA:</strong>
        <ul>
            <li>🔑 Username: <code>admin</code> | Password: <code>password</code></li>
            <li>⚙️ Change <strong>DVWA security level</strong> to <strong>'low'</strong> for testing.</li>
        </ul>
    </li>
    <li><strong>Perform SQL Injection Attacks:</strong>
        <ul>
            <li>🔍 Simulate 5 different <strong>SQL Injection</strong> queries, such as:</li>
            <li><code>' OR 1=1--</code></li>
            <li><code>' UNION SELECT username, password FROM users; --</code></li>
            <li><code>admin' #</code></li>
        </ul>
    </li>
</ol>

<h2>📊 Expected Output</h2>
<p>These SQL injection attempts reveal how weak SQL handling can be exploited to access sensitive database information, demonstrating the need for <strong>prepared statements</strong> and <strong>query parameterization</strong>.</p>

<h2>🧠 Conclusion</h2>
<p>This project highlights the dangers of <strong>SQL Injection</strong> and the importance of implementing <strong>secure coding practices</strong> to safeguard databases from unauthorized access. 🔒</p>
