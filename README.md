<h1><img src="https://gpvc.arturio.dev/user-bot"></h1>

<h1>user-bot-documentation</h1>
<p>This is documentation for installation user-bot</p>

<h1>Documentation</h1>
<h2>Starting</h2>
<p>Let's go to the site <a href="https://my.telegram.org"><em>my.telegram.org</em></a></p>
<p>You need to login following the picture below to get api-id and api-hash and edit <code>config.toml</code> file.</p>
<p><img src="./img/login.png"></p>
<p>After receiving api-id and api-hash start editing the <code>config.toml</code> file and change the value variables <code>api_id</code> and <code>api_hash</code>.</p>
<p>Now everything, run the <code>main.py</code> file.</p>
<p>Next, we will be asked to enter a phone number. Enter your phone number as shown below.</p>
<p><img src="./img/enter_phone.png"></p>
<p>After entering the phone number, we can go to Telegram and start using the bot.</p>
<p>I recommend entering commands before using the bot <code>.help</code></p>

<h2>Modules</h2>
<p>If you are a programmer and want to write a module for a user bot then follow the rules below:</p>
<p><strong>1. The module file must be in the folder "<code>modules</code>".</strong></p>
<p><strong>3. Module class name must end with "<code>Module</code>".</strong></p>
<p><strong>4. Be sure to inherit the class "<code>TGCLIENT</code>" imported from folder "<code>tgclient.py</code>" which is located in the root directory user bot.</strong></p>
<p><strong>5. You can optionally write documentation for the class (optional).</strong></p>
<p><strong>6. The main user bot code should be in the function "<code>start</code>".</strong></p>
<p>Before writing a module, I recommend looking at already written modules in the code.</>
