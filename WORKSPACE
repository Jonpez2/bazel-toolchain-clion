load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
  name = 'org_linaro_components_toolchain_gcc_5_3_1',
  build_file = '@//:compilers/linaro_linux_gcc_5.3.1.BUILD',
  url = 'https://bazel-mirror.storage.googleapis.com/releases.linaro.org/components/toolchain/binaries/latest-5/arm-linux-gnueabihf/gcc-linaro-5.3.1-2016.05-x86_64_arm-linux-gnueabihf.tar.xz',
  strip_prefix = 'gcc-linaro-5.3.1-2016.05-x86_64_arm-linux-gnueabihf',
)

register_toolchains(
    "//tools/arm_compiler:cc-toolchain-armeabi-v7a",
    "//tools/arm_compiler:cc-toolchain-k8"
)