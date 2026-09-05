use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': 'f8e8a164822d4f65e757bff66bc00e1567959aa0',
  'glslang_revision': 'efa016659ffc4f2ae566b6b1db71a70655ac33a1',
  'googletest_revision': '283c17563fe7a1111cd7f581aa5d541e8baeff2f',
  're2_revision': '4a8cee3dd3c3d81b6fe8b867811e193d5819df07',
  'spirv_headers_revision': '01e0577914a75a2569c846778c2f93aa8e6feddd',
  'spirv_tools_revision': '19042c8921f35f7bec56b9e5c96c5f5691588ca8',
}

deps = {
  'third_party/abseil_cpp':
      Var('abseil_git') + '/abseil-cpp.git@' + Var('abseil_revision'),

  'third_party/effcee': Var('google_git') + '/effcee.git@' +
      Var('effcee_revision'),

  'third_party/googletest': Var('google_git') + '/googletest.git@' +
      Var('googletest_revision'),

  'third_party/glslang': Var('khronos_git') + '/glslang.git@' +
      Var('glslang_revision'),

  'third_party/re2': Var('google_git') + '/re2.git@' +
      Var('re2_revision'),

  'third_party/spirv-headers': Var('khronos_git') + '/SPIRV-Headers.git@' +
      Var('spirv_headers_revision'),

  'third_party/spirv-tools': Var('khronos_git') + '/SPIRV-Tools.git@' +
      Var('spirv_tools_revision'),
}
