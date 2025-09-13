use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': '514b52ec61609744d7e587d93a7ef9b60407ab45',
  'glslang_revision': '9d764997360b202d2ba7aaad9a401e57d8df56b3',
  'googletest_revision': '9df216cc9d6fd2f27e00e5ba1e88a502d7f278c7',
  're2_revision': '6569a9a3df256f4c0c3813cb8ee2f8eef6e2c1fb',
  'spirv_headers_revision': '01e0577914a75a2569c846778c2f93aa8e6feddd',
  'spirv_tools_revision': '745e753fd68bc59d170bb812ba3b0b1123f66fe0',
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
