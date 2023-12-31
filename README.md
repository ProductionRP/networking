## Running WinMTR

When other diagnostic tools aren't enough, or you want a combination of traceroute and ping functions, WinMTR is an invaluable tool. It can help identify specific points of failure in your connection path.

### Steps:
1. [Download WinMTR](https://sourceforge.net/projects/winmtr/files/WinMTR-v092.zip/download)
2. Extract the .zip file to your desktop.
3. Navigate to the WinMTR folder, then choose the appropriate version for your machine (32-bit or 64-bit). Start the `WinMTR.exe` application.
4. In the **Host** field, type `play.productionrp.org`.
5. Click **Start** and allow it to run for at least five minutes. If no issues appear during this duration, you can opt to restart the test for another round.
6. If any abnormalities are detected, let the test continue for another five minutes, then click **Stop**.
7. To save the report, use the "Export Text" option. Save the `.txt` file on your desktop with the name `WinMTR.txt`.
8. When reaching out for assistance or submitting a report, make sure to attach this `WinMTR.txt` file.

**Before submitting a ticket on Discord**:  
Ensure you provide:
- A clear description of the issue you're facing.
- Exact time and date of the problem's occurrence.
- Your IPv4 address.
- The `WinMTR.txt` file from your desktop.
