FROM mcr.microsoft.com/windows/nanoserver/insider:10.0.20170.1000
LABEL Description="IIS" Vendor="Microsoft" Version="10"
ADD entrypoint.ps1 /entrypoint.ps1
RUN powershell /entrypoint.ps1
ENTRYPOINT ["/entrypoint.ps1"]
