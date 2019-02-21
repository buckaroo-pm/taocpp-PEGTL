load('//:subdir_glob.bzl', 'subdir_glob')

prebuilt_cxx_library(
  name = 'pegtl',
  header_only = True,
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '**/*.hpp'),
  ]),
  licenses = [
    'LICENSE',
  ],
  visibility = [
    'PUBLIC',
  ],
)
