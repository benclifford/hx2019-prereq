Haskell eXchange 2019 Hands-On Build-A-Commandline-Tool Tutorial
================================================================

If you're participating in this tutorial, you should bring
a laptop which can build Haskell code. The following steps
should help you get your laptop into that state.

Ideally do this setup step before coming to Haskell
eXchange. It should take about half an hour (depending on
how much you already have set up).

1. First, install 'stack', for example by following the instructions at
https://docs.haskellstack.org/en/stable/README/#how-to-install

2. Get this repository onto your laptop. For example:

```
$ git clone https://github.com/benclifford/hx2019-prereq
```

3. Build the pre-requisites test code:

```
$ stack build
$ stack exec check-tutorial
```

You should see the message
`Congratulations! Haskell eXchange 2019 tutorial setup is complete.`
on your console.

If you have problems with the above, ideally resolve them before the
tutorial - if you need help, email benc@cqx.ltd.uk

This will both verify that your installation works, and also download some
Haskell packages that are needed during the tutorial. This will save
time when you come to use them during the tutorial so that you do not
need to download them over the Haskell eXchange wifi. So please follow
these steps even if you know your 'stack' installation already works.
