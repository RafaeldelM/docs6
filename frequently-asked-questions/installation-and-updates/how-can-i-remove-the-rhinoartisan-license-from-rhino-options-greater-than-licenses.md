# How can I remove the RhinoArtisan license from Rhino Options > Licenses?

Yes. You can manually remove the RhinoArtisan license files from your computer.

Follow these steps:

1. Open Windows File Explorer.
2. Browse to the following folder:

```
%appdata%\McNeel\Rhinoceros\6.0\License Manager\Licenses
```

3. You will probably find several license files in this folder.\
   Delete all the files inside.
4. Then browse to:

```
%programdata%\McNeel\Rhinoceros\6.0\License Manager\Licenses
```

5. You will probably find one license file in this folder.\
   Delete all the files inside.

After removing these files, restart Rhino. The RhinoArtisan license should no longer appear under Options > Licenses.
