# FILE-RECOVERY-USING-AUTOPSY-SOFTWARE
#### Name: Thaksha Rishi
#### Reg. No. - 212223100058

## AIM
To use **Autopsy Digital Forensics Tool** to retrieve deleted files from a disk image.

---

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tool**: [Autopsy Digital Forensics](https://www.autopsy.com/)  
- **Test Data**: Disk image file (`disk.dd`, `disk.img`, `.E01`)

---

## ARCHITECTURE DIAGRAM

<img width="577" height="785" alt="Screenshot 2025-08-22 151258" src="https://github.com/user-attachments/assets/0e9e4744-5534-4828-8715-d6210ba065c3" />

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

<img width="1678" height="825" alt="image" src="https://github.com/user-attachments/assets/6012fa33-6c4c-49ec-9e03-7c3e63f4ab32" />

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

<img width="1646" height="815" alt="image" src="https://github.com/user-attachments/assets/758ae98a-e83d-4d37-b6d9-33d60c9aeef2" />


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/e45aa2c1-a24f-4a6a-abbd-e7563fbe5578" />


- Select **Local Disk** → **next** 

<img width="1668" height="858" alt="image" src="https://github.com/user-attachments/assets/6d4e2ce6-6b8c-450e-81e7-96a89b671606" />


- Select Disk → **Choose the VHD drive (`Drive1`)**

<img width="720" height="263" alt="image" src="https://github.com/user-attachments/assets/54f3ee1e-ad45-45c1-9468-e9561bc2de93" />


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

<img width="1567" height="710" alt="image" src="https://github.com/user-attachments/assets/91b2a2de-8389-4be6-83a9-7fbc47fc9c50" />




<img width="1917" height="938" alt="image" src="https://github.com/user-attachments/assets/d640dfc1-c158-48c9-bddf-2a407357fef7" />



- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.

<img width="1911" height="901" alt="image" src="https://github.com/user-attachments/assets/d8f27e87-96b0-4495-bb1b-7d1ffc8a7305" />

## Output :


### Folder before deleting the files

<img width="970" height="188" alt="Screenshot 2025-08-22 091320" src="https://github.com/user-attachments/assets/d1700d45-07e9-4a7d-a46c-681420461766" />

### Folder after deleting the files

<img width="1157" height="242" alt="Screenshot 2025-08-22 154355" src="https://github.com/user-attachments/assets/052e0aac-c42d-421e-aba1-e8031bdd3ee5" />

### Folder after extracting the deleted images using autopsy

<img width="970" height="188" alt="Screenshot 2025-08-22 091320" src="https://github.com/user-attachments/assets/342802c8-6f29-4147-a847-e6cceeff0ac8" />


## RESULT:

Deleted files were successfully retrieved and analyzed using Autopsy.
