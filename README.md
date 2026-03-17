# Fix for Cursor/Windsurf Installation Hanging on Windows

I encountered a persistent setup issue while trying to install or update to the latest version of **Cursor**. Since my previous comments regarding this fix were removed from the official channels, I'm documenting the solution here to help others facing the same problem.

## 🛠 The Problem
The installation process hangs or fails to complete. This issue appears to be related to compatibility conflicts between certain VS Code-based builds and Windows system processes.

## ✅ The Solution
This fix was originally shared by **"冷冷的火花"**. If your installation is stuck, follow these steps:

1.  **Open Task Manager**: Press `Ctrl + Shift + Esc`.
2.  **Search for PowerShell**: Go to the "Processes" or "Details" tab and search for any running `powershell.exe` processes.
3.  **End Tasks**: Right-click and **End Task** on all active PowerShell processes.
4.  **Resume**: Once the processes are closed, the installation should automatically resume and finish successfully.

---

### Reference
Here is the original suggestion (in Chinese):
![Solution Source](./image_1153a5.png)

*Note: This solution also applies to similar issues found during Windsurf installations.*
