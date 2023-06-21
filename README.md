# argocd-plugin-integration
This integration demonstrates the usage of the extended argocd vault plugin. You have two options, you can chose from api-key vs. sidecar integration
The folder api-key-integration contains all details how to setup an api-key based authentication. To create a new identity the conjur_identity.yaml can be used. 
The sidecar-integration provides all details to deploy a sidecar based plugin container to load secrets. The identity can be created by using the conjur_sidecar-identity.yaml

Both projects can then use the git_secrets.yaml file to load secrets from conjur and sync them into k8s. Different variations have been added.

# More Information:
You can find the sourcecode of the integrations in our argocd-vault-plugin repository.

If you have questions, feel free to reach out to us.
