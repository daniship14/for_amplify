NatureTrip S3 Static Website Practice

Upload index.html and the images/ folder to the root of your S3 bucket.
Keep this structure exactly:
  index.html
  images/hero.jpg
  images/maldives.jpg
  images/switzerland.jpg
  images/bali.jpg

In the S3 bucket, enable Static website hosting and set index.html as the index document.
The site uses relative image paths (images/filename.jpg), so keep the images folder.
For practice only: making a bucket public has security implications. Do not upload secrets or private data.
