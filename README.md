# visual_studio_code_style

Set the file code style which created by visual studio.

Others Editor also can use this.


### Support Visual Studio version

Visual Studio Community 2017 (15.5.2)


### Usage

put the file `.editorconfig` in the c/c++ code project top folder. THAT'S ALL. 

and every file's code style created by Visual Studio will be same with the documented in `.editorconfig`.

### other tryings

also try the Visual Studio's externsions, but failed.

```
https://marketplace.visualstudio.com/items?itemName=vilicvane.ForceUTF8
Save all text files without BOM in UTF8 encoding, no BOM will be added.
```

```
https://marketplace.visualstudio.com/items?itemName=SergeyVlasov.FixFileEncoding

When you edit a UTF-8 file in Visual Studio, it adds the byte order mark (BOM) sequence 
to the beginning of the file. You can select an encoding manually, 
but you need to do it each time you reopen the file.
```
