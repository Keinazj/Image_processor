# ImageProcessor

In this project, you can read an image from a file on your device, from the internet using a URL or you can email an image to it.

after reading the image, there are some filters you can apply on it and save the edited photo.

---

The image formats supported:

- jpg
- bmp
- png

---

libraries used in this project:

- stb_library
- libcurl
- openssl
- b64

---

command to build and run the project:

gcc name.c bmp.c filters.c url_function.c email2_test.c b64/libb64-master/include/b64/cdecode.c -o name -lssl -lcrypto -lm -lcurl
