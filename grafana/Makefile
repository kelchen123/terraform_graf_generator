.PHONY: apply
apply:
	@cd jsonnet/ && \
		/root/go/bin/jb install && \
		cd ../ && \
		terraform apply > output.json
