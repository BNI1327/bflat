## Sync Bucket content
gcloud projects list
gcloud config set project 580937940572

cd .
** Download **
gsutil -m cp -r gs://bflat.band/* .
** Upload **
gsutil cp your-file.txt gs://bflat.band