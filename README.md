Created a spreadsheet engine from scratch. Implements:  
Cell and sheet referencing (e.g. =Sheet1!A1)  
Workbook functions (AND, OR, XOR, EXACT, ISBLANK, SUM, MIN, MAX, AVERAGE)  
Parsing formulas with Lark parser  
Cell error handling (circular references, bad references, type errors, etc.)  
Moving/copying/renaming sheets, moving/copying cells  
Cycle detection, used in circular references and certain functions (ISERROR, IFERROR)  
  
Written in Python  
