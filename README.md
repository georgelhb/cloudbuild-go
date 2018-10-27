#### The code shows how to use Cloud Build to build a Go binary and push the binary to Google Cloud Storage.
---
1) You'll need a Google Cloud Storage bucket to push the Go binary after you build it. <br/>
2) Replace the [BUCKET_NAME] in cloudbuild.yaml. <br/>
3) Start the build by running the gcloud builds submit command: <br/>
```
gcloud builds submit --config cloudbuild.yaml .
```
4) You've just built the Go binary using the build config file and stored the binary in the Cloud Storage bucket.
