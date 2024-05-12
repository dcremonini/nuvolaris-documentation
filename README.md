# Nuvolaris Documentation

Nuvolaris is a distribution of [Apache OpenWhisk](https://openwhisk.apache.org) that aims to be portable to every Kubernetes and to include a set of integrated services to make awesome developer experiences.

It includes `nuv`, an [all-in-one CLI](https://github.com/nuvolaris/nuvolaris/releases) that manages both installations on Kubernetes and development.

## Learn More

- Learn [how to install Nuvolaris](documentation/installation.md).
- Learn [how to develop with Nuvolaris](https://openwhisk.apache.org/documentation.html) using OpenWhisk documentation.
- Read  [a book on Apache OpenWhisk](https://www.amazon.com/Learning-Apache-OpenWhisk-Developing-Serverless-ebook/dp/B07TYSXWNN) written by one of the authors of OpenWhisk and Nuvolaris.

**NOTE**: the Apache OpenWhisk documentation used the `wsk` tool, which is embedded as a subcommand in the `nuv` tool. If you use Nuvolaris, whenever you see `wsk` you should use `nuv wsk` instead. 

In alternative, you can add to your `.bashrc` the following:

```
alias wsk='nuv wsk'
```

So when you type `wsk` it will use `nuv wsk`.

## How to get help

If you have problems you can:

- Discuss with us in the [Nuvolaris Forum](https://nuvolaris.discourse.group)
- Check our [YouTube Channel](https://www.youtube.com/channel/UCPt5hk7qcOkESjB7kii1byw) for more training videos.
- Open an issue in the CLI [Issue Tracker](https://github.com/nuvolaris/nuvolaris-cli/issues) 
