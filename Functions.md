


#### Taken the nth token till last in the split

 name_surname_detail
 name_surname_detail1_detail2
 name_surname_detail_detail1_detail2_detail3

  >  RIGHT([Field Name],LEN([Field Name]) - FINDNTH([Field Name],"_",2))
  
#### Regexp_Match

  >  REGEXP_MATCH(string, pattern):
