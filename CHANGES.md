# Changes and TODO


## ????-????-?? / ?.?.?

* [TODO] First class Ring support (co-existing Clojure/Other webapp)
* [TODO] JNDI DataSource configuration
* [TODO] Support servlet filters :filters
* [TODO] Support servlet listeners :listeners
* [TODO] Template for SpringMVC
* [TODO] Template for Struts2
* [TODO] Template for Jython/modjy/WSGI/flask/jinja2
* [TODO] Template for Ruby/jrack/Sinatra


## 2014-March-22 / 0.4.0

* Servlet-engine adapters:
  * Jetty 7.6.14.v20131031 `lein-servlet/adapter-jetty7`
  * Jetty 8.1.14.v20131031 `lein-servlet/adapter-jetty8`
  * Jetty 9.1.3.v20140225  `lein-servlet/adapter-jetty9`
  * Tomcat 7.0.52 `lein-servlet/adapter-tomcat7`
  * Tomcat 8.0.3 `lein-servlet/adapter-tomcat8` (new adapter)
* Plugin `lein-servlet`
  * No change
* Templates: `lein-servlet/lein-template`
  * Use plugin version 0.4.0 everywhere
  * Update Quercus template to use Resin 4.0.30
  * Update Railo template to use Railo 4.3.0
  * Fix AOT compile issue in Struts template
  * Fix deprecated Leiningen keys in `project.clj`


## 2013-June-02 / 0.3.0

* Servlet-engine adapters:
  * Jetty 7.6.11.v20130520 `lein-servlet/adapter-jetty7` `0.3.0`
  * Jetty 8.1.11.v20130520 `lein-servlet/adapter-jetty8` `0.3.0`
  * Jetty 9.0.3.v20130506  `lein-servlet/adapter-jetty9` `0.3.0` (new)
  * Tomcat 7.0.40 `lein-servlet/adapter-tomcat7` `0.3.0`
* Plugin `lein-servlet` `0.3.0`
  * No change
* Templates: `lein-servlet/lein-template` `0.3.0`
  * Fix Railo template for idiomatic use (by Sean Corfield)
  * Update Railo template to use Railo 4.2.0
  * Update Struts-1 template to use Struts 1.3.10
  * Point to plugin version `0.3.0`


## 2012-July-20 / 0.2.0

* Servlet-engine adapters:
  * Jetty 7.6.4.v20120524 `lein-servlet/adapter-jetty7` `0.2.0`
  * Jetty 8.1.4.v20120524 `lein-servlet/adapter-jetty8` `0.2.0`
  * Tomcat 7.0.29 `lein-servlet/adapter-tomcat7` `0.2.0`
* Plugin `lein-servlet` `0.2.0`
  * Support :war-exclusions and :uberwar-exclusions under :servlet
  * Rename :classes to :servlets
  * Handle servlet init params in adapters and auto-generated web.xml (WAR file)
  * Generate WAR file for webapp from provided/auto-generated web.xml
* Templates: `lein-servlet/lein-template` `0.2.0`
  * Point to plugin version `0.2.0`


## 2012-June-17 / 0.1.0

* Servlet-engine adapters:
  * Jetty 7.6.3.v20120416 `lein-servlet/adapter-jetty7` `0.1.0`
  * Jetty 8.1.3.v20120416 `lein-servlet/adapter-jetty8` `0.1.0`
  * Tomcat 7.0.27 `lein-servlet/adapter-tomcat7` `0.1.0`
* Plugin `lein-servlet` `0.1.0`
  * Configuration support for
    * Servlet classes
    * Web descriptor `web.xml`
  * SSL support
  * JSP support
  * Display info on loaded-engines: `lein servlet engine`
  * Run webapp in interactive mode: `lein servlet run`
* Templates: `lein-servlet/lein-template` `0.1.0`
  * Clojure webapp based on servlet
  * Clojure/Java webapp based on Struts `1.2.9`
  * Clojure/PHP webapp based on Quercus `4.0.28`
  * Clojure/CFML webapp based on Railo `3.1.000`

