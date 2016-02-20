#How Build Less files with Grunt?

1. Install Node.js

2. Use NPM to install Grunt by running the follwing command: npm install -g grunt-cli

3. Run the following commands to initialize NPM for your project and install Grunt: npm install grunt –-save-dev

4. Next, you need to install the LESS plugin to be able to compile your styles.
You can do that by running the following command in your project root:
npm install grunt-contrib-less –-save-dev

5. Install the watch plugin by running the following command: npm install grunt-contrib-watch –-save-dev

6. Run the following command to make Grunt watch your LESS files:
grunt watch:styles
7. When you now make a change in one of your LESS files, you should see
something similar to the following output in your command prompt:
$ grunt watch:styles
Running "watch:styles" (watch) task
Waiting...OK
>> File "less/main.less" changed.
Running "less/app" (less) task
File css/main.css created.
Running "watch:styles" (watch) task
