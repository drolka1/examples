This directory contains a simple Web Application Bundle (WAB). It can be deployed into either Jetty or Tomcat.

Instructions:
-------------

1. The repository index has not been generated for this example, this is left as an exercise. To generate the index from within posh, change to the `examples/webapp` directory and enter the command:

<pre><code>
	%index --enable-ee-spotters webapp.example . index-nim.xml
</code></pre>

Or from the O/S shell:

<pre><code>
	$posh -c "index --enable-ee-spotters webapp.example . index-nim.xml"
</code></pre>

2. In posh, ensure that either the `jetty` or `gemini-web` (i.e. Tomcat) repository is loaded:
<pre><code>
    % repos -l gemini-web
    % repos
    policy:0
    fabric:0
    fabric-ext:0
    gemini-web:0
    nimble-cmpn:1.3
    REPOPATH=*
    %
</code></pre>

3. Load the example repository:
<pre><code>
    % repos -l examples/webapp/index-nim.xml
    % repos
    webapp.example:0
    policy:0
    fabric:0
    fabric-ext:0
    gemini-web:0
    nimble-cmpn:1.3
    REPOPATH=*
    %
</code></pre>

3. Deploy the web application:

<pre><code>
	%nim:add osgi.web.app@active
</code></pre>
4. Open the web page at `http://localhost:8080/osgi-web-app` OR `http://localhost:9000/osgi-web-app` (depending on the web container and port).
