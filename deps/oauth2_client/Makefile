PROJECT = oauth2_client
PROJECT_DESCRIPTION = OAuth2 client from the RabbitMQ Project
PROJECT_MOD = oauth2_client_app

DEPS = rabbit rabbit_common
TEST_DEPS = rabbitmq_ct_helpers cowboy
LOCAL_DEPS = ssl inets crypto public_key

DEP_EARLY_PLUGINS = rabbit_common/mk/rabbitmq-early-test.mk
DEP_PLUGINS = rabbit_common/mk/rabbitmq-macros.mk \
	      rabbit_common/mk/rabbitmq-build.mk \
	      rabbit_common/mk/rabbitmq-hexpm.mk \
	      rabbit_common/mk/rabbitmq-dist.mk \
	      rabbit_common/mk/rabbitmq-run.mk \
	      rabbit_common/mk/rabbitmq-test.mk \
	      rabbit_common/mk/rabbitmq-tools.mk

include rabbitmq-components.mk
include erlang.mk
