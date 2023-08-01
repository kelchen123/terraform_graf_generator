.PHONY: apply
apply:
	@cd jsonnet/ && \
		/root/go/bin/jb install && \
		cd ../ && \
		terraform apply -auto-approve 2>&1 | grep -vE "^\s*\[[0-9]+m|Changes to Outputs:" > output.json

