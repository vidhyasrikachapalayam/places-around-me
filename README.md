# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

Step 1:
clone the repository into the theia id

Step 2:
create a new django project

Step3:
Write the needed HTML code

Step4:
Run the django server and excute the code
## Code:

map.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Puzhal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>dharani p (22009065)</b></font>
</h3>
<center>
<img src="/static/images/location.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/ghs.html" title="Govt. Higher Secondary School">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/rto.html" title="RTO Office">
<area shape="circle" coords="400,350,50" href="/static/html/vk.html" title="Puzhal Lake">
<area shape="circle" coords="400,200,75" href="/static/html/bus.html" title="Hi-Tech Bus Stand">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/park.html" title="Eco-Park">
</map>
</center>
</body>
</html>
```
park.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Eco-Park</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Puzhal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Eco-Park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
A very nice park near puzhal bus stand. It is located surrounding the puzhal Lake. 
Very superb calm place in puzhal. Best for walking. Nice playing place for kids.
Well maintained with jogging track. Source of ground water.
Good place play with children.  In Banyan Tree lot of parrot stay like house. 
Good sound and Air. Lake view park looks awesome.
Very nice place at puzhal.
Simple and relax with play area.
</font>
</p>
</body>
</html>
```
rto.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>RTO Office</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Ariyalur - Cement City</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>RTO Office</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
RTO office or the Regional Transport Office is a government body specifically established to oversee all transport-related operations in the country. RTOs are located throughout the country in each state and union territory. RTOs are responsible for enforcing the rules as laid down by the Motor Vehicle Act of 1988.
The department also maintains a database of all the vehicles operating in the country as well as issues licenses for drivers. Besides, the RTO office also collects road taxes, supervises pollution checks, and ensures the enforcement of all road transportation rules. If you own or drive a vehicle in India, you will need to visit the RTO to get your vehicle registered, obtain a driver’s license or renew your driver’s license, etc.
RTOs are also responsible for improving road and vehicle safety, especially to avoid accidents and other road fatalities.
</b>
</font>
</p>
</body>
</html>
```
bus.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Bus Stand</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Puzhal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hi-Tech Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Puzhal is an administrative district, one of the 38 districts in the 
state of Tamil Nadu in India. The district headquarters is located at puzhal. 
The district encompasses an area of 1,949.31 km². Gangaikonda Cholapuram, 
built by King Rajendra Cholan of Chola Empire, is a UNESCO World Heritage site 
situated in this district. The district is also known for its rich prehistoric 
fossils. Many fossils of gigantic molluscs and jawed fishes, at least one 
fossilized dinosaur egg, and several fragmentary fossils of sauropod and theropod 
dinosaurs have been discovered here. An on-site museum is being set up at 
Keelapazhur to preserve and conserve fossils. Ariyalur is noted for its cement
 industries and Jayankondam has huge reserves of lignite.
</b>
</font>
</p>
</body>
</html>
```
ghs.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Govt. High. Sec. School</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Puzhal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Government Higher Secondary School</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The main objectives of puzhal Government Higher Secondary School are 
<ul>
<li>To impart proper and qualified training to teachers and give them an attractive salary and incentives so that they are not tempted to quit and look elsewhere for jobs.</li>
<li>To provide financial aids and grants wisely and judiciously.</li>
<li>To Frame of syllabus and curriculum.</li>
<li>To set aims and objectives of education.</li>
</ul>
</font>
</p>
</body>
</html>
```
vk.html
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Washerman’s Lake</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><Puzhal</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Puzhal Lake</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The uses of Puzhal Lake in puzhal are 
<ol type="1">
<li>Lake is used for rain water harvesting.</li>
<li>It is used for drinking.</li>
<li>Pisculture.</li>
<li>For bathing, washing clothes etc.</li>
</ol>
</font>
</p>
</body>
</html>
```
## Output:

![Screenshot (19)](https://user-images.githubusercontent.com/119477817/215650265-1455e893-8065-4fdc-b026-a23aab070007.png)


![Screenshot (20)](https://user-images.githubusercontent.com/119477817/215650229-dada3903-db46-4aa0-9570-c0065584a086.png)



![Screenshot (21)](https://user-images.githubusercontent.com/119477817/215650309-beb41524-f87e-4fa4-b8a3-fd4405db21c5.png)


![Screenshot (22)](https://user-images.githubusercontent.com/119477817/215650331-a46a32ef-43d5-480e-862e-2f2657dd47cf.png)


![Screenshot (23)](https://user-images.githubusercontent.com/119477817/215650349-89cf21b9-904f-4811-8007-bf20c825b679.png)

## validator



![Screenshot (24)](https://user-images.githubusercontent.com/119477817/215650827-cd12e356-81a6-4dcf-ade2-30599c15f412.png)


## Result:

thus we desigened a web page for pages around me 
