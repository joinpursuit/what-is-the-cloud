# What is cloud computing?

We talk about the cloud all the time. Things are stored there, uploaded there, processed there, and more. But what is the cloud?

The short answer is this:

![sss](https://miro.medium.com/max/325/1*el4nHcOQdfHxzzcTC99jDw.png)

For the longer, more helpful answer, read on.

## Why use the cloud?

In the old days, you installed software on your computer, and it ran on your computer, and that was it. The old Atari video game cartridges were examples of that. Even today there is still software that basically lives and runs only on your computer, for example a lot of photo and video editing programs.

With this type of software, how well it works depends on your computer. If your computer is fast and has lots of memory and storage, then you can do lots of things with these programs. If your computer is slow or low on memory and storage, you can't do as much.

For example, let's say you have non-cloud photo editing software. It is installed on your computer and doesn't do anything over the Internet. If you want to edit a really big photo, then you need:

- space on your computer's drive to store it
- RAM memory on your computer to be able to work with the photo
- enough processing power (CPU and/or GPU) to be able to edit it in a reasonable amount of time

With cloud computing, all of that changes. The storage or computation (or both) happen on **someone else's computer**, somewhere on the Internet.

This comes with lots of advantages. You can store more photos in the cloud than you can on your device. And you can have your data processed on machines that are more powerful, or more efficient, or combine their proccessing power in helpful ways.

## You're already in the cloud

You are definitely already using cloud applications. Here are some examples:

- Your gmail messages are stored on Google's computers, not yours
- Spam messages are filtered out of your inbox by a computer system that is more complex and powerful than could fit on your phone
- Streaming services like Spotify and Netflix give you access to a huge collection of media that would never fit on a single device.
- When you give a voice command to Siri or Alexa, your audio is sent over the Internet to a cloud-based system that processes it into text and "understands" your request
- You push your code to GitHub so that other students or instructors can see it without storing it on their computers

In addition to these well-known products, every website you visit has a server that receives your request, returns the HTML page to your browser, and stores and computes information for you. This cannot happen on your computer. It's all in the cloud!

## SaaS and the Cloud

You may have heard of the cloud-related acronym SaaS, which stands for "software as a service." Google Docs is an example of a SaaS product. In the old days, you would buy Microsoft Word and install it on your computer with a CD-ROM (or pay to download it to your computer). So then you had MS Word on your computer and it ran on your computer, with all of your computer's limitations in terms of storage, memory, and speed.

On the other hand, Google Docs is just a website. Key parts of the software that creates and edits your document, and all the storage of your documents, happens in the cloud, on Google's computers.

There are too many SaaS products in the world to count. Some of them are for consumers and many more are for very large enterprise-scale businesses. Companies that sell SaaS products to enterprises are often very profitable because SaaS software is never installed on the customer's machine. Instead, the customer has to pay a recurring fee to subscribe to the software. The fees for a SaaS business product can be 10s or 100s of thousands of dollars a month, if not even more.

## Deploying to the cloud

As a software engineer, you will also work with the cloud every day when you deploy web applications (update your site on the Internet).

In the old days, companies would have a few servers in a back room somewhere. These servers were connected to the Internet and would host the website and store user data.

Having a server in the back room turned out to be a pain. What if the power goes out? What if the computer gets old and needs to be upgraded? What if the server overheats and starts a fire? (This really happens!)

In addition, the company could be paying for a very expensive computer that gets a lot of traffic during the day, but gets no traffic at night. That's a waste of resources.

For those reasons, you are very likely to work at a company where the servers are no longer physically in a back room somewhere. Instead the servers are... You guessed it, in the cloud!

The most popular companies that provide this service are:

- Amazon Web Services (AWS)
- Google Cloud Platform (GCP)
- Microsoft Azure
- Heroku (what we'll use in class)

With a service like AWS, instead of maintaining your own server in the back room, you can log into the AWS website and set up a server by clicking a few buttons. You can choose how powerful you want the server to be, and you can even choose where it is located: Virginia, Ohio, Japan, etc.

What you'll get is not a physical computer assigned just to you, but a "virtual server" -- the ability to store data and use processing power on some portion of a much larger machine. Sometimes the storage and processing might be split over a bunch of different computers. We actually don't know -- and don't even need to know -- exactly how the virtual server is maintained. That's Amazon's problem! As far as we're concerned, as the people clicking on the AWS site, we can mostly live our lives as though there is a separate server just for us.

These services are better than maintaining your own server for many reasons.

First, maintaining the server or database is their problem, not yours. Most companies like AWS offer incredible guaranteed reliability. For these companies, offering 99% reliability isn't even impressive. Even 99.9% isn't impressive. Instead, these companies brag about guaranteed uptime or storage durability in terms of how many 9s are in the number. For example AWS S3 is a storage service that guarantees to keep 99.999999999% of everything it stores ("eleven nines").

Second, these services cost less than buying your own server. AWS has thousands of servers that it can buy at volume and combine efficiently in different data centers around the world, so it's much cheaper.

These services also offer very useful features like data backups or auto-scaling (adding more servers automatically if you get a spike in traffic).

These services also allow tech companies to create infrastructure (groups of related servers and applications) that is incredibly complex. Even a small company like Codecademy has an infrastructure in AWS that encompasses literally thousands of different servers. AWS helps the company keep track of and manage this complicated architecture.

## What do I need to know about the cloud to get a job?

As a junior engineer, nobody is going to expect you to create a system of thousands of servers running on Azure or AWS.

However, it will be helpful in interviews to show that you understand the general cloud computing concepts like the ones in this article.

Some things that will really help you are:

- Deploying your projects to a server in the cloud (we will eventually do this in class)
- Understand that servers live in the cloud and that most of the user's storage and computation is done in the cloud
- Know the main companies that offer cloud services (AWS, GCP, etc.)
- Know the names of some of the most common products these services offer, for example AWS S3 for storage.
- Know that companies use GitHub together with cloud providers like AWS to automatically test and deploy code from pull requests.

