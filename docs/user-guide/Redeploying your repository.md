<!-- this is  on github live server!
docs made by D.Galloway 2019- 2021-->


# Welcome to The Diabetic way

For full Website content visit [The Diabetic Way](https://www.thediabeticway.co.uk/index.php/en/).

## Redeploying your repository
<br>

<font size="4">
# Step 1. Cleaning up Github
<br>

<table width="1166" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><span style="color: #ffffff;">Note!  If you prefer video, see below</span></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">
<iframe width="850" height="415" src="https://www.youtube.com/embed/mk2dyzz4r28" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  </span></td>
</tr>
</tbody>
</table>
*  <a href=" https://github.com/login" target="_blank" title="Github Log into Account">Click Here</a> to log into at GitHub: 
* 	Enter your username and password. And Click Sign in.

<a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Github/signintogithub.jpg" title="Log into Github Account"/>
</a>

* Select your own cgm-remote-monitor project (not nightscout/cgm-remote-monitor)

<a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Github/your-own-cgm-remote-monitor-project.jpg" title="Select your own cgm-remote-monitor"/>
</a>

* Select the settings at th top right

<a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Github/settings.jpg" title="Select settings"/>
</a>


* Scroll down to Danger zone and click Delete the repository `(Don't worry)`

<a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Github/deleterepository.jpg" title="Delete this repository
"/>
</a>

* Copy and paste your full repository name to confirm (make sure no spaces)then click I understand...
<a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Github/reenterrepository-name.jpg" title="Confirm by adding your repository"/>
</a>

* Now <a href=" https://github.com/nightscout/cgm-remote-monitor" target="_blank" title="Update Tool">-- Click Here  --</a> to go to the official repository <span style="background-color: #FFFF00"><br>

* Click on Fork

<a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Github/Fork.jpg" title="Select Fork"/>
</a>
*  Wait for it to complete then leave GitHub open.

<a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Github/forking nightscout.jpg" title="Select Fork"/>
</a>

# Step 2 - Now Deploy in Heroku
<br>

* Log into Heroku <a href=" https://id.heroku.com/login" target="_blank" title="logging into Heroku">-- Click Here  --</a> <br>
<br>
* Select your App (see below )<span style="background-color: #FFFF00"> I will also note here that having multiple Apps for this setup can cause issues on updating the stack!</span> `( I will also note here multiple Apps for this setup can cause issues on updating the stack!)`

<a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Heroku/SelectingApp.jpg" title="Selecting Heroku App"/>
</a>

* Then Click on <span style="background-color: #FFFF00"> Deploy</span> 
 <a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Heroku/clickondeploy.jpg" title="Deploy"/>
</a>
* Verify Heroku is connected to GitHub, if not, click and Connect it to your GitHub Account  -<span style="background-color: #FFFF00"> Somtimes you may have issues and need to disconnect from Github and then re connect back and then add your repo again Type cgm-remote-monitor and click Search then click Connect!</span>  
 <a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Heroku/github connected.jpg" title="Github connected"/>
  </a>
  
<table width="1166" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><span style="color: #ffffff;">Note!  If you prefer video, see below</span></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">
<iframe width="850" height="415" src="https://www.youtube.com/embed/5S2lcc5XY_g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  </span></td>
</tr>
</tbody>
</table>
  
  * Or if Heroku is not connected to GitHub, scroll down and click Connect to GitHub, if a popup window opens and requires authorization, click Authorize Heroku
  * Scroll down to the bottom of the page, make sure to select the <span style="background-color: #FFFF00">master branch</span>  and then click <span style="background-color: #FFFF00"> Deploy Branch</span>
  <a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Heroku/masterthendeploy.jpg" title="Select master then Deploy Branch"/>
</a>
  * Build will start, do not interfere and wait for completion. It can take a while <span style="background-color: #FFFF00">approximately around 10 minutes Do not Interrupt the process</span>  has it can lead to a broken site and you'll need to restart again.
  <a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Heroku/Build-will-start.jpg" title="Build will start and information will scroll in the log window"/>
</a>
* Wait until the deploy process completes and click View if nothing happens click Manage App then upper right Open App
<a href="" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Heroku/view-App.jpg" title="Delect View now that the deploy process is complete"/>
</a>
* Your site will open and  it should be at the latest version on your Nightscout Site
* <span style="background-color: #FFFF00">You're Finished!</span> 
* Head over to your Nightscout site and check its updated!


<table width="1166" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><span style="color: #ffffff;">Head over to your Nightscout site and check if updated!</span></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">
<iframe width="850" height="415" src="https://www.youtube.com/embed/MFsbm45b6YY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  </span></td>
</tr>
</tbody>
</table>
<br><br>
<a href="https://www.diabetes.org.uk/" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Diabetesuk/pngarea.com_rutgers-logo-png-8467605.png" title="Diabetes UK"/>
</a>               Why Not take visit [UK Wide Cycle Ride - Diabetes.uk](https://cycle.diabetes.org.uk/) or  [Swim22 - Diabetes.uk](https://swim22.diabetes.org.uk/) for your Diabetes Needs!<br><br>

If you would like to donate to me for helping with these documents please visit where I try to attempt to do one of the challenge each year to raise funds for Diabetes UK I'm yet again doing one on the 1st September 2021 (Thank you for your kind donations!)  

<a href="https://cycle.diabetes.org.uk/fundraising/UKWideCycleRide-DiabetesUK" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Diabetesuk/uk_wide_cycle_ride_.jpg" title="Diabetes UK Wide cycle Ride"/>





</font>

 <!--

<table width="1166" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><span style="color: #ffffff;">Note!  If you prefer video, see below</span></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">
<iframe width="850" height="415" src="https://www.youtube.com/embed/gUEqZAfPEZ4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  </span></td>
</tr>
</tbody>
</table>


-->


