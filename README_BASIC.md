# 📱 Download Your Snapchat Memories - Super Simple Guide

**Got thousands of Snapchat memories and want them on your computer? This tool makes it easy!**

## 🎯 What Does This Do?

This tool helps you download **all your Snapchat photos and videos** to your computer in a much better way than Snapchat's basic download page.

**Instead of this:**
- Clicking download 1,000+ times 😫
- Files named "XdJkmgHT" with no date nor file extension 😕
- No way to organize by month 😞

**You get this:**
- Download everything at once 🎉
- Files properly named with dates 📅
- Organized by month 📂
- Shows progress so you know what's happening 📊

## 🚀 How To Use It (5 Easy Steps)

### Step 1: Get Your Snapchat Data
1. **Go to this website:** https://accounts.snapchat.com/accounts/downloadmydata
2. **Sign in** with your Snapchat username and password
3. **Export your Memories**
4. **Wait for an email** from Snapchat (can take up to 48 hours)
5. **Download the ZIP file** under My Exports in Snapchat web
6. **Extract/unzip** that file on your computer

*You should now have a folder with a few files, including one called `memories_history.html`*

### Step 2: Download the Enhanced Tool
1. **Download** the file called `enhanced_memories_history.html` from this Github page
2. **Save it** to the same folder where your Snapchat data is

### Step 3: Copy Your Personal Data
*This is the trickiest part, but don't worry - we'll walk through it!*

**Option A: Use a Text Editor (Notepad)**
1. **Right-click** on `memories_history.html` → **"Open with"** → **"Notepad"**
2. **Press Ctrl+F** to open search
3. **Type:** `id='mem-info-bar'` and press Enter
4. You should see a line that starts like: `<div id='mem-info-bar' style='color:red'></div>`
5. **Select the entire line** (triple-click on the middle of the line).
6. **Copy it** (Ctrl+C).
7. **Close Notepad**

8. **Right-click** on `enhanced_memories_history.html` → **"Open with"** → **"Notepad"**
9. **Press Ctrl+F** to open search  
10. **Type:** `PASTE YOUR TABLE DATA HERE` and press Enter
11. **Select that text** and **paste your copied line** (Ctrl+V)
12. **Save the file** (Ctrl+S)

**Option B: If You're Comfortable with VS Code**
- Copy line 612 from your original `memories_history.html`
- Paste it at line 1095 in `enhanced_memories_history.html`

### Step 4: Open the Enhanced Tool
1. **Double-click** on `enhanced_memories_history.html`
2. It should open in your web browser (Chrome, Firefox, etc.)
3. You should see a table with all your Snapchat memories!

### Step 5: Download Your Memories
**You have 3 options - pick the one that sounds best:**

#### 📦 Option 1: "Download All as ZIP" (Recommended for Most People)
- **Click the blue "Download All as ZIP" button**
- Your browser will ask permission to download multiple files - **click "Allow"**
- Wait for it to finish (you'll see a progress bar)
- You'll get ZIP files in your Downloads folder
- **Double-click the ZIP files** to see your photos and videos inside!

#### 📅 Option 2: "Download by Month" (Good for Organizing)
- **Click "Download by Month"**
- **Pick a month** from the list (like "November 2024 - 45 memories")
- Wait for that month to download as a ZIP file
- Repeat for other months you want
- *Note: At the 500MB mark, memories will be dowloaded in parts (Part1.zip, Part2.zip, etc.)*

#### 📥 Option 3: "Individual Files" (Slowest but Most Control)
- **Click "Individual Files"**
- It will download them one by one (like the original Snapchat way)
- Good if you only want a few specific photos

## ⚠️ Important Things to Know

### Your Browser Might Ask Questions
- **"Allow downloads?"** → Click **"Allow"** or **"Yes"**
- **"Keep downloading files?"** → Click **"Keep"** or **"Continue"**
- **Pop-up blocked?** → Click the popup blocker icon and allow popups

### How Long Does It Take?
- **100 memories:** About 2-5 minutes
- **1,000 memories:** About 15-30 minutes  
- **5,000+ memories:** Could take 1-2 hours

*Tip: Always try to keep an eye on the dowloading process in case something bugs!*

### Where Do My Files Go?
- They go to your **"Downloads" folder** by default
- Look for files named like `Snapchat_Memories_All.zip`
- **Double-click the ZIP files** to open them and see your photos/videos

## 🆘 Something Not Working?

### "I don't see any memories in the table"
- Double-check you copied the right line from your original file
- Make sure you pasted it in the right place in the enhanced file
- Try refreshing the webpage (F5)

### "Downloads not starting"
- Try a different browser (Chrome usually works best)
- Make sure JavaScript is enabled in your browser
- Clear your browser cache and try again

### "Files have weird names"
- This is normal! Files are now named with dates like `2024-11-27_17-32-47_image_001.jpg`
- Much better than "blob" with no date!

### "ZIP files won't open"
- Try right-clicking → "Extract All" (Windows)
- Or download a free program like 7-Zip
- Some ZIP files might be split into parts (like Part1.zip, Part2.zip) - extract them all

### "My computer is running slow"
- Downloading lots of files uses internet and computer power
- Close other programs while downloading
- Let it finish before doing other heavy computer tasks

## 🎉 Success! What's Next?

Once your downloads finish:

1. **Find your ZIP files** in your Downloads folder
2. **Extract them** (right-click → "Extract All")
3. **Back up your memories** to Google Drive, iCloud, or an external hard drive
4. **Delete the HTML files** (they contain your personal download links)
5. **Enjoy your organized Snapchat memories!** 📸

## 🔒 Is This Safe?

**Yes!** This tool:
- ✅ Only downloads **your own** memories from Snapchat
- ✅ Doesn't send your data anywhere else
- ✅ Works entirely in your browser
- ✅ Doesn't store your photos on any server

**Just remember:**
- Don't share the HTML file with anyone (it has your personal download links)
- Delete the HTML files after you're done downloading

---

## 🙋‍♀️ Still Need Help?

**Can't figure something out?** 
- Check if someone else had the same problem in the "Issues" section above
- Ask a tech-savvy friend to help with Step 3 (the copy/paste part)
- Try using a different computer or browser

**Want to say thanks?** 
- Tell your friends about this tool!
- Give it a star ⭐ on GitHub

---


*Made with ❤️ to help you get your memories back!*
