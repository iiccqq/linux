"# linux" 


1.catalina.sh文件首行中添加如下语句
  JAVA_OPTS="$JAVA_OPTS -Xrunjdwp:transport=dt_socket,server=y,suspend=n,address=5005"