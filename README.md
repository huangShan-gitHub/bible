# bible
bible json format file
local json files that may be needed when building your own Bible project

English
Basic English Full Bible (bible_en.json)
Old Testament (old_bible_en.json)
New Testament (new_bible_en.json)

JSON

The JSON files are also encoded using UTF-8 and built in the following structure:

[
 {
  "book": "Matthew",
  "chapters":
   {
     "chapter": "1",
     "verses
       {
         "verse": "1",
         "text": "The book of the generation of Jesus Christ, the son of David, the son of Abraham."
       },
       ........
       {
         "verse": "2",
         "text": "Abraham begat Isaac; and Isaac begat Jacob; and Jacob begat Judas and his brethren;"
       }
     }   
     ......
 }
 ......
]

You can get the number of the chapter and verse using the array index.
