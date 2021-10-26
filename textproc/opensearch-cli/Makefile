PORTNAME=	opensearch-cli
DISTVERSION=	1.1.0
CATEGORIES=	textproc
MASTER_SITES=	#

MAINTAINER=	y@trombik.org
COMMENT=	Command line interface for OpenSearch

LICENSE=	APACHE20
LICENSE_FILE=	${WRKSRC}/LICENSE

USES=	go:modules gmake

USE_GITHUB=	yes
GH_TUPLE=	opensearch-project:${PORTNAME}:v${DISTVERSION}
GH_TUPLE+=	\
		VividCortex:ewma:v1.1.1:vividcortex_ewma/vendor/github.com/VividCortex/ewma \
		aws:aws-sdk-go:v1.37.25:aws_aws_sdk_go/vendor/github.com/aws/aws-sdk-go \
		cheggaaa:pb:v3.0.5:cheggaaa_pb/vendor/github.com/cheggaaa/pb \
		davecgh:go-spew:v1.1.1:davecgh_go_spew/vendor/github.com/davecgh/go-spew \
		fatih:color:v1.7.0:fatih_color/vendor/github.com/fatih/color \
		go-yaml:yaml:eeeca48fe776:go_yaml_yaml/vendor/gopkg.in/yaml.v3 \
		go-yaml:yaml:v2.2.8:go_yaml_yaml_1/vendor/gopkg.in/yaml.v2 \
		golang:mock:v1.4.4:golang_mock/vendor/github.com/golang/mock \
		golang:sys:f84b799fce68:golang_sys/vendor/golang.org/x/sys \
		golang:term:2321bbc49cbf:golang_term/vendor/golang.org/x/term \
		hashicorp:go-cleanhttp:v0.5.1:hashicorp_go_cleanhttp/vendor/github.com/hashicorp/go-cleanhttp \
		hashicorp:go-retryablehttp:v0.6.7:hashicorp_go_retryablehttp/vendor/github.com/hashicorp/go-retryablehttp \
		inconshreveable:mousetrap:v1.0.0:inconshreveable_mousetrap/vendor/github.com/inconshreveable/mousetrap \
		jmespath:go-jmespath:v0.4.0:jmespath_go_jmespath/vendor/github.com/jmespath/go-jmespath \
		mattn:go-colorable:v0.1.2:mattn_go_colorable/vendor/github.com/mattn/go-colorable \
		mattn:go-isatty:v0.0.12:mattn_go_isatty/vendor/github.com/mattn/go-isatty \
		mattn:go-runewidth:v0.0.7:mattn_go_runewidth/vendor/github.com/mattn/go-runewidth \
		pmezard:go-difflib:v1.0.0:pmezard_go_difflib/vendor/github.com/pmezard/go-difflib \
		spf13:cobra:v1.1.1:spf13_cobra/vendor/github.com/spf13/cobra \
		spf13:pflag:v1.0.5:spf13_pflag/vendor/github.com/spf13/pflag \
		stretchr:testify:v1.6.1:stretchr_testify/vendor/github.com/stretchr/testify

.include <bsd.port.mk>
