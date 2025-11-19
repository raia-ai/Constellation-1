
# eSign - Anchor Tags | Constellation1 Customer Hub

An **eSign Anchor Tag** is a specially formatted text embedded into Word/Excel/PDF documents, that defines signing tags for eSign to render on a document during the signing ceremony. We support the following types of tags (Signature, Initial, Date Time, Free Text, Checkbox, Radio button, Dropdown list).

Two things need to be done for clients to get this feature.

*   Need to subscribe to eSign Anchor Tag service, so it gets enabled for you.
*   If using eSign APIs, set the new Document object property **HasAnchorTags** to true, to notify the service to scan the document for anchor tags. Refer to the API Reference for Create/Update Session.

**NOTE**: Do **_NOT_** just set all documents HasAnchorTags to true, as your sessions will take longer to process.

By subscribing to this feature it also makes it available in eSign UI when uploading documents. Where you can select the document(s) that has/have tags and click on the “**Read Tags**” button.

The text that defines the tag must start and end with a **_single_** special character that doesn’t appear in the uploaded document, and the client has the freedom to define what the opening and closing characters should be. e.g. the default opening character is ‘<‘ and the default closing is ‘>’, but the administrator can change them for you as desired, e.g. ‘#’ and ‘#’.

**NOTE**: Know that if these characters exist in the document then any text between them will be treated as a tag and it will get **_removed_** from the document, but no actual tag will appear on your final document. So, be careful about this.

Now, let’s explain the tag syntax, assuming the opening/closing characters are the default.

The supported types of eSign tags:

– DateTime (or only Date or Time)Â tag  
– Signature tag  
– Initial tag  
– Text tag  
– Checkbox tag  
– Radio tag  
– Dropdown tag

**Syntax format**: **<**\[Tag Type\]\_\[Tag Option\]\_\[Role Name\]\_\[Tag Width in pixels\]**\>**  
**NOTE**: For Text tag only, option to include the font size in pixels in range of 6-28, anything outside this range will be rolled up/down.  
**<**\[Tag Type\]\_\[Tag Option\]\_\[Role Name\]\_\[Tag Width in pixels\]\_\[Font size in pixels\]**\>**

**Definitions**:

1.  Tags Types:

*   DateTime:  
    There are 3 possible values for this (**dt**Â = datetime, **d** = date only, **t** = time only)

*   Tag Options:  
    **req** for Required  
    **opt** for Optional  
    **aut** for Auto-Fill

*   Signature:  
    Specified as, **sig**

*   Tag Options:  
    **req** for Required  
    **opt** for Optional

*   Initial:  
    Specified as, **ini**

*   Tag Options:  
    **req** for Required  
    **opt** for Optional

*   Text:  
    Specified as, **txt**

*   Tag Options:  
    **req** for Required  
    **opt** for Optional
*   Font Size: values in range of 6-28

*   Checkbox:  
    Specified as, **chk**

*   Tag Options:  
    **req** for Required  
    **opt** for Optional

*   Radio:  
    Specified as, **rdo**

*   Tag Options:  
    **req** for Required  
    **opt** for Optional  
    **2..10** Number of radio buttons

*   Dropdown:  
    Specified as, **ddl**

*   Tag Options:  
    **req** for Required  
    **opt** for Optional  
    **Item1…ItemN** List of items in the DDL

2.  Role Name

*   This can be any name you want that matches your roles in eSign. If you mistype a role then it will not get mapped to the corresponding eSign role and your document will need to be mapped manually through eSign UI.

4.  Tag Width

*   This is in pixels, if not provided or value is below the minimum zone value, then the zone will be set to its default value.

*   Signature’s minimum width is: 80px, and default: 175px
*   Initial’s minimum width is: 35px, and default: 45px
*   Date/Time minimum width is: 50px, and default: 100px
*   Text’s minimum width: 20px, and default: 175px

**Examples 1**:  
Tag of datetime, required, for role buyer. Will default to the default width.

<dt\_req\_buyer>

Tag of date only, required, for role buyer, with 150px width.

<dt\_req\_buyer\_150>

**Example 2**:  
Tag of time only, optional, for role seller, will default to default size since 10px is under minimum size.

<t\_opt\_seller\_10>

**Example 3**:  
Tag of signature, required, for role seller, a width of 100px.

<sig\_req\_seller\_100>

**Example 4**:  
Tag of checkbox, required, for role client.

<chk\_req\_client>

**Example 5**:  
Tag of radio button, required, for role client, with 3 buttons.

<rdo\_req\_client\_3>

**Example 6**:  
Tag of dropdown list, required, for role client, with 3 items.

<ddl\_req\_client\_50\_Birds\_Mammals\_Vertebrates>

**Example 7**

<txt\_req\_borrower\_100\_9>

<txt\_req\_borrower\_100>

NOTE: Some of our clients’ methods of generating their anchor tagged PDF with spaces in the DDL items result in some hidden characters instead of the space, which in turn removes the space e.g.

Depending on the process of generating the document such spaces between “Item 1” are not spaces, so when the file is uploaded into our system we read “Item1” without a space. For such cases, since we cannot fix incorrect files, we came up with a work around where you can replace the space with another configured character in your eSignature client’s setup, e.g. instead you can use a pipe character ‘|’ as follows <ddl\_req\_client\_50\_item|1\_item|2> and our system will replace this character with a valid space character.</ddl\_req\_client\_50\_item|1\_item|2>