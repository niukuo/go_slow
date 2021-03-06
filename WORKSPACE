load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "com_google_protobuf",
    sha256 = "9b4ee22c250fe31b16f1a24d61467e40780a3fbb9b91c3b65be2a376ed913a1a",
    strip_prefix = "protobuf-3.13.0",
    urls = [
        "https://github.com/protocolbuffers/protobuf/archive/v3.13.0.tar.gz",
    ],
)

load("@com_google_protobuf//:protobuf_deps.bzl", "protobuf_deps")

protobuf_deps()

http_archive(
    name = "io_bazel_rules_go",
    sha256 = "52d0a57ea12139d727883c2fef03597970b89f2cc2a05722c42d1d7d41ec065b",
    urls = [
        "https://mirror.bazel.build/github.com/bazelbuild/rules_go/releases/download/v0.24.13/rules_go-v0.24.13.tar.gz",
        "https://github.com/bazelbuild/rules_go/releases/download/v0.24.13/rules_go-v0.24.13.tar.gz",
    ],
)

load("@io_bazel_rules_go//go:deps.bzl", "go_register_toolchains", "go_rules_dependencies")

http_archive(
    name = "bazel_gazelle",
    sha256 = "222e49f034ca7a1d1231422cdb67066b885819885c356673cb1f72f748a3c9d4",
    urls = [
        "https://mirror.bazel.build/github.com/bazelbuild/bazel-gazelle/releases/download/v0.22.3/bazel-gazelle-v0.22.3.tar.gz",
        "https://github.com/bazelbuild/bazel-gazelle/releases/download/v0.22.3/bazel-gazelle-v0.22.3.tar.gz",
    ],
)

load("@bazel_gazelle//:deps.bzl", "gazelle_dependencies", "go_repository")

go_repository(
    name = "com_github_akavel_rsrc",
    importpath = "github.com/akavel/rsrc",
    sum = "h1:zjWn7ukO9Kc5Q62DOJCcxGpXC18RawVtYAGdz2aLlfw=",
    version = "v0.8.0",
)

go_repository(
    name = "com_github_certifi_gocertifi",
    importpath = "github.com/certifi/gocertifi",
    sum = "h1:6/yVvBsKeAw05IUj4AzvrxaCnDjN4nUqKjW9+w5wixg=",
    version = "v0.0.0-20180118203423-deb3ae2ef261",
)

go_repository(
    name = "com_github_cloudflare_backoff",
    importpath = "github.com/cloudflare/backoff",
    sum = "h1:8d1CEOF1xldesKds5tRG3tExBsMOgWYownMHNCsev54=",
    version = "v0.0.0-20161212185259-647f3cdfc87a",
)

go_repository(
    name = "com_github_cloudflare_cfssl",
    importpath = "github.com/cloudflare/cfssl",
    sum = "h1:vFJDAvQgFSRbCn9zg8KpSrrEZrBAQ4KO5oNK7SXEyb0=",
    version = "v1.5.0",
)

go_repository(
    name = "com_github_cloudflare_go_metrics",
    importpath = "github.com/cloudflare/go-metrics",
    sum = "h1:/8sZyuGTAU2+fYv0Sz9lBcipqX0b7i4eUl8pSStk/4g=",
    version = "v0.0.0-20151117154305-6a9aea36fb41",
)

go_repository(
    name = "com_github_cloudflare_redoctober",
    importpath = "github.com/cloudflare/redoctober",
    sum = "h1:p0Q1GvgWtVf46XpMMibupKiE7aQxPYUIb+/jLTTK2kM=",
    version = "v0.0.0-20171127175943-746a508df14c",
)

go_repository(
    name = "com_github_daaku_go_zipexe",
    importpath = "github.com/daaku/go.zipexe",
    sum = "h1:VSOgZtH418pH9L16hC/JrgSNJbbAL26pj7lmD1+CGdY=",
    version = "v1.0.0",
)

go_repository(
    name = "com_github_davecgh_go_spew",
    importpath = "github.com/davecgh/go-spew",
    sum = "h1:vj9j/u1bqnvCEfJOwUhtlOARqs3+rkHYY13jYWTU97c=",
    version = "v1.1.1",
)

