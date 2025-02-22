# Chatbot
Simple sample Chatbot


How to Publish as a Standalone EXE
If you want a single executable file that works on other computers without needing .NET installed, do this:

1️⃣ Right-click on Your Project
In Solution Explorer, right-click your project.
Select Publish.
2️⃣ Choose a Publish Method
Click Folder (to save it locally).
Click Next.
3️⃣ Select Deployment Mode
Choose Self-contained if you want the app to include .NET runtime.
Choose Framework-dependent if the target machine has .NET installed.
4️⃣ Choose Target Runtime
If you want a single .exe file:
Check Produce single file.
Check Enable ReadyToRun compilation (for performance).
Check Trim unused assemblies (to reduce size).
5️⃣ Click Publish
The .exe will be saved in the publish folder inside your project.
