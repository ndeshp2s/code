## file path generator from path patterns  
Originally published: 2010-05-18 03:39:00  
Last updated: 2010-07-09 19:10:59  
Author: Trent Mick  
  
Provides a `_paths_from_path_patterns` that will generate a list of paths from a list of path patterns. A "path pattern" can include glob chars. By default it generates a recursive listing of file paths, but: recursion can be turned off, file and/or dir paths can be listed. It supports a list of glob exclusions or inclusions.