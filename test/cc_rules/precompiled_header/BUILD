c_precompiled_header(
  name = 'all_headers_pch',
  hdr = 'all_headers.h',
  private_hdrs = ['header_1.h'],
)

c_test(
    name = 'lib_test',
    srcs = ['lib_test.c'],
    hdrs = [
        ':all_headers_pch',
    ],
)
