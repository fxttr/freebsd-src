.PATH: ${SRCTOP}/sys/geom/label

KMOD=	geom_label
SRCS=	g_label.c
SRCS+=	g_label_disk_ident.c
SRCS+=	g_label_ext2fs.c
SRCS+=	g_label_flashmap.c
SRCS+=	g_label_gpt.c
SRCS+=	g_label_iso9660.c
SRCS+=	g_label_msdosfs.c
SRCS+=	g_label_ntfs.c
SRCS+=	g_label_ufs.c
SRCS+=	g_label_swaplinux.c
SRCS+=	opt_geom.h
SRCS+=	vnode_if.h

opt_geom.h:
	echo "#define GEOM_LABEL 1" > ${.TARGET}

.include <bsd.kmod.mk>
