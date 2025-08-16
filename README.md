# 🚀 custom_mc_launcher
Minecraft Auto-Mod Updater & Launcher  

<hr/>

<h2>💡 What is this project?</h2>  
<p>
This project provides a <b>custom Minecraft launcher and host system</b> that makes playing modded servers hassle-free.  
Normally, the vanilla Minecraft client doesn’t check or update mods automatically — meaning players have to manually download, unzip, and install mod packs.  
</p>

<p>
With this launcher:  
<ul>
  <li><b>Host</b> runs a lightweight server (<code>mchost.exe</code>) to share the correct set of mods.</li>
  <li><b>Client</b> (<code>client.exe</code>) automatically downloads and updates mods before launching Minecraft.</li>
  <li>Players never need to manually manage <code>.zip</code> files or drag mods into the <code>mods/</code> folder again.</li>
</ul>
</p>

<hr/>

<h2>✨ Features</h2>  
<ul>
  <li>🔄 <b>Automatic Mod Syncing</b> – ensures players always have the exact same mods as the host.</li>
  <li>📦 <b>One-Click Launcher</b> – the client updates mods and starts Minecraft automatically.</li>
  <li>💨 <b>Fast File Streaming</b> – optimized chunked transfer system, handles even large mod packs efficiently.</li>
  <li>🔐 <b>No More Mismatched Mods</b> – avoids “missing mod” or “wrong version” errors.</li>
  <li>⚡ <b>Simple Setup</b> – host runs <code>mchost.exe</code>, clients just double-click <code>client.exe</code>.</li>
</ul>

<hr/>

<h2>🖥️ How It Works</h2>  
<ol>
  <li><b>Host</b> runs <code>mchost.exe</code>, which shares the server’s mod files.</li>
  <li><b>Client</b> runs <code>client.exe</code>.</li>
  <li>It connects to the host.</li>
  <li>Downloads missing or outdated mods.</li>
  <li>Updates the <code>mods/</code> folder automatically.</li>
  <li>Minecraft launches with the correct mod set — no manual steps required.</li>
</ol>

<hr/>

<h2>✅ What Users Need to Do</h2>  
<ul>
  <li><b>Host:</b> Run <code>mchost.exe</code> while hosting the server.</li>
  <li><b>Client:</b> Just run <code>client.exe</code> — mods will auto-update and Minecraft will start.</li>
</ul>
