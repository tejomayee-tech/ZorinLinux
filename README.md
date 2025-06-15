# ZorinLinux

## Videos

1. **Introduction** : [Click Here](https://github.com/tejomayee-tech/ZorinLinux-Introduction-And-Demo/blob/main/ZorinDemo%20(Introduction).mp4)

## Guide: Dual-Boot Zorin OS with Windows

**Goal:** Install Zorin OS next to Windows, letting Zorin handle the hard drive setup.

**IMPORANT:** Highly recommend backing all documents and files on the computer or try on old pc or laptop (you'd be surprized to how you make your old computers productive with Linux). 
> Note: You can also try Zorin with Oracle Virtual Box first or install at your own risk with/without backup. 

### What You Need:

1.  **Computer with Windows 10.**
2.  **Zorin OS:** Download the `.iso` file from `zorin.com/os/download/`. Use `Zorin Core` version for minimal default apps, blazing fast performance, use `Zorin Education` for kids.  
4.  **USB Stick (8GB+):** All data on it will be erased.
5.  **Rufus Software:** Download from `rufus.ie/en/`.
6.  **Important:** **Backup Your Files!**

---

### Step 1: Prepare Windows 10

1.  **Disable Fast Startup:**
    * Search for "Control Panel" -> "Power Options" -> "Choose what the power buttons do" -> "Change settings that are currently unavailable."
    * **Uncheck "Turn on fast startup (recommended)."** Save changes.
    * This prevents issues between Windows and Zorin.
2.  **Create Free Space (Optional but Recommended):**
    * While Zorin's automatic installer can shrink Windows, it's safer and gives you more control to do it first.
    * Press `Windows Key + X` -> "Disk Management."
    * Right-click your `(C:)` drive -> "Shrink Volume."
    * Enter **20000 MB to 50000 MB (20-50 GB)** or more for Zorin. This creates "Unallocated space."

---

### Step 2: Create Zorin OS USB Stick

1.  **Plug in your USB stick.**
2.  **Open Rufus.**
3.  **Select your USB stick** under "Device." (Double-check!)
4.  Click **"SELECT"** and choose the downloaded Zorin OS `.iso` file.
5.  Ensure "Partition scheme" is **GPT** (for most modern PCs).
6.  Click **"START."** Confirm that you want to erase the USB stick.
7.  Wait until Rufus says "READY," then close it.

---

### Step 3: Start from USB

1.  **Insert the Zorin OS USB stick.**
2.  **Restart your computer.**
3.  **Enter BIOS/UEFI Settings or Boot Menu:**
    * As your computer restarts, you need to repeatedly press a specific key to enter the "BIOS/UEFI Setup" or "Boot Menu."
    * **Common Keys:**
        * **Dell:** `F2` (BIOS) or `F12` (Boot Menu)
        * **HP:** `F10` (BIOS) or `F9` (Boot Menu)
        * **Lenovo:** `F1` or `F2` (BIOS) or `F12` (Boot Menu)
        * **Acer:** `F2` (BIOS) or `F12` (Boot Menu)
        * **Asus:** `Del` or `F2` (BIOS) or `F8` (Boot Menu)
        * **Microsoft Surface:** Press and hold Volume Up while pressing power button.
        * **General:** `Esc`, `F1`, `F8`, `F9`, `F10`, `F11`, `F12`, `Del`
4.  From the boot menu, select your **USB stick** (e.g., "UEFI: Your_USB_Name").

---

### Step 4: Experience Zorin OS (Without Installing)

Before you install, you can try Zorin OS right from the USB stick! This is a great way to see if you like it and if everything (like Wi-Fi, sound) works.

1.  **Zorin OS Welcome Screen:**
    * After your computer starts from the USB, you'll see a Zorin OS screen.
    * Use your keyboard arrows to select "Try or Install Zorin OS" and press `Enter`.
    * It might take a few moments for Zorin OS to load.
2.  **Explore Zorin OS:**
    * You'll now be in a fully functional Zorin OS desktop environment!
    * You can open the web browser, play around with the settings, connect to Wi-Fi, etc.
    * **Important:** Any changes you make or files you save in this "Try Zorin OS" mode will be lost when you shut down or restart, as it's running only from the USB stick.

### Step 5: Install Zorin OS (Automatic)

1.  On the first Zorin screen, select **"Try or Install Zorin OS."**
2.  Once Zorin OS loads, double-click the **"Install Zorin OS"** icon on the desktop.
3.  **Language:** Choose your language -> "Continue."
4.  **Keyboard Layout:** Select your layout -> "Continue."
5.  **Updates:**
    * **Check "Download updates while installing Zorin OS."**
    * **Check "Install third-party software..." (Highly Recommended!)** -> "Continue."
6.  **Installation Type (Crucial Step):**
    * Select **"Install Zorin OS alongside Windows Boot Manager."**
    * **Yes, this option automatically shrinks Windows (if you didn't do it manually) and creates the necessary partitions for Zorin.** If you already created unallocated space, it will use that.
    * Click "Continue."
7.  **Allocate Disk Space:**
    * You'll see a slider to choose how much space Zorin gets from your hard drive. Adjust as desired. (If you pre-shrunk, it will use the "Unallocated space").
    * Click "Install Now." Confirm changes.
8.  **User Setup:**
    * Pick your location, name, computer name, username, and **set a strong password (remember it!).** -> "Continue."
9.  **Wait for Installation:** Zorin OS will install.
10. **Restart:** When prompted, click "Restart Now." Remove the USB stick when the screen tells you to.

---

### Step 6: Choose Your System

1.  When your computer starts, you'll see a menu (GRUB).
2.  Use the **Up/Down arrow keys** to select:
    * **"Zorin OS"** to use Linux.
    * **"Windows Boot Manager"** to use Windows 10.
3.  Press `Enter`. If you don't choose, it will auto-start Zorin OS after a few seconds.

You're all set! Enjoy the world of Linux with the most user friendly and fast OS.
