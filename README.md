```
	# babyname
	docker run -it --rm -v $(pwd)/babyname.yml:/secret.yml xogroup/xo-helm:preprod kubectl apply -f secret.yml
	# registry
	docker run -it --rm -v $(pwd)/registry.yml:/secret.yml xogroup/xo-helm:preprod kubectl apply -f secret.yml
```