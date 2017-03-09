# Spring Booot REST File Upload


  Upload a file:
  
  /rest/upload?file={file} POST
  
  
  List all uploaded files:
  
  /rest/getallfiles GET
  
  REST Service Controller: 
  FileController - 
  Executes incoming request and defines URL to service method mappings. All remote call are delegated to the archive service.
  
  Data access object:
  Interface - FileUploadDAO
  Implementation - FileUploadImpl
  Data access object to insert load files. FileUploadImpl saves documents in the file system. No database in involved.
  
  
  
