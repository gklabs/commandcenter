# Commandcenter
*hmu @gkbytes on twitter if you want to collaborate or suggest features.*

The idea is to look at this at any point in time and  get a snapshot of your life situation and answer two questions.  
1. How are you ?
2. How is everything ?

## How are you ?
	Physically
		Body Temperature
		Body Weight
	Mentally
		DSM 5 captures a 
## How is everything ?
	Your home
		Is everything in its place ?
	Your Finances
		Do you have enough money to manage
			Food
			Medication
			Fees
	Your Groceries supply

Open [commandcenter.py](https://github.com/gklabs/commandcenter/blob/master/commandcenter.py) to take a look at the proposed functionality. The file is right now written to be rough in order to get an idea of what the application is going to look like. 

I will now explain modules that are proposed for development

## Cleaning up anything in your house using Computer Vision
Using your mobile phone's camera, take pictures/ videos of your house when it is both clean and at different stages of messy.
Suppose you take a picture of your table, a pretrained model can identify objects that are present. You decide whether the object present in the picture is 
* inplace
* outofplace

Suppose it is in place, you add a component to the 'cleanliness' of your room; else the object is identified to be put in its place.

## Drone module
Autonomous drones are now a reality. They are being used worldwide for surveillance, security, attacks and even perform humanly dangerous tasks like cleaning windows of tall structures. See here. 

For the purpose of commandcenter, 
1. an autonomous drone fitted with a HD camera and an [optical dust sensor](https://www.sparkfun.com/products/9689) can be trained to learn the interiors of the house and capture video and images of various objects. On sufficient training, a robust model can detect how dusty an object or a surface is and be able to display a progress bar like representation to say when the object needs to be dusted or cleaned. 
2. Identify inplace and out of place objects as described above.

## Integration with Voice assistants
With ever increasing presence of voice assistants 
