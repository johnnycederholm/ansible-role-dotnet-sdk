.NET SDK
=========

Installs .NET SDK using official installation script

Example Playbook
----------------

    - hosts: desktop
      roles:
         - dotnet-sdk
      vars:
        dotnet_versions: 
          - 8.0
          - 9.0
          - 10.0

License
-------

MIT