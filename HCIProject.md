
# RECON-KIT (Reconnaissance Kit )
# What is the RECON-KIT (Reconnaissance Kit )
---
<p style="text-align: justify;">It’s essentially a standalone device that can be easily attached to anything, from drones to cars, or even carried as a personal item. There are two versions of the kit: one is a cellphone app compatible with Android smartphones running Android 5 or above, and the other is an easy-to-assemble solder kit with 3D-printed parts including a custom phone case that is mountable.</p>

## What does the RECON-KIT (Reconnaissance Kit ) do?
---
<p style="text-align: justify;">Leveraging the variety of sensors installed in an Android smartphone, along with highly customizable modular electronic sensors, the device functions as a reconnaissance tool. Essentially, it acts as a reconnaissance drone, drawing inspiration from surveillance aircraft. Imagine the capabilities of a surveillance aircraft condensed into the form factor of a smartphone with easily swappable modular parts.</p>
## Use for the the RECON-KIT (Reconnaissance Kit )
---
	<p style = "text-align: justify">Inspired by the concept of war driving—also known as access point mapping, which involves locating and exploiting connections to wireless local area networks (WLANs) while driving around a specific location—this approach is enhanced by incorporating military surveillance vehicles that scan and analyze radio waves. The device, which functions both as a stand-alone tool and as a smartphone app, is designed to analyze and map wireless data within a given area. This technology is particularly useful for professionals in cybersecurity, the military, and law enforcement, providing them with enhanced tactical awareness by identifying and understanding the wireless signals in their environment.</p>

# The Stand Alone Kit
---
- # Modular Parts that are in use 
	- ## Data Gathering/Reconnaissance Parts
		![[Pasted image 20240811130537.png]]
			<p style="text-align: center;">Common Wifi Module</p>
		-  **Modular Wifi Sensors**: <p style ="text-align: justify;">The kit mostly consists of an ESP microchip for wireless communication, which can be used to capture Wi-Fi signals in an area. This is particularly useful for detecting different encryptions and security protocols on Wi-Fi networks. It can also help identify the presence of someone in what appears to be a rural or isolated area by detecting Wi-Fi signals. This capability can be further enhanced with signal boosters.</p>
			
			![[Pasted image 20240811131153.png]]
				<p style="text-align: center;">Wifi Booster (2.4GHz to 2.5GHz range)</p>
			**Wifi Booster Modules:** <p style="text-align: justify;">Wi-Fi booster modules can also be used in tandem with the stock Wi-Fi sensor/module, but they may drain the power pack of the standalone device more quickly. These boosters are effective in the 2.4GHz to 2.5GHz range. By using a directional antenna, such as a Yagi antenna, the signal can be further narrowed and focused, enhancing detection accuracy and range.</p>
			![[Pasted image 20240811213721.png]]
				<p style ="text-align: center;">GPS Module</p>
		- **GPS Module:** <p style ="text-align: justify;"> This is typically used to determine the current location of an object or the RECON-KIT (Reconnaissance Kit). GPS modules gather location data in different ways. Common or more affordable versions often use the triangulation method, which calculates a 'general location' rather than an exact pinpoint. In this method, the device scans for nearby cellphone towers and uses at least three of them to triangulate its general location. The more towers it can detect, the more precise the location becomes. Other GPS modules connect directly to a satellite, which can take 15 to 30 minutes or more, depending on the satellite's position. If the device loses power or its connection to the satellite, the location data it receives will be lost.</p>
			
			![[Pasted image 20240811222023.png]]
				<p style = "text-align: center">Bluetooth Module</p>
		- **Bluetooth Module:** <p style ="text-align: justify;"> While not as powerful or long-range as Wi-Fi or radio, Bluetooth still has the capability to detect nearby devices. Since Bluetooth typically has higher transmit power when a device is close by, it can be easily detected. </p>
			![[Pasted image 20240812214304.png]]
			<p style = "text-align:center;">Camera Module with IR (Infrared) Sensor</p>
		- **Camera Module With IR Sensor:** <p style = "text-align: justify">This is usually intended for visual representation of the location of a specific standalone RECON-KIT (Reconnaissance Kit). It is preferable to use analog cameras rather than digital ones, even though analog cameras have lower quality and resolution. Analog cameras can withstand various weather conditions and can broadcast an image much farther than standard digital ones. </p>
	- ## Data Transmission Parts

		![[RadioTransmission.png]]
			<p style = "text-align:center;">Radio Transmission Method Diagram</p>
		
		- **Radio Transmission:**
		<p style ="text-align:justify;">Converting all the data gathered by sensors into a form of sound transmission—these sound transmissions could take the shape of SSTV (Slow Scan Television) or involve image processing that converts an image into sound to be decoded. Alternatively, the data could be transmitted similarly to how NOAA radio transmitters work, providing audio-generated data that dictates the current state of the device.</p>
		
		![[ServerClientModel.png]]
			<p style = "text-align: center;">Client to Server Method Diagram</p>
		- **Client to Server:**
			<p style ="text-align:justify;">If an internet connection is available, it's possible to send data through the internet to a remote server where the gathered data is stored. Cloud storage is not recommended because it is owned by private entities that can change their policies and potentially leak data to a threat actor.</p>
		
		![[MeshNetwork.png]]
			<p style ="text-align:center;">Mesh Network Diagram</p>
		- **Mesh Network Connection:**
			<p style ="text-align:justify;">A mesh network type of data transmission is ideal for scenarios where traditional communication channels are scarce, and no internet connectivity is available. This approach embodies the concept of decentralized communications, as there are no central servers to store or transmit data. Instead, data packets are stored and transmitted across nodes within the network. In this context, these nodes could be standalone devices such as the RECON-KIT (Reconnaissance Kit) or smartphones equipped with similar functionality. The strength of a mesh network lies in its distributed nature—the more nodes that are part of the network, the greater the coverage and data-gathering capabilities. These nodes can be strategically scattered across an open area, enabling them to communicate with one another in tandem, thus creating a robust and resilient communication network even in the absence of traditional infrastructure.</p>

