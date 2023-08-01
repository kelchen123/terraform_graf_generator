.PHONY: apply
apply:
	@cd jsonnet/ && \
		/root/go/bin/jb install && \
		cd ../ && \
		terraform apply -auto-approve 2>&1 | grep -v '[0m\|[32m+' > output.json


