# ❌ Wolf Client – Fatal Error

The system detected a **critical error** that prevents Wolf Client from starting.  
Please check the possible causes below:

---

## 🔎 Possible Error Reasons
- `system/systemdata/staylimbo.important` is missing  
- `system/systemdata/fatalerror.md` is corrupted or missing  
- Required system files (e.g. `homescreen.html`) cannot be found  
- Your browser cache is outdated or corrupted  

---

## 🛠️ How to Fix
1. Make sure you are running the **official Wolf Client version** (GitHub Pages release).  
2. If you cloned or downloaded the project, confirm all files exist in:
   - `system/systemdata/`
   - `system/programms/`
   - `system/list/`
3. Clear your browser cache and reload the page.  
4. If the error persists, redownload or update to the latest version of Wolf Client.  

---

## ℹ️ Additional Information
- This error screen is automatically displayed when a **system integrity check fails**.  
- If you are a developer, verify that the `staylimbo.important` file is present to confirm a full release build.  

---

> 💡 Tip: Without `staylimbo.important`, Wolf Client assumes you are running an **incomplete or modified build** and will not continue.
