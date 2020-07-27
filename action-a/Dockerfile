FROM microsoft/windowsservercore

ADD entrypoint.ps1 /entrypoint.ps1
RUN powershell /entrypoint.ps1
ENTRYPOINT ["/entrypoint.ps1"]
