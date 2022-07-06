# Livingston_Ref_Value_types
Reference vs Value type differences


Reference types and values types main difference is how their information is shared. Reference types point to a specific block of memory. Reference types, also known as classes, share an instance of data. Any changes made to one variable affects the original. Reference types point to a specific point in memory. 

  Value types create new instances of the original type.  Much like sharing an email document to multiple people. Any changes made to those copies don't affect the original value type. Value types are structs, enum, tuples. This is particularly useful when implementing across multiple threads. It helps to ensure that the original value won't get broken.
The pros and cons of using reference type over value type is memory usage. A pro to using reference types would be less memory space is used, and thus be faster to run. A con might be that any changes to new instances of that data type would affect the original. 
While value types use new blocks of memory every time they're called. Con to using value types is implementing more memory space.
  
  Reference and Value types are used similarly implemented between ObjC and Swift. With Swift, however, there are more options of using the two types of value types.


Link to UML File
https://lucid.app/lucidchart/6517a19d-a940-4871-8803-1e87ebaba2c9/edit?invitationId=inv_f2c651ba-83e7-4759-9163-be06c4ecfb07#
