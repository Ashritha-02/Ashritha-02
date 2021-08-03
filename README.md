	Create a database for IoT simulator with the following tables.
Device_details (deviceID, devicename, properties)
Connect_status(deviceID, loginTime, logoutTime)
Transaction_details(transID, deviceID, updatedProperties, timeofUpdation)
i.	List the details of the devices that are connected in a particular session
ii.	Display the details of the device and its property that has been active for most of the time.
iii.	Develop a PL/SQL procedure that deletes the details of the devices that have been least updated.
