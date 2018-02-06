# Website Performance Optimization portfolio project

### Description
One of Front End Web Development projects , a given website required to be optimized.

### Changes:

#### index.html
1. Delete Google Fonts, I dont see any use of it.
2. Create a new java script file for the blocked java script code in the html file, and make it inlined.
3. Move all js file at the end of html file, and make then *sync* .
4. Delete print.css file, since it takes time for loading and add it to the style tag in the header.
5. Make style.css as a block in html file instead of inlined.
6. Optimize all images using ImageOptim.

#### pizza.html
1. Optimize all images using ImageOptim.

#### main.js
1. Remove some valrable out side the loops, since they' have to be assigned(changed) once.
2. Assinged repaeted value into one variable, and that variable.
3. Make less use of *offsetWidth*.

### Demo
https://rawana.github.io/frontend-nanodegree-mobile-portfolio/

### Installtion

## Run it on the internet 
1. Click "Download ZIP" and unzip the file.
2. Download *ngrok* into the same folder.
3. Open the terminal and put the folder's directory.
4. Optional : Chaeck Python version if not known.
```
Python -V
```
5. If Python version returns 3.X
```
Python -m http.server
```
6. If python version returns 2.X
```
Python -m SimpleHTTPServer
```
*A local host is created*.

7. Open a new Terminal.
8. Go the folder's directory.
9. write 
```
./ngrock http localhostnumber
```
10. Get the link appeared.
