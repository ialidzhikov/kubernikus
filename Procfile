operator: env NODEPOOL_AFFINITY=true bin/$(go env GOOS)/kubernikus operator --auth-username=$KS_USERNAME --auth-domain=$KS_USER_DOMAIN_NAME --auth-password="$KS_PASSWORD" --auth-project=$KS_PROJECT_NAME --auth-project-domain=$KS_PROJECT_DOMAIN_NAME --auth-url=$KS_AUTH_URL --namespace=$KS_NAMESPACE --context=$KS_CONTEXT --kubernikus-domain=$KS_DOMAIN --v=5
api: bin/$(go env GOOS)/apiserver --context=$KS_CONTEXT --namespace=$KS_NAMESPACE --auth-url=$KS_AUTH_URL --images-file=charts/images.yaml --v=5
