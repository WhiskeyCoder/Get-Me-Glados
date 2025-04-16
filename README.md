# get_me_glados.py

<p align="center">
  <img src="https://static.wikia.nocookie.net/villains/images/7/79/GLaDOS_P2.png/revision/latest?cb=20210517180141" width="50%">
</p>


## 🎙 get_me_glados.py

A mildly unhinged script that downloads **every voice line of GLaDOS** from Portal, for "educational" purposes (and definitely not AI voice trolling). It scrapes the Portal Wiki, finds all the `Download` links, and saves them into a local `audio_files/` folder.

Because why *wouldn't* you want a library of sass, sarcasm, and passive-aggressive cake-based threats?

---

### 🧠 Features
- Crawls the Portal Wiki GLaDOS voice line page
- Automatically detects and downloads all files labeled "Download"
- Saves files to `audio_files/` directory (created automatically if it doesn’t exist)
- Great for:
  - AI voice cloning
  - Soundboards
  - Scaring your friends
  - Reminding coworkers that "the cake is a lie"

---

### 📦 Requirements
- Python 3.x
- `requests`
- `beautifulsoup4`
- `urllib`

Install missing dependencies:
```bash
pip install requests beautifulsoup4
```

---

### 🚀 Usage
```bash
python get_me_glados.py
```

This will:
1. Fetch [this GLaDOS wiki page](https://theportalwiki.com/wiki/GLaDOS_voice_lines_(Portal))
2. Find all the download links
3. Download them into the `audio_files/` folder

---

### 📝 Notes
- If the `audio_files` folder doesn’t exist, the script will create it.
- If any files fail to download, the script will print an error but keep going.

---

### ⚠️ Disclaimer
- Use responsibly. GLaDOS is watching.
- Don’t use these lines commercially or claim them as your own. They belong to Valve.

---

### 💀 Example Output
```bash
File 'glados_welcome.wav' downloaded successfully.
File 'glados_cake_lie.wav' downloaded successfully.
File 'glados_you_monster.wav' downloaded successfully.
...
```

---

### 🧁 "This was a triumph..."
Let the trolling begin. Or build a voice model. Or just vibe with her glorious passive-aggressive energy.

> *"Well done. Here come the test results: You are a horrible person. That’s what it says. A horrible person. We weren’t even testing for that."*

