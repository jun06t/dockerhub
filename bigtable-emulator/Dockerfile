FROM gcr.io/google.com/cloudsdktool/google-cloud-cli:alpine

RUN gcloud components install beta bigtable

EXPOSE 8086

CMD ["gcloud", "beta", "emulators", "bigtable", "start", "--host-port=0.0.0.0:8086"]
