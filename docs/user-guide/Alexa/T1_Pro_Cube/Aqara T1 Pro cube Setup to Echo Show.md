<center><img width="300" height="auto" border="0" align="center"  src="/my-project/img/Alexa/T1_Pro_Cube/T1pro_cube_logo860x1147.jpg" title="T1 Pro Cube"/></a></center><br>
<iframe width="660" height="415" src="https://www.youtube.com/embed/bTc6qBVb9d4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe><br>

## Short Intro
This device is a very helpful cube T1 Pro that we can use to read out are Glucose readings but not only that can control your Home and so much more. I will be trying to help you set up an Echo Show 10 (3rd Gen) or an Echo Dot or a Samsung Tablet. So, it will read out your Glucose readings. I will not be going through and explaining the unboxing as this as been done in other videos.<br>

This device is a very helpful cube T1 Pro that we can use to read out are Glucose readings but not only that can control your Home and so much more. I will be trying to help you setup onto an Echo Show 10 (3rd Gen) or a Exco Dot so it will read out your Glucose readings.

<br>

## Items you are going to need

1.	<a href="https://www.amazon.co.uk/dp/B0BHWS3VTZ?maas=maas_adg_F2E7A71BEAD7E7012F8DA4528E905764_afap_abs&linkCode=sl1&tag=paulhibbert-21&linkId=17f5a99c41bcb0d2cd1cdd6c378794b3&language=en_GB&ref_=as_li_ss_tl" target="_blank" title="Aqara Cube T1 Pro">Aqara Cube T1 Pro</a>   (Also REQUIRES AQARA ZIGBEE 3.0 HUB)
2.	<a href="https://www.amazon.co.uk/dp/B09BJCNCKM?psc=1&ref=ppx_yo2ov_dt_b_product_details" target="_blank" title="Aqara Smart Hub">Aqara Smart Hub E1</a> Aqara Smart Hub E1 (2.4 GHz Wi-Fi Required)
3.	<a href="https://www.amazon.co.uk/dp/B084P3KP2R?psc=1&ref=ppx_yo2ov_dt_b_product_details" target="_blank" title="Echo Show 10">Echo Show 10 (3rd generation)</a> or an <a href="https://www.amazon.co.uk/gp/product/B09B96TG33/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1" target="_blank" title="Echo Dot">Echo Dot </a> (5th generation, 2022 release) Or your Samsung Mobile or Tablet
4.	Android Mobile Device in my case a <a href="https://www.amazon.co.uk/gp/product/B07W6XFX64/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1" target="_blank" title="Samsung Note10 +">(Samsung Note10 +)</a> 
If you have an iPhone you may wish to set it up with Home App (but I will not be showing you a setup in this video) <br>

## Software you will need to have Setup

