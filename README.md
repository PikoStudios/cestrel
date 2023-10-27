# Cestrel
An easy-to-use structured game engine for C11

## Licensing
For now, Cestrel is under the MIT License. However expect LGPLv2.1 in some way in the future, this will most likely be for commerical use only. The most important thing to mention about a possible migration to LGPLv2.1 is static linking. In general, static linking is prohibited by LGPLv2.1 but under two conditions will static linking be allowed under LGPLv2.1, those being:
 - The application can also be licensed under LGPLv2.1
 - The application object and any build scripts or other relevant files needed to be able to link against another version of the library are provided. **THIS DOES NOT MEAN YOUR VERSION OF THE LIBRARY MUST BE ABLE TO BE INTERCHANGED WITH OTHER VERSIONS.** For example: if you make a change to the library and your application relies on these changes, like a new function, you may still statically link even if the application cannot link against other versions of the library. You do have to distribute any changes and provide the object file.
