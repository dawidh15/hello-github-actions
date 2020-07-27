FROM microsoft/windowsservercore
LABEL Description="IIS" Vendor="Microsoft" Version="10"
ADD entrypoint.ps1 /entrypoint.ps1
RUN powershell /entrypoint.ps1
ENTRYPOINT ["/entrypoint.ps1"]
