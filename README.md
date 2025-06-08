# ZorinLinux

You're right, the previous guide was very detailed. Let's make it concise and directly address your points about the automatic option.

Here's a crisp, brief guide to dual-booting Zorin OS with Windows 10, focusing on the automatic installation:

---

## Simple Guide: Dual-Boot Zorin OS with Windows 10

**Goal:** Install Zorin OS next to Windows 10, letting Zorin handle the hard drive setup.

### What You Need:

1.  **Computer with Windows 10.**
2.  **Zorin OS:** Download the `.iso` file from `zorin.com/os/download/`.
3.  **USB Stick (8GB+):** All data on it will be erased.
4.  **Rufus Software:** Download from `rufus.ie/en/`.
5.  **Important:** **Backup Your Files!**

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
3.  As it restarts, repeatedly press your computer's **Boot Menu key** (common: `F12`, `F10`, `Esc`, `F2`).
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

You're all set! Enjoy dual-booting.
