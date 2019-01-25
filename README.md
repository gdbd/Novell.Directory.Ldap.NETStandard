Rebild of https://github.com/dsbenghe/Novell.Directory.Ldap.NETStandard

 Changes comapred to origin:
 - replaced  1.0.2 to 2.1.1 vesrion of packages:
    Microsoft.Extensions.Logging
    Microsoft.Extensions.Logging.Abstractions
    Microsoft.Extensions.Logging.Debug" Version
- removed build for netstandard1.3

reason:
Project built on .netcore 2.1 contains package which references one of mentioned above.
In runtime accurs filenotfoundexception for Novell.Directory.Ldap.NETStandard.dll or one of it depencies