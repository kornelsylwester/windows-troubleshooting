# windows-troubleshooting
Creating scenarios in Windows 11 that let me test different troubleshooting and performance tools.

1. Simulating high CPU usage with a Power Shell script.
   In the PowerShell ISE I will create a simple script that's only job is to create an endless loop with calculations on big numbers. This will considerably slow down CPU performance.
   <img width="1235" alt="Screen Shot 2024-02-02 at 11 40 31 AM" src="https://github.com/kornelsylwester/windows-troubleshooting/assets/63569412/4de20f95-5f91-4964-9331-035ef0f600e8">
2. I prefer not to post this script here, since someone may misuse it.
   I run it from the PowerShell console:
   ![Screen Shot 2024-02-02 at 11 46 43 AM](https://github.com/kornelsylwester/windows-troubleshooting/assets/63569412/1545307b-9202-4f09-a41e-4cf2c281d097)

3. In Task Manager I can see the offending process represented as the PowerShell ISE.
   This is because I started it from within the ISE console.
   We can see that it's consuming around 30% of the available CPU processing power!
<img width="1035" alt="Screen Shot 2024-02-02 at 11 47 05 AM" src="https://github.com/kornelsylwester/windows-troubleshooting/assets/63569412/6540a741-f934-4826-8ca6-c94dfbb53205">

4. From here, I can examine it further in the Details tab, or right-click and End Task.
   This will free up the CPU resources from this endless loop.
   

    