## Smartphone Version RECON-KIT (Reconnaissance Kit )
---
- ## App functions  
	- **Using of GPS Sensors:** <p style = "text-align: justify;"> Smartphone GPS technology is far more robust than most freely available alternatives on the market. It's not new knowledge that many high-end GPS modules for certain embedded systems are derived from actual smartphones. These modules, like most high-end GPS systems, can also take 15 to 30 minutes to pair with a GPS satellite.</p>
	- **Using of Camera** <p style = "text-align: justify">Its going to be hardcoded that the use of camera for the app will be particular be useful in any situations the RECON-KIT (Reconnaissance Kit ) will be used.</p>
	- **Using of GSM Module** <p style="text-align: justify;">Sending data via SMS is a practical method for transmitting valuable information without relying heavily on internet connections. This approach can be particularly useful in situations where internet access is limited or unreliable, as SMS does not require a continuous connection and can operate on basic mobile networks.</p>
	- **Sending data via internet** <p style ="text-align:justify">If an internet connection is available, it's possible to send data through the internet to a remote server where the gathered data is stored. Cloud storage is not recommended because it is owned by private entities that can change their policies and potentially leak data to a threat actor.</p>

# Mock-up and Prototype
---
- # Mock-up APP 
	![[MockUPGPS 5.png]]
	![[MockUpGPSMap01 1.png]]
	![[MockUPMonitoringGPS 1.png]]

- # Prototype Enclosure
	![[PrototypeCase.png]]
	
	![[MockupScreenShot.png]]
	![[Mockup03.png]]
	![[Mockup02.png]]
- # Stand-Alone Components 
	![[Components.png]]