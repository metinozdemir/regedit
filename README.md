# regedit

When we adding registry entry we create a text file to reg file. And add a 

"Windows Registry Editor Version 5.00" to the top of file.

After than if we want to adding a Entry or Key we use [] to Path.

  [HKEY_CURRENT_USER\Test]
  "New Value #1"="123"


If we want to delete a Entry or Key we can use [-] to Path.

  [-HKEY_CURRENT_USER\Test]
  "New Value #1"="123"

