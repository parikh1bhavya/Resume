## Resume 
It makes use of the latex template and docker to create a pdf resume. It  is easy to keep track of and to modify.

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex bhavya_parikh_resume.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)

### License

Format is MIT and the template is owned by Sourabh Bajaj. But data in the template is owned by Bhavya Parikh.