1.	[Nightscout](../../Nightscout/Setting_up_Github_Account_part1.md#part-1-setting-up-the-github-for-nightscout)
(Which I will not be showing you how to setup in these instructions) But will add a link for you to do it if you have not done so already. 
<br>

2.	<a href="https://www.sugarmate.io/" target="_blank" title="Sugarmate">Sugarmate</a>  on a  PC (You will need to sign up) or
3.	Sugarmate link sent onto your Desktop of your mobile phone.
4.	<a href="https://play.google.com/store/apps/details?id=com.amazon.dee.app&hl=en" target="_blank" title="Amazon Alexa App">Amazon Alexa App</a> 
<br> with an Amazon Account
5.	<a href="https://atlas-night-out.github.io/my-project/user-guide/xdrip/xdrip%20-%20Download/" target="_blank" title="Xdrip">Xdrip</a> 
6.	<a href="https://aiot-management.aqara.cn/config/app/aqaraHomeDeveloping" target="_blank" title="Aqara Home">Aqara Home</a>  App
<br>

## My Setup

#### Quick Setup
### Add Device
1.	First download the Aqara Home app.
Search for "Aqara Home" in the Apple App Store, or Google Play,
Xiaomi Get Apps, Huawei App Gallery, or scan the following QR code to download the Aqara Home App:<br>
<img width="300" height="auto" border="0" align="center"  src="/my-project/img/Alexa/T1_Pro_Cube/Aqara barcode.jpg" title="Aqara Home App"/></a><br>

2.	An Aqara Zigbee 3.0 hub is required. Please make sure
you have an <a href="https://www.amazon.co.uk/dp/B09BJCNCKM?psc=1&ref=ppx_yo2ov_dt_b_product_details" target="_blank" title="Aqara Smart Hub">Aqara Smart Hub E1</a> installed and added to
your Aqara Home App<br>

## Setting up the E1 Hub 
<img width="200" height="auto" border="0" align="center"  src="/my-project/img/Alexa/T1_Pro_Cube/E1 Hub.png" title="E1 USB Hub"/></a><br>

1. Plug the hub into a USB port that can provide power, wait for the yellow indicator to flash quickly, and make sure your mobile phone is connected to a Wi-Fi network in the 2.4 GHz frequency band.  <br>

You will need to make sure your home router is set to a 2.4 ghz bands until you are setup with your hub and T1 Pro, you may turn it back to Auto 5GHz after the setup.  <br>
keep the mobile phone as close to the hub as possible, and your mobile phone and hub are using the same Wi-Fi network.<br>

2. Open the Aqara Home app, click the <span style="background-color: #FFFF00">**+**</span> in the upper right corner of the home page, select <span style="background-color: #FFFF00">**Hub E1**</span>, from  <span style="background-color: #FFFF00">**Add Accessory - Gateway/Hub E1**</span> and follow the instructions of the app to operate.<br>
1 <img width="300" height="auto" border="0" align="center"  src="/my-project/img/Alexa/T1_Pro_Cube/Adding Accessory.png" title="Add Accessory"/></a>2 <img width="300" height="auto" border="0" align="center"  src="/my-project/img/Alexa/T1_Pro_Cube/Gateway_Hub E1.png" title="Gateway - Hub E1"/></a><br>
3 <img width="300" height="auto" border="0" align="center"  src="/my-project/img/Alexa/T1_Pro_Cube/Add Hub E1.png" title="Add Hub E1"/></a>4 <img width="300" height="auto" border="0" align="center"  src="/my-project/img/Alexa/T1_Pro_Cube/scan the device.png" title="scan the Device"/></a><br>
5.	If the addition fails, please long press the hub button for 10s to reset the network, and then add it again in the app.<br>
6. Once the E1 Hub is connected you can now connect the T1 Pro Cube.<br>

<iframe width="392" height="397" src="https://www.youtube.com/embed/6WkQg_FvaU8" title="Connecting to Aqava E1 Hub after changing Router to a 2 4ghz" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe><br>

## Adding the T1 Pro Cube

## Adding Battery <br>
Open the battery cover of Cube T1 Pro with the ejector tool, take out the battery, replace it with a new <span style="background-color: #FFFF00">**CR2450**</span>.
Be careful when removing the lid to know the correct  position of the cube for knowing when replacing the lid after you change the battery, that you have the correct position to avoid damage to the lid. <br>

## Reset Switch
1 <img width="500" height="auto" border="0" align="center"  src="/my-project/img/Alexa/T1_Pro_Cube/T1 Pro Reset button pairing.jpg" title="Reset button"/><br>

## T1 Battery Replacement
<iframe width="883" height="509" src="https://www.youtube.com/embed/Ec3coJxT6Lw" title="T1 Pro Cube Battery Replacement Tip" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Adding Aqara Cube T1 Pro
1. Now in the Aqara Home app, click <span style="background-color: #FFFF00">**+**</span> in the upper right corner of the home page to enter the <span style="background-color: #FFFF00">**Add Accessory page**</span>, then select <span style="background-color: #FFFF00">**Remote control**</span> on the left then select <span style="background-color: #FFFF00">**Cube T1 Pro,**</span> and select the hub to be linked.<br>

use corresponding to the instructions on the app, and then long press the device reset button for 5 seconds, waiting for the hub to indicate that the connection is successful.<br>

1 <img width="300" height="auto" border="0" align="center"  src="/my-project/img/Alexa/T1_Pro_Cube/Aqara Home app click plus.png" title="AQara Plus"/></a>2 <img width="300" height="auto" border="0" align="center"  src="/my-project/img/Alexa/T1_Pro_Cube/remote T1 Pro cube.png" title="Remote - Cube T1 Pro"/></a><br>

2. You should now have both the E1 Hub and T1 Pro Cube installed in your AQara Software.<br>
<Center><img width="300" height="auto" border="0" align="center"  src="/my-project/img/Alexa/T1_Pro_Cube/Accessories.jpg" title="Accessories"/></a></Center><br>


## Amazon Alexa
<img width="300" height="auto" border="0" align="center"  src="/my-project/img/Alexa/T1_Pro_Cube/Google Play Amazon Alexa.jpg" title="Google Play Amazon Alexa"/><br>

1.	Now you need to install <a href="https://play.google.com/store/apps/details?id=com.amazon.dee.app&hl=en" target="_blank" title="Amazon Alexa App">Amazon Alexa App</a> with an Amazon Account on your device rather it be Echo Show 10 or an Android Mobile.<br>
2. After logging in select, the bottom More Option and then Skill & Games







#### not finished yet more to come!
# Full Setup Coming soon! 









</br>









  <!--  
  ******************************************************************************************************************
  mkdocs.yml    # The configuration file.
    docs/
    index.md  # The documentation homepage.
       ...       # Other markdown pages, images and other files.
		
		*************************************************************************
		center text**
		## <center>Now Do  </center><br>
		
		*************************************************************
		
		
<a href="http://nightscout.github.io/pages/update-fork/" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/Time to Update Nightscout.png" title="Update Tool"/></a>		
		
		
adding 	Yellow Hightligher!!!!!!!!	with bold too
<span style="background-color: #FFFF00">**Marked text**</span>


<a>
  <img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/Time to Update Nightscout.png" title="Update Tool"/></a>	




Adding a image with link
<a href="https://www.youtube.com/watch?v=MFsbm45b6YY" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/img/Part 1 Setting up Github 2021/Github account details.jpg" title="github account details"/>
</a><br>
******************************
just a link
***************

<a href="https://www.mongodb.com/cloud/atlas" target="_blank" title="Click Try Free">See Here</a> 

********************************
link to another page!
*************************

[Nightscout](../../Nightscout/Setting_up_Github_Account_part1.md#part-1-setting-up-the-github-for-nightscout)

********************************************

Adding Video

<iframe width="850" height="415" src="https://www.youtube.com/embed/MFsbm45b6YY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Adding an embeded video
<iframe id="video3" width="560" height="315" src="https://www.youtube.com/embed/o7-T2IrDJ_A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Note
**Note:** a note is something that needs to be mentioned but is apart from the context.


List
This is a regular paragraph.

Paragraph:

1. **Now Open another tab**  to make a Mongodb Atlas** Account: <a href="https://www.mongodb.com/cloud/atlas" target="_blank" title="Click Start Free">See Here</a> 
  and **click** Start Free
 <img width="auto" height="auto" border="0" align="center"  src="/img/Atlas/MongoDB Atlas start free.jpg"Click Start"/>
   2. Sub item two
   3. Sub item three
2. Item two



font size
<font size="4">

</font>

link
<a href=" https://github.com/" target="_blank" title="First create a user account by going to">Click Here</a>


Table
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |


Video in a box border!

<table width="1166" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><span style="color: #ffffff;">video Instructions,</span></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">
 <iframe id="video3" width="860" height="515" src="https://www.youtube.com/embed/6o3AdkQBVog" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  </span></td>
</tr>
</tbody>
</table>
*****************************************************
Warning Note<table width="1266" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #FF0000;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Warning!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;"> 1: Some new features, updates, or bug fixes may require that you clear your browser cache before you will see the changes taken effect<br/> 2: If you get no errors and no readings after a while see about doing a <a href="http://127.0.0.1:8000/user-guide/Redeploying%20your%20repository/" target="_blank" title="Redeploying your repository link">Redeploying your repository</a> </span></td>
</tr>
</tbody>
</table>

-->


<!--  
  ******************************************************************************************************************
  mkdocs.yml    # The configuration file.
    docs/
    index.md  # The documentation homepage.
       ...       # Other markdown pages, images and other files.
		
		****************************************************************

[In the the video above](../xdrip/Xdrip%20-%20Setting%20up%20Glucose%20Meters.md#video-instructions)





!!!warning 
    Do not use CONTOUR DIABETES app, when using xdrip you can only have one App running!
   <br><br>



   !!!info 
    Do not use CONTOUR DIABETES app, when using xdrip you can only have one App running!
   <br><br>


		
<a href="http://nightscout.github.io/pages/update-fork/" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/Time to Update Nightscout.png" title="Update Tool"/></a>		
		
		
adding 	Yellow Hightligher!!!!!!!!	with bold too
<span style="background-color: #FFFF00">**Marked text**</span>


link

<a href=" https://github.com/" target="_blank" title="Github">Click Here</a> 

  <img width="auto" height="auto" border="0" align="center"  src="/img/Fork and Deploy cgm remote monitory Part 4/warning_sign.png" title="Update Tool"/></a>	

<img width="30" height="30" src="/img/Fork and Deploy cgm remote monitory Part 4/clipart2068155.png">

Adding a image with link
<a href="https://www.youtube.com/watch?v=MFsbm45b6YY" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/img/Part 1 Setting up Github 2021/Github account details.jpg" title="github account details"/>
</a><br>


Adding Video

<iframe width="850" height="415" src="https://www.youtube.com/embed/MFsbm45b6YY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Adding an embeded video
<iframe id="video3" width="560" height="315" src="https://www.youtube.com/embed/o7-T2IrDJ_A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Note
**Note:** a note is something that needs to be mentioned but is apart from the context.


List
This is a regular paragraph.

Paragraph:

1. **Now Open another tab**  to make a Mongodb Atlas** Account: <a href="https://www.mongodb.com/cloud/atlas" target="_blank" title="Click Start Free">See Here</a> 
  and **click** Start Free
 <img width="auto" height="auto" border="0" align="center"  src="/img/Atlas/MongoDB Atlas start free.jpg"Click Start"/>
   2. Sub item two
   3. Sub item three
2. Item two



font size
<font size="4">

</font>

link
<a href=" https://github.com/" target="_blank" title="First create a user account by going to">Click Here</a>

*******************************************************************************************************************************
*******************************
orange table

<table width="1166" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #db4e12;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Note!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">If you’re on Heroku and have Automatic Deploys enabled, you’re done!<br>
 If you don’t have Automatic Deploys on yet, or aren’t sure, run through these steps below!</span></td>
</tr>
</tbody>
</table>
***************************************
red warning table
***************************
<table width="1266" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #FF0000;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Warning!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;"> 1: Some new features, updates, or bug fixes may require that you clear your browser cache before you will see the changes taken effect<br/> 2: If you get no errors and no readings after a while see about doing a <a href="http://127.0.0.1:8000/user-guide/Redeploying%20your%20repository/" target="_blank" title="Redeploying your repository link">Redeploying your repository</a> </span></td>
</tr>
</tbody>
</table>
*********************************
Blue Note
******************************
<table width="1166" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Note!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;"> You will have already needed to have done <a href="https://atlas-night-out.github.io/my-project/user-guide/Setting_up_Github_Account_part1/" target="_blank" title="firt you need to do Part 1 Setting up Github Account for Nightscout">Part 1 Setting up Github Account for Nightscout</a>. To be able to continue.</span></span></td>
</tr>
</tbody>
</table>



Table
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |


Video in a box border!

<table width="1166" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><span style="color: #ffffff;">video Instructions,</span></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">
 <iframe id="video3" width="860" height="515" src="https://www.youtube.com/embed/6o3AdkQBVog" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  </span></td>
</tr>
</tbody>
</table>
*****************************************************
Warning Note<table width="1266" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #FF0000;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Warning!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;"> 1: Some new features, updates, or bug fixes may require that you clear your browser cache before you will see the changes taken effect<br/> 2: If you get no errors and no readings after a while see about doing a <a href="http://127.0.0.1:8000/user-guide/Redeploying%20your%20repository/" target="_blank" title="Redeploying your repository link">Redeploying your repository</a> </span></td>
</tr>
</tbody>
</table>
<img width="400" height="auto" border="0" align="center"  src="/my-project/img/Nightscout/sadface.png" Sad day"/><br>
-->


