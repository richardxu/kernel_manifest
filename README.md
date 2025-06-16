# how to download
repo init -u https://github.com/richardxu/kernel_manifest.git -b oneplus/sm8750 -m oppo_find_x8_ulta.xml  --depth=1  --repo-url=https://mirrors.tuna.tsinghua.edu.cn/git/git-repo

repo sync --no-tags -c -j8

# how to build
./kernel_platform/oplus/build/oplus_build_kernel.sh sun perf
