# SuhelMachine
Vulnerable VM, public for learning
Lab Name: VulnLab: Suhel's Box — Basic to Root

Author: Suhel Kathi
Email ID: suhelkathi94@gmail.com
Mobile : +918879360479
https://www.linkedin.com/in/suhel-kathi-26018a244/

Goal / Flag Location:
- Your mission is to escalate privileges and capture the root flag located at:
  /root/root.txt

Intended Difficulty:  
- Beginner to Intermediate

## 🖥️ Requirements to Run

- **Recommended:** VMware Workstation 17+
- **Compatible with:** VMware Workstation 16 *(with minor modification)*

---

## ⚠️ Opening in VMware 16 – Important Fix

If you are using **VMware Workstation 16** or **VMware Player 16**, you must **downgrade the VM's virtual hardware version manually**:

1. Open the VM folder after extracting the `.zip`.
2. Locate the file with the extension: `.vmx` (e.g., `Ubuntu 64-bit (2).vmx`).
3. Open it in any text editor (like Notepad).
4. Find this line (or similar):

virtualHW.version = "20"

markdown
Copy
Edit

5. Change `"20"` to `"16"`:

virtualHW.version = "16"

markdown
Copy
Edit

6. Save and close the file.
7. Now open the VM in VMware Workstation 16.

✅ Done! The VM should now be compatible.


Contact:  
If you'd like to share feedback, you can reach me at: suhelkathi94@gmail.com
