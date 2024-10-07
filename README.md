# Basic web app to test session replication and sticky session in Red Hat JBoss EAP 8.x 

Usage

1- Clone project:
~~~
git clone -b ee8 https://github.com/nzhu972/counter
~~~
2- Generate war file:
~~~
mvn clean install
~~~
3- Deploy and open a browser, navigate to http://{IP}:{PORT}/counter
   Counter should increment by 1 when each JBoss instance is hit
~~~
