# Ex09 Event Registration Web Application
## Date: 10.05.2023

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
HOME PAGE 
```
<div style={{width: 372, height: 641, position: 'relative', background: 'white'}}>
  <img style={{width: 376, height: 656, left: -4, top: 0, position: 'absolute'}} src="https://via.placeholder.com/376x656" />
  <div style={{width: 202, height: 42, left: 95, top: 263, position: 'absolute', fontSize: 24, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>         LOGIN          </div>
  <div style={{width: 240, height: 55, left: 61, top: 330, position: 'absolute', background: '#FF0101'}} />
  <div style={{left: 128, top: 343, position: 'absolute', color: 'white', fontSize: 24, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>LOGIN</div>
  <div style={{left: 150, top: 591, position: 'absolute', color: 'white', fontSize: 24, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>RE</div>
  <div style={{width: 240, height: 55, left: 61, top: 566, position: 'absolute', background: '#FF0101'}} />
  <div style={{width: 118, height: 29, left: 118, top: 579, position: 'absolute', color: 'white', fontSize: 24, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>REGISTER</div>
  <img style={{width: 149, height: 136, left: 103, top: 116, position: 'absolute'}} src="https://via.placeholder.com/149x136" />
  <div style={{width: 268, height: 49, left: 52, top: 281, position: 'absolute', color: 'black', fontSize: 24, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>SPORTS DAY EVENTS</div>
  <img style={{width: 348, height: 50, left: 7, top: 10, position: 'absolute'}} src="https://via.placeholder.com/348x50" />
</div>
```
EVENTS PAGE
```
<div style={{width: 360, height: 640, position: 'relative', background: 'white'}}>
  <div style={{width: 28, height: 23, left: 35, top: 401, position: 'absolute', background: 'black', borderRadius: 9999}} />
  <div style={{width: 28, height: 23, left: 35, top: 466, position: 'absolute', background: 'black', borderRadius: 9999}} />
  <div style={{width: 220, height: 35, left: 111, top: 401, position: 'absolute', color: 'black', fontSize: 24, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>HI</div>
  <div style={{width: 220, height: 35, left: 111, top: 462, position: 'absolute', color: 'black', fontSize: 24, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>HI</div>
  <img style={{width: 360, height: 640, left: 0, top: 0, position: 'absolute'}} src="https://via.placeholder.com/360x640" />
  <div style={{left: 109, top: 223, position: 'absolute', color: 'black', fontSize: 24, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>*CRICKET<br/><br/>*VOLLEYBALL<br/><br/>*TENNIS<br/><br/>*1OO METRES<br/><br/>*200 METRES<br/></div>
  <img style={{width: 366, height: 55, left: 0, top: 14, position: 'absolute'}} src="https://via.placeholder.com/366x55" />
  <div style={{width: 282, height: 43, left: 49, top: 160, position: 'absolute', color: 'black', fontSize: 24, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>SPORTS DAY EVENTS</div>
</div>
```
EVENT REGISTRATION 
```

<div style={{width: 360, height: 640, position: 'relative', background: 'white'}}>
  <div style={{width: 240, height: 55, left: 64, top: 182, position: 'absolute', background: '#FF0101'}} />
  <img style={{width: 360, height: 640, left: 0, top: 0, position: 'absolute'}} src="https://via.placeholder.com/360x640" />
  <div style={{width: 268, height: 49, left: 39, top: 160, position: 'absolute', color: 'black', fontSize: 24, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>EVENT REGISTRATION</div>
  <div style={{width: 232, height: 17, left: 57, top: 220, position: 'absolute', color: 'black', fontSize: 14, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>FILL IN YOUR DETAILS<br/></div>
  <div style={{width: 214, height: 25, left: 61, top: 273, position: 'absolute', background: 'white'}} />
  <div style={{width: 73, height: 25, left: 72, top: 273, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>NAME</div>
  <div style={{width: 210, height: 23, left: 65, top: 320, position: 'absolute', background: '#F5F5F5'}} />
  <div style={{width: 112, height: 25, left: 72, top: 320, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>GENDER</div>
  <div style={{width: 210, height: 27, left: 65, top: 354, position: 'absolute', background: 'white'}} />
  <div style={{left: 72, top: 363, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>AGE</div>
  <div style={{width: 214, height: 20, left: 57, top: 414, position: 'absolute', background: 'white'}} />
  <div style={{width: 126, height: 29, left: 73, top: 414, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>MOBILE NUMBER</div>
  <div style={{width: 210, height: 23, left: 61, top: 473, position: 'absolute', background: 'white'}} />
  <div style={{width: 76, height: 23, left: 69, top: 473, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>EMAIL ID</div>
  <div style={{width: 199, height: 20, left: 63, top: 533, position: 'absolute', background: 'white'}} />
  <div style={{width: 75, height: 20, left: 65, top: 533, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>EVENTS</div>
</div>
```

CONTACT
```

<div style={{width: 360, height: 652, position: 'relative', background: 'white'}}>
  <img style={{width: 360, height: 652, left: 0, top: 0, position: 'absolute'}} src="https://via.placeholder.com/360x652" />
  <div style={{left: 61, top: 255, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>WE ARE EAGERLY WAITING FOR<br/>YOUR PARTICIPATION IN THE<br/>SPORTS ACTIVITIES.</div>
  <img style={{width: 324, height: 49, left: 11, top: 6, position: 'absolute'}} src="https://via.placeholder.com/324x49" />
  <div style={{left: 119, top: 198, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>THANK YOU </div>
  <div style={{left: 36, top: 575, position: 'absolute', color: 'black', fontSize: 15, fontFamily: 'Inter', fontWeight: '700', wordWrap: 'break-word'}}>CONTACT US: T.KAVINAJAI<br/>7339102544 kavinajai1311@gmail.com</div>
</div>
```

## OUTPUT:
![alt text](<Screenshot 2024-05-10 130621.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
