# Install
npm install -g nodebot-workshop
# Run
nodebot-workshop

A series of code challenges will teach you the basics of the johnny-five api, a framework for working with Arduino and other rapid prototyping boards.

## Hardware is optional

The workshop will pose a challenge, you will code a solution which the workshop will then verify.

You will be writing working, executable johnny-five code.

Each of your solutions can be run by the workshop or directly as a node program.

When run through the workshop the low level code to talk to the Arduino is stubbed out.

Wire up an Arduino, connect the USB and run your solution directly to see it run for real.
Contributing
Code style

To move towards a consistent style for nodeschool projects we use the .jshintrc as defined in learnyounode: https://github.com/rvagg/learnyounode/blob/master/.jshintrc
Building

npm scripts are present for testing and linting:

$ npm run test
$ npm run lint

A pre-commit hook will be installed in your repo clone to run the test/lint scripts with every commit.