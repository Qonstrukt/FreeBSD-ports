# Created by: Denis Shaposhnikov <dsh@vlink.ru>
# $FreeBSD$

PORTNAME=	tkXwin
PORTVERSION=	1.0
PORTREVISION=	5
CATEGORIES=	x11
MASTER_SITES=	http://beepcore-tcl.sourceforge.net/

MAINTAINER=	dsh@vlink.ru
COMMENT=	Tcl/Tk library to detect idle periods of an X session

DEPRECATED=		This port depends on Tcl/Tk 8.4 , which is no longer\
			maintained. Please port it to 8.5+
EXPIRATION_DATE=	2017-10-15

USES=		libtool tk:84,tea tar:tgz
USE_XORG=	xt xscrnsaver
USE_LDCONFIG=	yes

CONFIGURE_ENV=	INSTALL="${INSTALL_DATA}"

.include <bsd.port.mk>
