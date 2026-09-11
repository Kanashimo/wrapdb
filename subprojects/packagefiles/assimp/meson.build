project(
  'assimp',
  'cpp',
  version: '6.0.5',
  meson_version: '>=0.56.0'
)

cc = meson.get_compiler('c')

if cc.get_id() == 'clang'
  add_project_arguments('-Wunsafe-buffer-usage', language: 'cpp')
endif