go_repository(
    name = "com_github_geertjohan_go_incremental",
    importpath = "github.com/GeertJohan/go.incremental",
    sum = "h1:7AH+pY1XUgQE4Y1HcXYaMqAI0m9yrFqo/jt0CW30vsg=",
    version = "v1.0.0",
)

go_repository(
    name = "com_github_geertjohan_go_rice",
    importpath = "github.com/GeertJohan/go.rice",
    sum = "h1:KkI6O9uMaQU3VEKaj01ulavtF7o1fWT7+pk/4voiMLQ=",
    version = "v1.0.0",
)

go_repository(
    name = "com_github_getsentry_raven_go",
    importpath = "github.com/getsentry/raven-go",
    sum = "h1:ELaJ1cjF2nEJeIlHXahGme22yG7TK+3jB6IGCq0Cdrc=",
    version = "v0.0.0-20180121060056-563b81fc02b7",
)

go_repository(
    name = "com_github_go_sql_driver_mysql",
    importpath = "github.com/go-sql-driver/mysql",
    sum = "h1:7LxgVwFb2hIQtMm87NdgAVfXjnt4OePseqT1tKx+opk=",
    version = "v1.4.0",
)

go_repository(
    name = "com_github_golang_protobuf",
    importpath = "github.com/golang/protobuf",
    sum = "h1:YF8+flBXS5eO826T4nzqPrxfhQThhXl0YzfuUPu4SBg=",
    version = "v1.3.1",
)

go_repository(
    name = "com_github_google_certificate_transparency_go",
    importpath = "github.com/google/certificate-transparency-go",
    sum = "h1:Yf1aXowfZ2nuboBsg7iYGLmwsOARdV86pfH3g95wXmE=",
    version = "v1.0.21",
)

go_repository(
    name = "com_github_jessevdk_go_flags",
    importpath = "github.com/jessevdk/go-flags",
    sum = "h1:4IU2WS7AumrZ/40jfhf4QVDMsQwqA7VEHozFRrGARJA=",
    version = "v1.4.0",
)

go_repository(
    name = "com_github_jmhodges_clock",
    importpath = "github.com/jmhodges/clock",
    sum = "h1:dYTbLf4m0a5u0KLmPfB6mgxbcV7588bOCx79hxa5Sr4=",
    version = "v0.0.0-20160418191101-880ee4c33548",
)

go_repository(
    name = "com_github_jmoiron_sqlx",
    importpath = "github.com/jmoiron/sqlx",
    sum = "h1:41Ip0zITnmWNR/vHV+S4m+VoUivnWY5E4OJfLZjCJMA=",
    version = "v1.2.0",
)

go_repository(
    name = "com_github_kisielk_sqlstruct",
    importpath = "github.com/kisielk/sqlstruct",
    sum = "h1:o/c0aWEP/m6n61xlYW2QP4t9424qlJOsxugn5Zds2Rg=",
    version = "v0.0.0-20150923205031-648daed35d49",
)

go_repository(
    name = "com_github_kisom_goutils",
    importpath = "github.com/kisom/goutils",
    sum = "h1:z4HEOgAnFq+e1+O4QdVsyDPatJDu5Ei/7w7DRbYjsIA=",
    version = "v1.1.0",
)

go_repository(
    name = "com_github_konsorten_go_windows_terminal_sequences",
    importpath = "github.com/konsorten/go-windows-terminal-sequences",
    sum = "h1:mweAR1A6xJ3oS2pRaGiHgQ4OO8tzTaLawm8vnODuwDk=",
    version = "v1.0.1",
)

go_repository(
    name = "com_github_kr_pretty",
    importpath = "github.com/kr/pretty",
    sum = "h1:L/CwN0zerZDmRFUapSPitk6f+Q3+0za1rQkzVuMiMFI=",
    version = "v0.1.0",
)

go_repository(
    name = "com_github_kr_pty",
    importpath = "github.com/kr/pty",
    sum = "h1:VkoXIwSboBpnk99O/KFauAEILuNHv5DVFKZMBN/gUgw=",
    version = "v1.1.1",
)

go_repository(
    name = "com_github_kr_text",
    importpath = "github.com/kr/text",
    sum = "h1:45sCR5RtlFHMR4UwH9sdQ5TC8v0qDQCHnXt+kaKSTVE=",
    version = "v0.1.0",
)

