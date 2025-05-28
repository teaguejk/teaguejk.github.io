---
layout: post
title:  "Birdhouse"
date:   2022-04-06 11:56:46 -0500
categories: jekyll update
---
This was my capstone project during my senior year at Appalachian State University. I designed and built a smart birdhouse capable of detecting motion and capturing images and videos of visiting birds.

The project involved building a birdhouse from scratch and integrating it with a Raspberry Pi Zero equipped with a GPIO motion sensor and NoIR camera, making use of a waterproof container. I developed a Python script to automatically capture images whenever motion was detected, send out emails to anyone who signed up for the mailing list, and then finally upload them to my schools student server for later use and display.

For displaying the captured images I built:

1. a basic web interface -- which I am now revisting using the skills I have gained since then. This included an email form for signing up for bird notifications.
2. automatic emails on motion detected, including the image
3. a discord bot

The system features a web interface for viewing collected media and automatically sends email notifications with attached photos to a mailing list whenever a bird is detected.

This project was super fun and taught me a lot about hardware integration, Python programming, web development, and automation. Working with the Raspberry Pi Zero gave me hands-on experience with GPIO sensors and camera modules, while developing the email notification system taught me about SMTP protocols and mailing list management. I also learned how to make birdhoues from scratch, and weatherproofing electronics so I can try this again one day soon!
