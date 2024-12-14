AWS_PROFILE=personal

init:
	AWS_PROFILE=${AWS_PROFILE} terraform init \
		-backend-config=environments/dev/backend.tfvars

apply:
	AWS_PROFILE=${AWS_PROFILE} terraform apply \
		-var-file=environments/dev/terraform.tfvars	

fmt:
	terraform fmt