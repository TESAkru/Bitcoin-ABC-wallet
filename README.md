# Bitcoin-ABC-wallet
## Official wallet for Bitcoin Cash ABC [BCHA]

<pre> Licence: MIT Licence
Author: Thomas Ramo
BCHA Porting: The Bitcoin ABC developers
Language: Python
Homepage: https://mybchawallet.org
</pre>

  <a href="">
    <img src="https://camo.githubusercontent.com/a4bf767b19695ac59cffcf809a1ad065a0e89b9dd58cd79668c6cc9679ea80cf/68747470733a2f2f6170692e6e65746c6966792e636f6d2f6170692f76312f6261646765732f32373431393837392d376165382d346637622d616432652d3131376665373863653831342f6465706c6f792d737461747573" alt="">
  </a>

<a href="">
    <img src="https://camo.githubusercontent.com/6af924e2715d6ef374ce052cf9ad25e51cc3fcac8eb01dddc2b65f488f2d5a4a/68747470733a2f2f7472617669732d63692e6f72672f626974636f696e2d636173682d6e6f64652f6263686e6f64652d7765622e7376673f6272616e63683d6d6173746572" alt="">
  </a>

  [![local.png](https://i.postimg.cc/VLmgByqR/local.png)](https://postimg.cc/Dmp1nMYJ)

## Getting started

### Lattest light version 4.31 - [BCHA wallet](https://mybchawallet.org/) 

You can also install BitcoinABC on your system, by running this command:

<pre>sudo apt-get install python3-setuptools
pip3 install .[fast] </pre>
This will download and install the Python dependencies used by BitcoinABC, instead of using the 'packages' directory. The 'fast' extra contains some optional dependencies that we think are often useful but they are not strictly needed.

If you cloned the git repository, you need to compile extra files before you can run BitcoinABC. Read the next section, "Development Version".

# Creating Binaries
To create binaries, create the 'packages' directory:
<pre>./contrib/make_packages </pre>
This directory contains the python dependencies used by Bitcoin ABC.

## Mac OS X / macOS
See contrib/build-osx/.

## Windows
See contrib/build-wine/.

## Android
See Bitcoin_ABC/gui/kivy/Readme.md file.
