.PATH: ${SRCTOP}/sys/arm/allwinner

KMOD=	aw_rtc
SRCS=	aw_rtc.c

SRCS+=	\
	bus_if.h \
	clknode_if.h \
	device_if.h \
	ofw_bus_if.h \
	spibus_if.h \

.include <bsd.kmod.mk>