go_repository(
    name = "com_github_kylelemons_go_gypsy",
    importpath = "github.com/kylelemons/go-gypsy",
    sum = "h1:mkl3tvPHIuPaWsLtmHTybJeoVEW7cbePK73Ir8VtruA=",
    version = "v0.0.0-20160905020020-08cad365cd28",
)

go_repository(
    name = "com_github_lib_pq",
    importpath = "github.com/lib/pq",
    sum = "h1:/qkRGz8zljWiDcFvgpwUpwIAPu3r07TDvs3Rws+o/pU=",
    version = "v1.3.0",
)

go_repository(
    name = "com_github_mattn_go_sqlite3",
    importpath = "github.com/mattn/go-sqlite3",
    sum = "h1:jbhqpg7tQe4SupckyijYiy0mJJ/pRyHvXf7JdWK860o=",
    version = "v1.10.0",
)

go_repository(
    name = "com_github_mreiferson_go_httpclient",
    importpath = "github.com/mreiferson/go-httpclient",
    sum = "h1:oKIteTqeSpenyTrOVj5zkiyCaflLa8B+CD0324otT+o=",
    version = "v0.0.0-20160630210159-31f0106b4474",
)

go_repository(
    name = "com_github_nkovacs_streamquote",
    importpath = "github.com/nkovacs/streamquote",
    sum = "h1:E2B8qYyeSgv5MXpmzZXRNp8IAQ4vjxIjhpAf5hv/tAg=",
    version = "v0.0.0-20170412213628-49af9bddb229",
)

go_repository(
    name = "com_github_op_go_logging",
    importpath = "github.com/op/go-logging",
    sum = "h1:lDH9UUVJtmYCjyT0CI4q8xvlXPxeZ0gYCVvWbmPlp88=",
    version = "v0.0.0-20160315200505-970db520ece7",
)

go_repository(
    name = "com_github_pkg_errors",
    importpath = "github.com/pkg/errors",
    sum = "h1:WdK/asTD0HN+q6hsWO3/vpuAkAr+tw6aNJNDFFf0+qw=",
    version = "v0.8.0",
)

go_repository(
    name = "com_github_pmezard_go_difflib",
    importpath = "github.com/pmezard/go-difflib",
    sum = "h1:4DBwDE0NGyQoBHbLQYPwSUPoCMWR5BEzIk/f1lZbAQM=",
    version = "v1.0.0",
)

go_repository(
    name = "com_github_sirupsen_logrus",
    importpath = "github.com/sirupsen/logrus",
    sum = "h1:hI/7Q+DtNZ2kINb6qt/lS+IyXnHQe9e90POfeewL/ME=",
    version = "v1.3.0",
)

go_repository(
    name = "com_github_stretchr_objx",
    importpath = "github.com/stretchr/objx",
    sum = "h1:2vfRuCMp5sSVIDSqO8oNnWJq7mPa6KVP3iPIwFBuy8A=",
    version = "v0.1.1",
)

go_repository(
    name = "com_github_stretchr_testify",
    importpath = "github.com/stretchr/testify",
    sum = "h1:2E4SXV/wtOkTonXsotYi4li6zVWxYlZuYNCXe9XRJyk=",
    version = "v1.4.0",
)

go_repository(
    name = "com_github_valyala_bytebufferpool",
    importpath = "github.com/valyala/bytebufferpool",
    sum = "h1:GqA5TC/0021Y/b9FG4Oi9Mr3q7XYx6KllzawFIhcdPw=",
    version = "v1.0.0",
)

go_repository(
    name = "com_github_valyala_fasttemplate",
    importpath = "github.com/valyala/fasttemplate",
    sum = "h1:tY9CJiPnMXf1ERmG2EyK7gNUd+c6RKGD0IfU8WdUSz8=",
    version = "v1.0.1",
)

go_repository(
    name = "com_github_weppos_publicsuffix_go",
    importpath = "github.com/weppos/publicsuffix-go",
    sum = "h1:0Tu1uzLBd1jPn4k6OnMmOPZH/l/9bj9kUOMMkoRs6Gg=",
    version = "v0.13.0",
)

go_repository(
    name = "com_github_ziutek_mymysql",
    importpath = "github.com/ziutek/mymysql",
    sum = "h1:GB0qdRGsTwQSBVYuVShFBKaXSnSnYYC2d9knnE1LHFs=",
    version = "v1.5.4",
)

