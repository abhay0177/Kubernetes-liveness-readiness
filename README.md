# liveness and readiness probes
linveness and readiness probes are the Health check of the container


# Liveness Probe:- This checks whether the container is alive or not. If the liveness probe fails, Kubernetes will restart the container because it assumes the container is in a bad state or has crashed. This is useful when your application might get stuck or face unresponsive states.

# Readiness Probe:- This checks whether the container is ready to handle traffic. If the readiness probe fails, Kubernetes removes the pod from the list of available pods that can receive traffic, but it doesn't restart the container.