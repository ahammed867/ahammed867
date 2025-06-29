# Hey, I'm Ahmed 👋

I'm working on making cloud infrastructure less painful for developers.

## What I'm building

Right now I'm deep into **[GNOS](https://github.com/ahammed867/gnos)** - basically trying to make all those cloud APIs work like regular files.

You know how you need different SDKs for everything? AWS has one way of doing things, OpenAI has another, Google Cloud is completely different... it's exhausting.

So I thought - what if you could just do this:

```bash
# Talk to AI
echo "explain quantum computing" > /mnt/gnos/ai/gpt4
cat /mnt/gnos/ai/gpt4

# Upload to cloud  
cp report.pdf /mnt/gnos/cloud/s3/my-bucket/
```

Just regular file operations. No SDKs, no API keys in your code, no vendor lock-in.

## The technical stuff

I mostly work with:
- Rust (for the low-level filesystem stuff)
- Python (for prototyping)
- A concerning amount of Linux kernel documentation

Currently learning the hard way why FUSE filesystems are tricky to get right.

## Why I care about this

I thought this was a bottleneck and I am trying to solve itl

I think developer tools should just work. You shouldn't need a PhD to deploy a function or talk to an AI model.



---

*Currently turning caffeine into questionable filesystem drivers*
