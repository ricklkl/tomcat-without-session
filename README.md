# tomcat-without-session
Make tomcat not create session when HttpReqest comes in, so we have a sessionless service and save many memory resource by this.

Steps:
`1，clone or download this project.`
`2，expert a jar package with your IDE.`
`3，copy the jar to ${tomcat}/lib`
`4，edit ${tomcat}/conf/context.xml,modify <Manager className="com.nosession.SessionManager" /> like the context.xml in our project`