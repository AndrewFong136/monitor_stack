# monitor_stack

Add files in ./alloy to /etc/alloy
systemctl restart alloy

Add to /etc/default/alloy:
CUSTOM_ARGS="--server.http.listen-addr=0.0.0.0:12345"
