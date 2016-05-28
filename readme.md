##Install

OSX requires

    brew install pkg-config cairo libpng jpeg giflib
    xcode-select --install # el capitain only

Ubuntu 

    sudo apt-get install libcairo2-dev libjpeg8-dev libpango1.0-dev libgif-dev build-essential g++

Everyone

    npm install

##Test

    npm run test

##Optimizations

- Iterate arrays in a CPU cache efficient way
- Keep track of smallest on top row
