.NET SDK
=========

Installs .NET SDK using official installation script

Example Playbook
----------------

    - hosts: desktop
      roles:
         - dotnet-sdk
      vars:
        version: 9.0.306 # latest by default

License
-------

MIT