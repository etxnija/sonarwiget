# sonarwiget

[Sonar](http://www.sonarsource.org/) is a great tool for static code analysis and I use it most every day to see code qualty
trends of the code I'm responsible for. There is a great dashboard that shows you mertics of the code. This dashboard can be 
inimidating. I also notices that most of the team members beeing it managers, business or develiopers did not visit the 
report page.

How do I get the code analysis result visiable? My idea is to put the in your face. Most projects have a web page 
to spread information and track progress. So I wanted a way to put important metrics on this page without installing 
somehing on a server and such. The result is some HTML and JavaScript that you can paste to you page. 

_I'm not a HTMNL/Web Designer so the look can be improved same is probably true for the JavaScript as well._ 
Any input and improvments are wellcome. 


## Usage
* Copy the contents of the sonar.html page and place it on the page where you want he widget.
* Update the url variable to your sonar url ```var url = "http://sonar:8080"```
* Update the sonar project id (resource) in the code ```var resource ="17597";``` it's the number ```http://sonar:8080/dashboard/index/17597``` on the project dashboard url.
* Save the page


Now the widget dashboard should diplay on the page and pull the values form the sonar server.

## Credit
I'm using code from [J50Nπ by Roberto Decurnex](https://github.com/robertodecurnex/J50Npi) that was very easy to use.

## Reference links
* [Sonar](http://www.sonarsource.org/)
* [Sonar Web services API reference](http://docs.codehaus.org/display/SONAR/Web+Service+API)


/Nils

