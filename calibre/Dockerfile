FROM aptalca/docker-rdp-calibre
LABEL org.freenas.interactive="false" 		\
      org.freenas.version="2.82"		\
      org.freenas.upgradeable="true"		\
      org.freenas.expose-ports-at-host="true"	\
      org.freenas.autostart="true"		\
      org.freenas.web-ui-protocol="http"	\
      org.freenas.web-ui-port=8080		\
      org.freenas.web-ui-path="/#/client/c/Calibre"		\
      org.freenas.port-mappings="8080:8080/tcp,8081:8081/tcp"	\
      org.freenas.volumes="[					\
          {							\
              \"name\": \"/config\",				\
              \"descr\": \"Storage: rw\"			\
          },							\
	  {							\
              \"name\": \"/etc/localtime\",			\
              \"descr\": \"Localtime: ro\"			\
          }							\
      ]"							\
      org.freenas.settings="[ 					\
          {							\
              \"env\": \"EDGE\",				\
              \"descr\": \"Update calibre when restarted\",	\
              \"optional\": true				\
          },							\
          {							\
              \"env\": \"WIDTH\",     				\
              \"descr\": \"GUI resolution: width\",		\
              \"optional\": true				\
          },							\
          {							\
              \"env\": \"HEIGHT\",				\
              \"descr\": \"GUI resolution: height\",		\
              \"optional\": true				\
          },							\
          {							\
              \"env\": \"LIBRARYINTERNALPATH\",			\
              \"descr\": \"Internal library location\",		\
              \"optional\": true				\
          },							\
          {							\
              \"env\": \"URLPREFIX\",				\
              \"descr\": \"Url prefix\",			\
              \"optional\": true				\
          }							\
      ]"
