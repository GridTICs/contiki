all: udp-client

CONTIKI = ../..
CONTIKI_WITH_IPV6 = 1
CFLAGS += -DUIP_CONF_ND6_SEND_NS=1
CFLAGS+=-DPROJECT_CONF_H=\"project-conf.h\"
include $(CONTIKI)/Makefile.include