go_repository(
    name = "com_github_zmap_rc2",
    importpath = "github.com/zmap/rc2",
    sum = "h1:kKCF7VX/wTmdg2ZjEaqlq99Bjsoiz7vH6sFniF/vI4M=",
    version = "v0.0.0-20131011165748-24b9757f5521",
)

go_repository(
    name = "com_github_zmap_zcertificate",
    importpath = "github.com/zmap/zcertificate",
    sum = "h1:17HHAgFKlLcZsDOjBOUrd5hDihb1ggf+1a5dTbkgkIY=",
    version = "v0.0.0-20180516150559-0e3d58b1bac4",
)

go_repository(
    name = "com_github_zmap_zcrypto",
    importpath = "github.com/zmap/zcrypto",
    sum = "h1:PIpcdSOg3pMdFJUBg5yR9xxcj5rm/SGAyaWT/wK6Kco=",
    version = "v0.0.0-20200911161511-43ff0ea04f21",
)

go_repository(
    name = "com_github_zmap_zlint_v2",
    importpath = "github.com/zmap/zlint/v2",
    sum = "h1:b2kI/ToXX16h2wjV2c6Da65eT6aTMtkLHKetXuM9EtI=",
    version = "v2.2.1",
)

go_repository(
    name = "in_gopkg_check_v1",
    importpath = "gopkg.in/check.v1",
    sum = "h1:qIbj1fsPNlZgppZ+VLlY7N33q108Sa+fhmuc+sWQYwY=",
    version = "v1.0.0-20180628173108-788fd7840127",
)

go_repository(
    name = "in_gopkg_yaml_v2",
    importpath = "gopkg.in/yaml.v2",
    sum = "h1:ZCJp+EgiOT7lHqUV2J862kp8Qj64Jo6az82+3Td9dZw=",
    version = "v2.2.2",
)

go_repository(
    name = "org_bitbucket_liamstask_goose",
    importpath = "bitbucket.org/liamstask/goose",
    sum = "h1:bkb2NMGo3/Du52wvYj9Whth5KZfMV6d3O0Vbr3nz/UE=",
    version = "v0.0.0-20150115234039-8488cc47d90c",
)

go_repository(
    name = "org_golang_google_appengine",
    importpath = "google.golang.org/appengine",
    sum = "h1:lMO5rYAqUxkmaj76jAkRUvt5JZgFymx/+Q5Mzfivuhc=",
    version = "v1.6.6",
)

go_repository(
    name = "org_golang_x_crypto",
    importpath = "golang.org/x/crypto",
    sum = "h1:4yd7jl+vXjalO5ztz6Vc1VADv+S/80LGJmyl1ROJ2AI=",
    version = "v0.0.0-20201012173705-84dcc777aaee",
)

go_repository(
    name = "org_golang_x_lint",
    importpath = "golang.org/x/lint",
    sum = "h1:5hukYrvBGR8/eNkX5mdUezrA6JiaEZDtJb9Ei+1LlBs=",
    version = "v0.0.0-20190930215403-16217165b5de",
)

go_repository(
    name = "org_golang_x_net",
    importpath = "golang.org/x/net",
    sum = "h1:mUVeFHoDKis5nxCAzoAi7E8Ghb86EXh/RK6wtvJIqRY=",
    version = "v0.0.0-20201010224723-4f7140c49acb",
)

go_repository(
    name = "org_golang_x_sys",
    importpath = "golang.org/x/sys",
    sum = "h1:+Nyd8tzPX9R7BWHguqsrbFdRx3WQ/1ib8I44HXV5yTA=",
    version = "v0.0.0-20200930185726-fdedc70b468f",
)

go_repository(
    name = "org_golang_x_text",
    importpath = "golang.org/x/text",
    sum = "h1:cokOdA+Jmi5PJGXLlLllQSgYigAEfHXJAERHVMaCc2k=",
    version = "v0.3.3",
)

go_repository(
    name = "org_golang_x_tools",
    importpath = "golang.org/x/tools",
    sum = "h1:/e+gpKk9r3dJobndpTytxS2gOy6m5uvpg+ISQoEcusQ=",
    version = "v0.0.0-20190311212946-11955173bddd",
)

go_rules_dependencies()

go_register_toolchains()

gazelle_dependencies()
