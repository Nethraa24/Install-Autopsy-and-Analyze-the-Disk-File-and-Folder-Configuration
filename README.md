# Install-Autopsy-and-Analyze-the-Disk-File-and-Folder-Configuration
## AIM:
To install Autopsy on Kali Linux and analyze disk images, files, and folder configurations for digital forensic purposes.

## DESIGN STEPS:
### Step 1:
### **Step 3: Install Autopsy (GUI-based Forensic Tool)**
🔗 **Download Autopsy**: [Click Here](https://www.autopsy.com/download/)  

### **Installation Steps:**
1. Download the **Autopsy Windows Installer** from the official website.  
2. Extract the ZIP file and open the **bin** folder.  
3. Run `autopsy.exe` and set up a new forensic case for analysis.


### **Step 4: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version

### **Step 5: Create & Configure a Virtual Hard Disk (VHD) in Windows**

1. Press **Win + X**, Select Disk Management.
2. Click Action > Create **VHD**.
3. Choose a location and set a disk size (e.g., 10GB+).
4. Select Fixed Size or Dynamically Expanding and click OK.
5. In Disk Management, find your new disk (marked as "Not Initialized") -> Right-click the new disk → Initialize Disk → Select **MBR**.
6. Right-click Unallocated Space → **New Simple Volume** → Format the disk -> Click next → Finish.

---

## Output:

### **Autopsy**

![image](https://github.com/user-attachments/assets/5773fd17-45c1-4361-bc41-fe94d3d26272)


---

### **Creation of Virtual Hard Disk**

![image](https://github.com/user-attachments/assets/c23434bb-a48a-4aac-8ce8-87d0862e8416)

---


## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
