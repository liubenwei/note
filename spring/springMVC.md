## SpringMVC

​	1、随时随地获取httpRequest：

>1. HttpServletRequest request = ((ServletRequestAttributes) RequestContextHolder.getRequestAttributes()).getRequest(); 