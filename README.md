# Website Starter!

To add the website starter code to your cs50 workspace, do the following:

1. **Close and re-open your terminal (click the trash bin)**
<img height="361" alt="Screenshot 2025-11-03 at 12 13 14 AM" src="https://github.com/user-attachments/assets/46fdbbae-594d-4730-b105-7e8ee482e6e9" />
<img width="886" height="371" alt="Screenshot 2025-11-03 at 12 14 32 AM" src="https://github.com/user-attachments/assets/25518692-e330-4de6-923a-2c657a9d8a92" />

<br/>

<br/>

<br/>

<br/>

2. **Run this command in Terminal:**

MacOS
```bash
git clone --depth 1 https://github.com/mrsharp-milken/website-starter.git temp && rm -rf temp/.git && mv temp/{*,.*} . 2>/dev/null && rmdir temp
```
Windows
```PowerShell
git clone --depth 1 https://github.com/mrsharp-milken/website-starter.git temp; Remove-Item -Recurse -Force temp\.git; Get-ChildItem temp -Force | Move-Item -Destination .; Remove-Item -Recurse -Force temp
```

<img width="1625" height="722" alt="Screenshot 2025-11-03 at 12 18 49 AM" src="https://github.com/user-attachments/assets/198fafcd-bfd2-440a-b492-69e7b4579e86" />


3. **Open `index.html` and `style.css`**

<img width="1840" height="824" alt="image" src="https://github.com/user-attachments/assets/1317a995-4067-49f2-b223-90d16c009504" />


4. **Start working!**
