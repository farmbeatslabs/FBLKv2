Register your FarmBeats Lab Kit User and Device
===================================================

To get your FarmBeats Lab Kit devices connected to the cloud you need to
register the unique ID from each device and get it provisioned to the Azure IoT
Central Cloud Service.

The FarmBeats Lab Kit portal makes this easier for you by providing you with
a simple way to register your user and then your device so configuration of the
cloud service is done for you.

*Note: It is recommended that you start your web browser in a Private Mode to
avoid conflicts with the username that you might already being logged into other
sites with.*

Register your user at the FarmBeats Lab Kit Portal
------------------------------------------------------

-   Please check the URL on the outside of the Lab Kit and visit the portal using that URL.

-   To login for the first time click either the Login or the Activate Your Kit
    button on the home page. Note: In the top right of the page it will show if
    you are logged in already. If you are already logged in with an account that
    you don’t want to use for the Lab Kit then log out and visit the page
    again.

![](media/0fa4559111333367aeab004c8cbaab80.png)

-   At the login page, either select the account you want to log in with or use
    another account.

![](media/63d98a1de0e5842d1de6883de4079a7b.jpg)

-   Enter your user name and password.

*Note: If you don’t already have a Microsoft Work or School account or a
Microsoft Account like an Outlook, Live or Hotmail user name then this process
will create a MSA on top of your existing email address.*

-   If it’s your first time logging in then you will be redirected to the User
    Registration Page. If you have logged in before you will need to select
    Activate your Kit from the Getting Started section.

![](media/b102044e9142091ac6a75925691bc408.png)

-   On the registration page your name and email address will already be
    provided from your login account. Continue to fill in the remaining
    information.

-   If you are registered as part of an organization then you will need to also
    fill out any information the might be customized specific to the
    organization you are affiliated with.

![](media/2af1dc580ba7df2412266bf30187d2a2.png)

-   *Note: when you try to type the address in the address field it’s only going
    to accept from the nearest town and not to the exact address.*

-   Once you have filled out the form you will need to select any confirmation
    boxes for policies on this page.

-   Submit the form to complete the account creation. You have now registered
    your user.

-   From there the next steps are to register your device or devices.

Register your devices
---------------------

*The FarmBeats Lab Kit cloud service is provided for free 2 devices
limit per user. Any additional devices over the 2 device limit will incur cost.
Devices added over the free limit will be programmatically removed unless
billing information is provided. Please* [contact
us](mailto:support@farmbeatslabs.com) *to arrange.*

-   To register your Lab Kit device you are going to need a unique **Device
    ID** to use as the claim code. The Device ID that we use is from the Mac
    address of the LAN adapter on your Raspberry Pi. 

- On the back of your device will be a Device ID code that you can use to register the device.  

![](media/RPi_DeviceID.jpg)

- You will used this code as the Device ID on the device registration page. 

![](media/5480cbfabe1fd2e98fe9d0698ba54ec8.png)

-   When you have registered your first device the provisioning process will
    start and the portal will generate your Azure IoT Central application and
    add your device.

-   When the provisioning process is complete you will be sent a confirmation
    email and be redirected to the Lab Kit Portal profile page.

-   In the email and on the profile page you will be able to see your Azure IoT
    Central URL. There is a copy icon beside this field to copy the URL to the
    clipboard.

![](media/ce49fc97053af0332676b55bf3049420.png)

### User account and device registration complete

-   You have now completed the User and Device registration and the Azure IoT
    Central application has been created and your device has been added to your
    cloud application. You can now proceed to [Step 3 – Configure your Azure IoT
    Cloud
    Service](https://github.com/farmbeatslabs/fblkv2/blob/master/Indoor-m1/3_Configure_your_Azure_IoT_Central_Cloud_Service.md)

### Register a second device

-   If you have a second device to register you can do it here by pressing the
    “Add Device” button.

![](media/f1af29bc8a27778a52e7596337ccc223.png)

-   You will receive an email for every device you add.

![](media/4ac2b44a24ea0f0381ca40ebfea83e8d.png)
