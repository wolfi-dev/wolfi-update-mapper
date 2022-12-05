| package name | identifier | release service | notes |
| ------------ | ----------- |--------------- | ----- |
|acl|16|https://release-monitoring.org||
|alsa-lib|38|||
|apk-tools|20466|||
|attr|137|||
|autoconf|141|||
|automake|144|||
|bash|166|||
|bazel-5|15227||SKIP bazel - 5 version stream|
|binutils|7981|||
|bison|193|||
|brotli|15235|||
|bubblewrap|10937|||
|busybox|230|||
|bzip2|237|||
|c-ares|5840|||
|ca-certificates|9026|||
|check|7593|||
|clang-15|11811||SKIP clang - 15 version stream|
|cmake|306||SKIP - includes subset of the version in the melange fetch URL|
|coreutils|343|||
|cosign|||SKIP UNKNOWN|
|crane|||SKIP UNKNOWN|
|cups|380|||
|curl|381|||
|dbus|5356|||
|diffutils|436|||
|dumb-init|11582|||
|encodings|15051|||
|envoy|||SKIP UNKNOWN|
|execline|5482|||
|expat|770|||
|file|807|||
|findutils|812|||
|flex|819|||
|font-util|15055||name=xorg-font-util|
|fontconfig|827|||
|freetype|854|||
|gawk|868|||
|gcc|6502|||
|gdbm|882|||
|giflib|1158|||
|git-lfs|11551|||
|git|5350||includes release candidates e.g. 2.39.0-rc0|
|glibc|5401||includes Pre-release 9000 https://release-monitoring.org/project/5401/|
|gmp|1186|||
|go-bindata||| SKIP UNKNOWN|
|go|1227|||
|gperf|1237|||
|grep|1251|||
|grype|||SKIP UNKNOWN|
|gzip|1290|||
|help2man|1309|||
|icu|16134||SKIP uses unusual version format|
|isl|13286|||
|jenkins|||SKIP UNKNOWN|
|jq|13252|||
|kubectl|||SKIP UNKNOWN|
|lcms|1542|||
|libarchive|1558|||
|libbsd|1567|||
|libcap|||SKIP double check as we have a very old version if they are the same package https://release-monitoring.org/project/1569/|
|libedit|1599||SKIP check as they include the date in the version but we have it hard coded in melange config|
|libev|1605|||
|libevent|1606|||
|libffi|1611|||
|libfontenc|1613|||
|libgcrypt|1623|||
|libgpg-error|1628|||
|libice|1638|||
|libjpeg|1648|||
|libmd|15525|||
|libpaper|15136|||
|libpng|1705|||
|libpthread-stubs|13519|||
|libretls|148759|||
|libsm|1726|||
|libtool|1741|||
|libusb|1749|||
|libuv|10784|||
|libx11|1764|||
|libxau|1765|||
|libxcb|1767|||
|libxdmcp|1772|||
|libxext|1774|||
|libxfixes|1775|||
|libxi|1778|||
|libxml2|1783|||
|libxrandr|1788|||
|libxrender|1789|||
|libxslt|13301|||
|libxt|1793|||
|libxtst|1794|||
|linenoise|5691|||
|linux-headers|6501|||
|llvm-libunwind|1830||the mono LLVM repo|
|llvm-lld|1830||the mono LLVM repo|
|llvm15|1830||the mono LLVM repo|
|lua5.3-lzlib|21513|||
|lua5.3|||SKIP check this https://release-monitoring.org/projects/search/?pattern=lua5|
|lz4|1865|||
|m4|1871|||
|make|1877|||
|maven|1894|||
|meson|6472|||
|mkfontscale|15043|||
|mpc|1667|||
|mpdecimal|11578|||
|mpfr|2019|||
|ncurses|2057||SKIP check melange config as fetch URL includes the date https://release-monitoring.org/project/2057/|
|nghttp2|8651|||
|nodejs|||SKIP double check do we want to track latest or LTS? https://release-monitoring.org/projects/search/?pattern=nodejs|
|oniguruma|11184|||
|openjdk-11|||SKIP check this - we might want to monitor patch versions which release monitor seems to not https://release-monitoring.org/projects/search/?pattern=openjdk|
|openjdk-17|||SKIP check this - we might want to monitor patch versions which release monitor seems to not https://release-monitoring.org/projects/search/?pattern=openjdk|
|openssh|2565|||
|openssl|2566|||
|patch|2597|||
|pax-utils|2601||SKIP - latest version has changed URL|
|pcre2|5832|||
|perl-test-pod|3410|||
|perl-yaml-syck|11926|||
|perl|13599|||
|pkgconf|12753|||
|popt|3689|||
|postgresql-11|5601||SKIP check version stream https://release-monitoring.org/project/5601/|
|postgresql-12|5601||SKIP check version stream https://release-monitoring.org/project/5601/|
|postgresql-13|5601||SKIP check version stream https://release-monitoring.org/project/5601/|
|postgresql-14|5601||SKIP check version stream https://release-monitoring.org/project/5601/|
|postgresql-15|5601||SKIP check version stream https://release-monitoring.org/project/5601/|
|procps|3708|||
|py3-appdirs|6278|||
|py3-contextlib2|6215|||
|py3-flit-core|44841|||
|py3-gpep517|255912|||
|py3-installer|197662|||
|py3-jinja2|3894|||
|py3-markupsafe|3918|||
|py3-more-itertools|12201|||
|py3-ordered-set|7433|||
|py3-packaging|11718|||
|py3-parsing|3756|||
|py3-pep517|47623|||
|py3-pip|6529|||
|py3-retrying|13217|||
|py3-setuptools-stage0|||SKIP stage 0?|
|py3-setuptools|4021||SKIP # NOTE: Be very careful when upgrading this package as upstream aggressively deprecates functionality used by packages in production|
|py3-six|4027|||
|py3-tomli|207408|||
|python3|13254|||
|readline|4173|||
|regclient|||SKIP UNKNOWN|
|rhash|13843|||
|rsync|4217|||
|ruby-3.0|4223||SKIP version stream|
|ruby-3.1|4223||SKIP version stream|
|rust-stage0|||SKIP stage 0|
|s6|5485|||
|samurai|96779|||
|scdoc|68662|||
|sed|4789|||
|skalibs|5486|||
|skopeo|9216|||
|sqlite|4877|||
|su-exec|||SKIP UNKNOWN|
|texinfo|4958|||
|tini|13826|||
|tree|5006|||
|trivy|141362|||
|ttf-dejavu|418||SKIP check format of version|
|tzdata|5021|||
|util-macros|5252|||
|wget|5124|||
|xcb-proto|13646|||
|xmlto|13307|||
|xorgproto|17190|||
|xtrans|13440|||
|xz|5277||SKIP - redirects issue|
|zip|10080|||
|zlib|5303|||
|zstd|12083|||
|http-parser|10989|||
|libgit2|1627|||
|libssh2|1730|||
|wasi-libc|||SKIP UNKNOWN|