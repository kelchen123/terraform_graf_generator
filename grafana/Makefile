.PHONY: apply
apply:
	@cd jsonnet/ && \
		/root/go/bin/jb install && \
		cd ../ && \
		terraform plan --no-color -out=tfplan && terraform apply --no-color tfplan --auto-approve > output.json



