use_relative_paths = True

vars = {
  'abseil_git':  'https://github.com/abseil',
  'google_git':  'https://github.com/google',
  'khronos_git': 'https://github.com/KhronosGroup',

  'abseil_revision': '1315c900e1ddbb08a23e06eeb9a06450052ccb5e',
  'effcee_revision': '514b52ec61609744d7e587d93a7ef9b60407ab45',
  'glslang_revision': '0f2400cd75c540a2fea883d780bf752c57b35b30',
  'googletest_revision': '244cec869d12e53378fa0efb610cd4c32a454ec8',
  're2_revision': '6569a9a3df256f4c0c3813cb8ee2f8eef6e2c1fb',
  'spirv_headers_revision': 'e6d5e88c07cc66a798b668945e7fb29ec1cfee27',
  'spirv_tools_revision': 'fda5a216e9d25fa2eeda73ec8436b96e395ce5d5',
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
