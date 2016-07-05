# Static-youtube-loop
Autoplay and loop youtube for eternerty with a single html file.
## Introduction
As you know, Youtube doesn't have autoreplay feature build-in. It has replay button in the end and autoplay new video (by default) instead.The need for auto-replay youtube video is enormous. You can see on Youtube some Music Videos posted in 10 hours content loop, or many sites built up just to auto-replay videos.

While most of those sites are built with server-side languague like php, python. __Static-youtube-loop__ brings in the simplest solution that can help you auto-replay video with just __an HTML file__. 

## Setup
Just clone my repo

> git clone https://github.com/lequanghuylc/Static-youtube-loop

The __index.html__ file in there is all you need.
## Usage
For example I wanna auto-replay this video https://www.youtube.com/watch?v=ukigjUvwAR4

Just paste the part __?v=ukigjUvwAR4__ in the end of the URL and we're good to go.

You can use it by browsing local file (__eg: /index.html?v=ukigjUvwAR4__). But putting it in web server is the best use. Since it's just a static file, you can upload it in any static hosting (like github pages).

With web server environment, we can hide index.html in URL. The final URL is

> http://www.example.com/?v=ukigjUvwAR4

## Live Demo

> https://www.youtubereplay.xyz/?v=ukigjUvwAR4