# SharpInvoke-SMBExec
A native C# conversion of Kevin Robertsons Invoke-SMBExec powershell script. (https://github.com/Kevin-Robertson/Invoke-TheHash/blob/master/Invoke-SMBExec.ps1)

Built for .NET 4.0+

# Description
This Assembly will allow you to execute a command on a target machine using SMB by providing an NTLM hash for the specified user.



# Usage
Sharp-InvokeWMIExec.exe target_ip test\username hash command

# Example
Sharp-InvokeWMIExec.exe 192.168.1.100 User 161cff0846hfe596a5d45b8186y98a24 "calc.exe"
Sharp-InvokeWMIExec.exe 192.168.1.100 User 161cff0846hfe596a5d45b8186y98a24 "calc.exe 123" nowait
        


