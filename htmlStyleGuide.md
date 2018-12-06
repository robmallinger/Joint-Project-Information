# HTML Style Guide

* Omit the protocol portion (http:, https:) from URLs pointing to images and other media files, style sheets, and scripts unless the respective files are not available over both protocols.
* Indent by 2 spaces at a time.
* Use only lowercase.
* Remove trailing white spaces.
* Use UTF-8 (no BOM). Make sure your editor uses UTF-8 as character encoding, without a byte order mark. Specify the encoding in HTML templates and documents via <meta charset="utf-8">. Do not specify the encoding of style sheets as these assume UTF-8.
* Use comments to explain code.
  * ``<!-- text -->`` for HTML.
  * ``/* text */`` for CSS.
* Mark todos and action items with TODO. Highlight todos by using the keyword TODO only, not other common formats like @@. Append a contact (username or mailing list) in parentheses as with the format TODO(contact). Append action items after a colon as in TODO: action item.
* Use HTML5. <!DOCTYPE html>.
* Use tools such as the W3C HTML validator to test.
* Provide alternative contents for multimedia. (For images whose alt attributes would introduce redundancy, and for images whose purpose is purely decorative which you cannot immediately use CSS for, use no alternative text, as in alt="".)
* Separate structure from presentation from behavior.
* Omit optional tags (optional).
* Omit type attributes for style sheets and scripts.
* Use a new line for every block, list, or table element, and indent every such child element. (If you run into issues around whitespace between list items it’s acceptable to put all li elements in one line.)
* When quoting attributes values, use double quotation marks.
* Whenever possible, use width=“” and height=“” attributes with <img> elements to speed page loading of images….though these should be controlled in CSS(?).
## ALSO….
* Use jpeg for colorful images, png or gif for flat fill colors.
* Save images in the same pixel dimensions that they will be used on the screen.
