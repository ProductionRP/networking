## Running a Traceroute

When facing persistent connection disruptions, choppy VOIP, or other connectivity issues, a traceroute can provide valuable insight into the problem. This procedure displays the journey your connection takes to reach its endpoint.

### Windows Users:
1. Click on the **Start** button.
2. Type `cmd` in the search box.
3. Right-click on `CMD.exe` and choose **Run as Administrator**.
4. Type `cd Desktop` and press Enter.
5. Next, enter `tracert netflow.productionrp.net > tracert.txt` and press Enter.
6. Please wait a few minutes. Once a new command line appears, the traceroute has concluded. A `tracert.txt` file will be saved on your desktop.
7. If any errors arise, ensure the command prompt was launched with administrative rights. 

**Before opening a ticket on Discord**:  
Prepare the following information:
- Description of the issue.
- Time and date of occurrence.
- Your IPv4 address.
- The `tracert.txt` file from your desktop.

[Understanding Traceroute Results](#analyzing-my-traceroute)

---

## Running a Pathping

Pathping can help detect packet loss between your computer and our servers, which could be a cause for constant disconnects or choppy VOIP.

### Windows Users:
1. Click on the **Start** button.
2. Search for `cmd`.
3. Right-click `CMD.exe` and select **Run as Administrator**.
4. Type `cd Desktop` and hit Enter.
5. Enter `pathping netflow.productionrp.net > pathping.txt` and press Enter.
6. Be patient; after a while, a `pathping.txt` file will appear on your desktop.

**Before submitting a ticket on Discord**:  
Ensure you have:
- A description of the problem.
- Time and date details.
- Your IPv4 address.
- The `pathping.txt` file from your desktop.

[Interpreting Pathping Data](#analyzing-a-pathping)

---

## Running WinMTR

For specific scenarios where the usual tests don't clarify the underlying issue, a WinMTR test might be suggested.

### Steps:
1. [Download WinMTR](https://sourceforge.net/projects/winmtr/files/WinMTR-v092.zip/download)
2. Extract the .zip file to your desktop.
3. Open the WinMTR folder, then choose the appropriate version (32-bit or 64-bit). Start `WinMTR.exe`.
4. In the **Host** field, type `netflow.productionrp.net`.
5. Click **Start**. If after five minutes no issues surface, restart the test.
6. If an error is identified, persist for another five minutes, then click **Stop**.
7. Use "Export Text" and save the `.txt` file on your desktop as `WinMTR.txt`.
8. Attach this file when seeking support on Discord.

---

## Analyzing My Traceroute

If your traceroute reveals issues such as time-outs, asterisks (*), significant latency spikes between stages, or consistently high latency, this could point to potential problems. Occasional high packet loss (PL) might be normal, but consistent PL that causes you to disconnect constantly, especially during in-game activities, can suggest ISP-related issues or challenges with your connection.

---

## Analyzing A Pathping

Consistent packet loss, especially during gameplay, may hint at a need to communicate with your ISP. If the packet loss originates at your router or modem, consider a firmware update or hardware replacement. Should you require assistance interpreting your pathping, share the results on our Discord support channel. Note: Some packet loss spikes upon playing on our servers can be disregarded unless they reach 15%+ at a high rate and do not settle.

---
