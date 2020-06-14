---
layout: post
title: 'Nurture The Essence'
---
My friend and Qi Gong instructor Stephen Schleipfer had this idea for a web app where accupuncturists could recommend medical Qi Gong videos for their patients to use. We spoke with several other accupuncturists who thought this was a really good idea - there are a lot of great medical Qi Gong exercises, but most accupuncturists don't have time to demonstrate them to their patients.

If you have a provider account you can refer patients to specific video sets on the site. Patients receive an email to sign up, and they will see the videos under "My Practice" along with a note the provider has added. Additionally, anyone can find a video set under the "Explore" section and it will appear under "My Practice".There is a CMS in the site for uploading and editing videos and video sets, as well as managing users.

I designed and created this app working part time, starting in late 2019 and finishing up with the technical side of things in 2020.

I used tools that I am very comfortable with: Typescript, Nodejs, React, Apollo, GraphQL, Heroku, and AWS. I created a pipeline to host and stream HLS encrypted videos from AWS but that ended up being fairly expensive in terms of encoding so we ended up using Vimeo. For the backend I used NestJS and TypeORM, which was new to me and was actually pretty great. The TypeScript-from-the-ground-up approach made it feel like I was working on something much more safe than a typical Node app.

Overall this project took a lot of time and I haven't made any money on it so far, but it will hopefully start making money in the future and it was pretty awesome to work on it either way. We are taking it slow and steady and look at it as a long term side project for both of us. We are shooting videos on the weekend and we have a few accupuncture clinics lined up to start testing it.

If you are thinking about hiring me and would like to see a code sample, I would be happy to share some of the code used on this website with you. 

{% include image.html url="http://www.nurturetheessence.com" image="projects/proj-1/desktop.png" %}

{% include image.html url="http://www.nurturetheessence.com" image="projects/proj-1/mobile.png" %}

{% include image.html url="http://www.nurturetheessence.com" image="projects/proj-1/referrals.png" %}

{% include image.html url="http://www.nurturetheessence.com" image="projects/proj-1/admin.png" %}
