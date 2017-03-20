FROM sameersbn/bind:9.9.5-20170129
LABEL org.freenas.interactive="false" 		\
      org.freenas.version="9.9.5-20170129"		\
      org.freenas.upgradeable="true"		\
      org.freenas.expose-ports-at-host="true"	\
      org.freenas.autostart="true"		\
      org.freenas.capabilities-add="NET_BROADCAST" \
      org.freenas.web-ui-protocol="http"	\
      org.freenas.web-ui-port=10000		\
      org.freenas.web-ui-path="web"		\
      org.freenas.port-mappings="53:53/tcp,53:53/udp,10000:10000/tcp"			\
      org.freenas.volumes="[					\
          {							\
              \"name\": \"/data\",				\
              \"descr\": \"Data storage space\"		\
          }							\
      ]"
