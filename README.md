# RemoteIpFilter
A Servlet remote ip Filter. Most code here is copied from `org.apache.catalina.filters.RemoteIpFilter`, except that we use
 ip subnet/mask to match ip address instead of regex in `org.apache.catalina.filters.RemoteIpFilter`. This makes ip subnet configuration much easier.
