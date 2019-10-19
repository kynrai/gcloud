FROM gcr.io/cloud-builders/gcloud-slim@sha256:b2ff6703a41a9d9ae1be66cf4b9d17736afe486dff436ee876512ad5a818731a

LABEL name="gcloud-auth"
LABEL version="1.0.1"
LABEL maintainer="GitHub Actions <support+actions@github.com>"

LABEL "com.github.actions.name"="GitHub Action for Google Cloud SDK auth"
LABEL "com.github.actions.description"="Wraps the GCloud SDK to login using a service account."
LABEL "com.github.actions.icon"="log-in"
LABEL "com.github.actions.color"="green"
COPY LICENSE README.md THIRD_PARTY_NOTICE.md /

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
