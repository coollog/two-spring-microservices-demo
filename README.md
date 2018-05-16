`mvn package`

`mvn -pl name-service kubernetes-dev:run -Dport=80`

`mvn -pl hello-service kubernetes-dev:run -Dport=80`

`mvn -pl name-service kubernetes-dev:debug`


Add breakpoint.
Attach debugger.

Go to external ip for `hello-service`.

Step through and resume.

Change name and recompile and hot swap.

Refresh page.
