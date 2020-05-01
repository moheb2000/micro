# micro
## Welcome to micro
"Micro" is a simple static site generator that is written in shell programming language. It has a long way upon its face to become a good and complete site generator but I thank you because of your choice. I will be glad if you tell me my script problems and bugs and give me your suggestions about "micro". It is my first serious script in bash and I thank you again for your ideas that give to me.
## Installaton
For use of "micro" you should turn it executable. For that download "micro" from github and open bash on that directory. Then type this command in bash:
```
sudo chmod 755 micro
```
After that copy this file in /home/bin directory. If it does not exist create it. Then open bash and enter in a directory that you want to design and develop your site. use this command:
```
cd my-site-directory
```
Then write and run this command:
```
micro
```
In the first step, the script wants you to enter your site title. In the next step, you should enter your site-building directory. If you do not enter a directory it is create your site in frontend directory by default. Wish your site function and select a directory (this directory must exist).
```
Please enter your site title ->
Please enter build address(If you are not sure just click enter) ->
```
## Building site
To build your site run below bash script:
```
./builder
```
This script removes all files in building directory and adds new site files in it.

for more information, documentation and see DEMO: <a href="https://moheb2000.github.io/micro/index.html">CLICK HERE</a>
