cxx_library(
  name = 'sqlitecpp', 
  header_namespace = 'SQLiteCpp', 
  exported_headers = subdir_glob([
    ('include/SQLiteCpp', '**/*.h'), 
  ]), 
  srcs = glob([
    'src/**/*.cpp', 
  ]), 
  deps = [
    '//sqlite3:sqlite3', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
