# Windows-Sandbox-with-Local-Disk

#### Windows Features

Use the search bar on the task bar and type Turn Windows Features on or off to access the Windows Optional Features tool. Select Windows Sandbox and then OK. Restart the computer if you're prompted.

#### sandbox.wsb
```
 <Configuration>
  <MappedFolders>
     <MappedFolder>
      <HostFolder>C:\</HostFolder>
      <ReadOnly>true</ReadOnly>
    </MappedFolder>
    <MappedFolder>
      <HostFolder>D:\</HostFolder>
      <ReadOnly>true</ReadOnly>
    </MappedFolder>
  </MappedFolders>
</Configuration>
```
