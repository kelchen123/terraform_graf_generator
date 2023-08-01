.PHONY: apply
apply:
	@cd jsonnet/ && \
		/root/go/bin/jb install && \
		cd ../ && \
		terraform apply -auto-approve -> output.json
