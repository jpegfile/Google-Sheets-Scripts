# Google-Sheets-Scripts
Sheets scripts that I personally use. 

If you use two functions like:

function a(event)
{}

function b(event)
{}

You can merge them like this:

function all(event){
  a(event);
  b(event);
}
