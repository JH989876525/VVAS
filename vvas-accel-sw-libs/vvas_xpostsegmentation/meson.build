# Copyright (c) 2023 innodisk Crop.
# 
# This software is released under the MIT License.
# https://opensource.org/licenses/MIT

vvas_xpostsegmentation = library('vvas_xpostsegmentation',
  'src/vvas_xpostsegmentation.cpp',
  cpp_args : [vvas_accel_sw_libs_args, '-std=c++17'],
  include_directories : [configinc],
  dependencies : [gst_dep, jansson_dep, vvasutils_dep, gstvvas_dep, opencv_dep],
  install : true,
)
