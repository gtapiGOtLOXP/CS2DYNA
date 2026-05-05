# CS2DYNA
CS2 Bhop script that turns Csharp code to an functional exe.
# CS2 AutoBhop (C#) (Fixed?: Yes, but I don’t know when it was fixed.)

# READ THIS
**IMPORTANT:** if your config doesn’t load automatically, use "**exec autoexec**" in the console or "**-exec autoexec**" in the game launch options.

**Ported from AHK (which used Tweek) to C# because many people were getting errors.**  
I set the default settings to what worked for me. They worked on my system, but things like "FPS change, jumping, etc." might not work for you. I recommend checking. If everything works fine, leave it as is. If not, edit the config yourself. Press Insert in the app and rebind keys so they work for YOU. It’s possible some keys are already in use, etc. Make everything unique to your setup.  

Sometimes the game may crash (**NOT BECAUSE OF THE APP**), but due to the config. This usually happens rarely and only when leaving custom maps or lobbies. I’ve never had crashes in matchmaking or wingman.

upd4. **YOU GUYS NEED TO DISABLE ANTICHEATS BEFORE USING THIS. FACEIT AC, Vanguard, and any other anticheats can completely block automation created by this program. Please stop messaging me that the program doesn’t work—try disabling anticheats before launching the software. If it still doesn’t work, message me on Discord and I’ll help.**

upd5. Since Valve removed the ability to change FPS directly in a match, I decided to use RTSS (you’ll need to download it separately). With it, we lock FPS to 64. The program will automatically configure everything so it works out of the box—just launch it and configs will be applied.  
(Use at your own risk. RTSS is not an official Valve program, but it doesn’t read files or memory. I can’t guarantee anything. Personally, I’ll use it because I don’t care about my account, but you probably shouldn’t get banned for this… although knowing Valve, who knows.)  

My personal opinion (**THIS DOES NOT MEAN IT IS 100% CORRECT**): no, you cannot get banned for this.

---

**Advanced AutoBhop Application for CS2**, written in C#.  
Fully open source, with no direct memory reading. Configuration is done **in the application console**.

---

## Configuration

- At any time, press **Insert** in the console to open the configuration menu.
- In the menu you can:
  - Assign keybinds (jump, toggle, etc.)
  - Adjust autobhop settings to your liking
  - Save or reset settings
- The menu is fully **text-based**, running in the console window, with no GUI or in-game overlays.

---

## Quick Start for Users

1. Download and run the `.exe`.
2. In the window that appears—everything is already running.
3. Press **Insert** to configure.
4. After configuration—minimize the console (or leave it open) and launch CS2.  
   — Autobhop will work automatically, set up in just two steps.

---

## Project Structure

- `AutoBhop.sln` — C# solution (Visual Studio)
- `AutoBhop/AutoBhop.csproj` — project with source code
- `build.bat` — build script (if needed)
- `README.md` — this file

---

## License and Additional Information

- The project is **open source**, freely available on GitHub.
- No memory reading, everything works through high-level logic and console interaction.
- For questions, bugs, or suggestions—you can open an issue or submit a pull request.

---

### Conclusion

**CS2 AutoBhop (C#)** is a simple way to enable automatic bhop in CS2 without complications:  
download .exe → run → configure via **console** (optional) → play with autobhop.
