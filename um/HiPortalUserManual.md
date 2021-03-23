# Disclaimers

<span style="color:red;font-size:20pt;font-family:Segoe UI;">Important Notice</span>
<span style="font-size:16pt;font-family:Segoe UI;">Copyright © Hypontech. All rights reserved. <br>No part of this document may be reproduced, stored in a retrieval system or transmitted, in any form or by any means, electronic, mechanical, photographic, magnetic or otherwise, without the prior written permission of Hypontech.
The material furnished in this document is believed to be accurate and reliable. However, Hypontech assumes no responsibility for the use of this material. Hypontech reserves the right to make changes to the material at any time and without notice. You may refer to the Hypontech web site ([www.hypontech.com](https://www.hypontech.com)) for the most updated version. <br>All company and brand products and service names are trademarks or registered trademarks of their respective holders.
<br>The general terms and conditions of delivery of Hypontech shall apply. <br>The content of these documents is continually reviewed and amended, where necessary. However, discrepancies cannot be excluded. No guarantee is made for the completeness of these documents.
The images contained in this document are for illustrative purposes only and may vary depending on product models.</span>

# Overview

HiPortal is a renewable energy monitoring cloud based platform. It is designed for all energy generation, distribution and consumption system. This system allows distributors, installers and end users to manage single solar plants or a portfolio of customer sites. Equipped with remote upgrade and remote configuration, users are able to mange their assets from any part of the world.

This document describes the configuration and standard operation procedure of HiPortal as well as problems may occur along the operation of product user interface. 

This document is intended for all HiPortal users. 

<img src="https://i.loli.net/2020/12/18/Kjuqr43seaWD1yJ.png" align = "left" width = 1080/>

> ***All functions described in this document are demonstrated on:***
>
> * ***Google Chrome 84.0.4147.105 (64 bit)***
> * ***iPhone 11, iOS 14.2***

All problems regarding the HiPortal, please e-mail us at service@hypontech.com

# Required Inverter Models and Accessories

Please note that the availability of HYPONTECH products are region-specific. Cross-country distribution is strictly forbidden and will void all product warranty. Please contact your local distributor or wholesaler to consult about HYPONTECH product models.

Technical details of products are available on Hypontech.com.

The following product models are supported with data communication via HiPortal App:
**Grid-tied Inverters**

- HPK-1000, HPK-1500, HPK-2000, HPK-2500, HPK-3000 (*Single Phase, 1 MPPT*)
- HPS-1500, HPS-2000, HPS-2500, HPS-3000, HPS-3000L, HPS-3680, HPS-4000, HPS-5000, HPS-6000, HPS-6500 (*Single Phase, 1 MPPT/2 MPPTs*)
- HPS-7000, HPS-8000 (*Single Phase, 2 MPPTs*)
- HPT-3000, HPT-4000, HPT-5000, HPT-6000, HPT-8000, HPT-10000, HPT-11000 (*Three Phase, 2 MPPTs*) 
- HPT-15K, HPT-17K, HPT-20K, HPT-25K (*Three Phase, 2 MPPTs*)
- HPT-33K, HPT-40K, HPT-50K (*Three Phase, 3 MPPTs/4MPPTs*)

 **Storage Inverters**

* HHS-3680, HHS-4000, HHS-5000 (*Hybrid Single Phase, 2 MPPTs*)

* HBS-3680, HBS-4000, HBS-5000 (*AC-Couple/Retrofit*)

 **Communication Devices**

* Wi-Fi Stick (*Plug-and-play, Wireless Access Point*)
* GPRS Stick (*Plug-and-play, 2G SIM Card*)
* HiManager (*RS485 and Wireless Access Point, for plants with multiple devices*)

# System Structure

## Module Map

 The major modules of HiPortal are shown as diagram below:

 <img src="https://i.loli.net/2021/01/12/bPuNkVntHUQi3qJ.png" alt="modules" width=600 />

## Roles and Authorizations

HiPortal has a four-layer role structure, which are:

| Role         | Description                                                  |
| ------------ | ------------------------------------------------------------ |
| Manufacturer | Refers to Hypontech                                          |
| WholeSaler   | A business entity imports and distributes Hypontech Products |
| Installer    | A business entity or individual purchases Hypontech Products from a WholeSaler |
| End-User     | The owner of solar plant                                     |

The Authorizations of certain role can be seen on the left side menu of the screen, Backstage/User Management. The visibility of this menu function is differ according user's role.

# Get an account

There are multiple ways to register for a new HiPortal account:

* [Self Register](#self-register)
* [Register for your client](#register-for-your-client)

## Self Register

<table>
    <tr>
        <td><img src="https://i.loli.net/2021/01/12/yODk1gzHjiwrY9C.png" width = 600 /></td>
        <td><img src="https://i.loli.net/2021/01/12/URMbt3uWTECwjoY.png" width = 600 /></td>
    </tr>
    <tr>
        <td>[Click Here](#Registration)</td>
        <td>[Click Here](#Registration)</td>
    </tr>
</table>

 <img src="https://i.loli.net/2021/01/12/yODk1gzHjiwrY9C.png" width = 600 />

1. Open a web browser on your PC, laptop or tablet;

2. Key in [www.hyponportal.com](www.hyponportal.com) in the address bar;

3. Click on **Register**

 <img src="https://i.loli.net/2020/11/09/MKJ9QdmbtgEawT4.png" alt="image-20201109143654369"  width=600 />

4. Type in your email address and click **Send code** button:

 <img src="https://i.loli.net/2020/11/09/HbK9qfT1GRS7VFW.png" alt="image-20201109143913542"  width=600 />

5. A confirmation code will be sent to your designated email address. The code is in 4 digits and valid for 5 minutes.

 <img src="https://i.loli.net/2020/11/09/PBWne2AY4uU5NC1.png" alt="image-20201109144124228"  width=600 />

6. Back to web browser and type in the confirmation code.

 <img src="https://i.loli.net/2020/11/10/2EgRhKyIJ8kqbQF.png" alt="image-20201109144627990" width=600 />

6. Set your password. Valid password should be:

   * More than 6 digits
   * Contains at least 1 digit number and 1 digit alphabetical letter

<img src="https://i.loli.net/2020/12/18/Kjuqr43seaWD1yJ.png" align = "left" width = 1080/>

> **The password is case sensitive!**

<hr>
 <img src="https://i.loli.net/2021/01/12/Xe7gNtqASDabcxz.png" alt="image-20210112145842791" width=600 />

8. Check the box to agree with the User Terms and Agreements.

9. Click on **Register** button to complete the registration.

Now the user can login the HiPortal with the email address and password set.

For the first time user, the account setting page is appeared. User **must** fill in Nickname, Company Name and Country/Region before any further operation.
			<img src="https://i.loli.net/2020/11/10/I4kjNFz9Cy26HRY.png" alt="image-20201109145111642" style="zoom:33%;" />

 <img src="https://i.loli.net/2021/01/12/URMbt3uWTECwjoY.png" width = 600 />

1. Enter HiPortal App<br>
   <img src="https://i.loli.net/2020/11/23/e3WOYgfQZjhwV2S.png" alt="image-20201123135859773" style="zoom:50%;" />

2. On the Login page, tap on Sign Up<br>
   <img src="https://i.loli.net/2020/11/23/LTxFrM5PlRB4y6s.png" alt="image-20201123140220099" style="zoom:50%;" />

3. Fill in account details:<br>
   <img src="https://i.loli.net/2020/11/23/VF1ZbUQl36uJONn.png" alt="image-20201123140612504" style="zoom:50%;" />
   a. E-mail address
   b. Password (case sensitive; at least 1 number, 1 uppercase letter 1 lowercase letter; 6-16 digits)
   c. Repeat the password to be sure
   d. Press Send button to get verification code, the code will be sent to the e-mail address filled in a as such form:

   <img src="https://i.loli.net/2020/11/23/WnHJmwyFcr1bSsN.png" alt="image-20201123141219672" style="zoom:50%;" />
   e. Fill in the verification code here
   f. Tick the box to agree with the terms and agreements
   g. Tap on Submit

<img src="https://i.loli.net/2020/12/18/Kjuqr43seaWD1yJ.png" align = "left" width = 1080/>

> All accounts registered in the App are End-User Accounts.
> To register an installer account, please contact your Wholesaler.

<img src="https://i.loli.net/2020/12/18/Kjuqr43seaWD1yJ.png" align = "left" width = 1080/>

> When you cannot receive registration e-mail, check if:
> * E-mail address is invalid or entered incorrectly
> * Your phone has no internet connection
> * Registration e-mail is moved to junk mail folder
>
> And if none of above worked for you, please send an inquiry e-mail to [service@hypontech.com](mailto:service@hypontech.com)

## Register for your client

***This function is developed only for distributors and installers***

Click [**here**](#Add new user), jump to chapter under User Management.

# Add a new site



# Pilot View

![image-20201109171740605](https://i.loli.net/2020/12/28/7YPjw5ctxv6ROhD.png)

Screenshot above is the default interface of HiPortal after login. It is also known as the Pilot View. It gives the user an overview of operating status of all solar plants.

![image-20201110152820689](https://i.loli.net/2020/12/28/KCOkax1igS5d6RF.png)

1. On upper left corner, there is the HiPortal Icon. It shows on all pages of this portal. User can jump back to Pilot View from any page.
2. The menu is on the left. Different amount of items are shown according to role and authorizations of each account. Screenshot shows the complete set of items. The menu can be folded into icon mode gives user more space.
3. ***[Under Construction]*** The dashboard mode gives users to show the system on a big screen in a launch control style. Usually it is used in a show room.
4. ***[Under Construction]*** Shows the in-site messages from other user.
5. Switch languages, languages available:
   - English
   - Chinese
   - Portuguese
   - Vietnamese
   - Polish
     *<br><span style="color:blue;font-size:11pt;font-family:Segoe UI;">Special thanks to clients of Hypontech contribute to translation of the terms.</span>*
6. Shows your WIE ID and nickname. It is also a linked button to Account Setting page.
7. Shows a bar chart for all plants' generation in the last 30 days.
8. Shows an overall status of all plants.
9. Shows sum of plants in different status.
10. Shows the earning of the account and the environmental data.
11. Enlisted plants under the account.





# Plant Management

## Add New

- 

### Add new device

The system allows a plant without any device. Thus, the plant created by Add New function is empty. User needs to add new gateway to the plant. Further, the gateway will read and transmit inverter data onto the HiPortal.

Please click here to see the method of adding new devices.

## Plant Overview

Plant Overview / Plant List is the default page open when clicking on Plant Overview on left side-bar menu. It shows a complete list of plants owned by the user logged in and plants owned by subordinate users. On this page, user many easily find and configure a plant or an inverter installed in the plant.

<img src="https://i.loli.net/2020/11/10/247cd9AJZwu8smj.png" alt="image-20201110155928606" style="zoom: 67%;" />

- Search by WIE ID of a plant owner
  ![image-20201110160020074](https://i.loli.net/2020/12/28/XM3b4vYmlGL1VD6.png)

- Search by location of the plant
  ![image-20201110160121169](https://i.loli.net/2020/12/28/u1t6ZPTrJw2iWnO.png)

- Search by Plant Name
  ![image-20201110160204996](https://i.loli.net/2020/12/28/wCUFILpG23a8J7K.png)

- Plant Table
  ![image-20201110160252973](https://i.loli.net/2020/12/28/WyZJam8kcspNor2.png)

- By clicking the plus (+) sign, the plant will unfold and show the inverters under specific plant.
  <img src="https://i.loli.net/2020/11/10/MYponcgbZ8iVNTq.png" alt="image-20201110162901588" style="zoom:67%;" />

- More button gives options user can operate to the plant or inverter
  ![image-20201110163100584](https://i.loli.net/2020/12/28/r1MP85YH64daltB.png)


  <img src="https://i.loli.net/2020/11/10/3EJq1N26nCRTfMI.png" alt="image-20201110163133637" style="zoom:67%;" />

- More Functions

  - Plant

    - Edit
      Jump to the interface which allows the user to edit detail information of the plant. The interface is the same as [Add New](#Add New)
    - Add Gateway
      ![image-20201110163621413](https://i.loli.net/2020/12/28/pBlJeQvjAgSaHzq.png)
      ![image-20201110163642794](https://i.loli.net/2020/12/28/TLiODtKp6EJ7qAf.png)
      Key in the SN number printed on the Gateway Stick. Multiple entries are allowed by click on the plus (+) sign.
    - Delete
      ![image-20201110163836545](https://i.loli.net/2020/12/28/nkX4pDTq9JErbBS.png)
      To avoid misoperation, user need to type in DELETE (Case sensitive) into the input box to confirm the action.
    - FFR
      <img src="https://i.loli.net/2020/11/10/wlgW6a4ZP9JOF3U.png" alt="image-20201110164257669" style="zoom:67%;" />
      It is a direct contact channel to Hypontech supporting engineer. Fill more information would largely help problem solving.
    - Transfer
      ![image-20201110164446198](https://i.loli.net/2020/12/28/QBb6WgPuqpGSzY9.png)
      It is the function to transfer the ownership of entire plant to another user. Target user's WIE ID is needed.

  - Inverter

    - Detail
      Jump to Plant Management/Plant Chart

    - Configure
      User may able to adjust inverter configurations. 

      ![image-20201110164805939](https://i.loli.net/2020/12/28/9nGXY7WxyLgb1kj.png)

    - Unbind
      To delete this inverter from the plant. Key in capitalized UNBIND to confirm.
      ![image-20201110164944735](https://i.loli.net/2020/12/28/dfweBuc7pztPso8.png)

    - Set Alias
      ![image-20201110165116831](https://i.loli.net/2020/12/28/dk5KcEfMNi92Rxa.png)
      Give an alias to an inverter. Such as "North side", "South side".

    - Debug
      <img src="https://i.loli.net/2020/11/10/xgo2GyehAHOk4Li.png" alt="image-20201110165255434" style="zoom:67%;" />
      To send command to inverter and get response.

    - FFR
      <img src="https://i.loli.net/2020/11/10/vcydBfEguDtGxVn.png" alt="image-20201110165430332" style="zoom:67%;" />
      System will automatically read the specific information from the inverter. Hypontech supporting engineer will receive the FFR and help to solve the problem.

### Plant Management / Plant Chart

This page shows when clicking on an individual plant on the plant list.

![image-20201112102444762](https://i.loli.net/2020/12/28/rKsCcATolpX1WVm.png)

### Plant Management / Device - List

Clicking on Device - List, the page will jump to screenshot as such:

![image-20201112102738218](https://i.loli.net/2020/12/28/s63LHBJkcfgzqn2.png)

It gives a complete list of inverters and gateways installed in this plant in a form of table. On this table, it shows the inverter SN/Alias number, type of the inverter, current power and current / nominal power ratio,  gateway SN, gateway type. The thin black line connecting the plant, inverter and gateway briefly shows the physical connection structure.

On the top of the table, user may search the inverter by inverter SN/Alias, in case there are a large number of inverters installed. **Add New Gateway** button allows user to bind more inverters into the plant by adding new gateway.

NOTE: *If the plant installed HiManager which has the ability to connect to multiple inverters, when user installed more inverters connected to HiManager, there is no further operation needed on HiPortal platform.*

**Split** button grants distributors or installers to install multiple plants and put in the same plant on HiPortal. Later on, use **Split** function to divide the inverters to multiple plants in order to match the actual situation. After splitting, those plants can be transferred to actual plant owners with **Transfer** Function.

### Plant Management / Device - Detail

This page shows the overall status of an individual inverter.
<img src="https://i.loli.net/2020/11/12/EGykqFpCaglxS96.png" alt="image-20201112105134037" style="zoom:67%;" />

- Export this page: Create a downloadable pdf file of current page.
- Click on the SN, user can shift inverters to view.
- Data / Graph switch button: shift view form chart to table.
  ![image-20201112111421228](https://i.loli.net/2020/12/28/moZg4PVY6zEDpBx.png)
  The table shows the working data of current inverter on the selected day.
- Factor selection box: Click the check box, user can add another curve onto the graph, such as:
  <img src="https://i.loli.net/2020/11/12/4jXonMNkhy76UEO.png" alt="image-20201112105515560" style="zoom:80%;" />
  NOTE: *HiPortal allows max. 2 unit simultaneously, e.g. If existing selection is Voltage and Power which the units are V and W, when adding current factor, voltage or power factor will be cleared (depending on clicking order).*
- Date selector: the date selector allows 30 days max. The range can be selected on such interface:
  ![image-20201112111008478](https://i.loli.net/2020/12/28/2Hm4BFlzLyat7vj.png)
- Day / Month Switch: switch between daily data and monthly data.
- ![image-20201112111157475](https://i.loli.net/2020/12/28/CXovjYnFl8U6VDf.png)Icon: Allows user to generate a png, pdf, or excel file to download of current graph.

### Plant Management / Event

Event page gives a table of events on current plant, including warning, fault information. 
![image-20201112111722876](https://i.loli.net/2020/12/28/PDhdnsGW61ATwIS.png)

User can click on the more button to claim the problem is solved or file an FFR to Hypontech for technical support.

# Device Management

## Inverter

<img src="https://i.loli.net/2020/11/10/KtAF1aGNuo47UlC.png" alt="image-20201110165637148" style="zoom:67%;" />
A table lists all inverters.

The more button gives the options operating on individual inverter. Please [read Chapter Plant Overview](#Plant Overview), sector more function for more information.

## Gateway

<img src="https://i.loli.net/2020/11/10/3hBy5j7rWUFmb8H.png" alt="image-20201110165734227" style="zoom:67%;" />
A table lists all gateways.

# Firmware Management

[^1]: Authorization needed

It is a function used by Hypontech to mange inverter/gateway firmware and remote upgrade. It is also allowing batch upgrading.
<img src="https://i.loli.net/2020/11/10/3hBy5j7rWUFmb8H.png" alt="image-20201110165918047" style="zoom:67%;" />

# User Management

[^1]: Authorization needed



## Add new user

 <img src="https://i.loli.net/2021/01/12/yODk1gzHjiwrY9C.png" width = 600 />

By this function, a distributor or installer can create a new account for its client. Please follow the steps:

1. Select one of the role as target role, for instance: **Installer**;
   <img src="https://i.loli.net/2020/11/10/RBnQzluV93o5wbc.png" alt="image-20201109153127317" style="zoom:33%;" />

2. Click on **+ Add New User**;
   <img src="https://i.loli.net/2020/11/10/a6Ll7qMpouQEOzk.png" alt="image-20201109153004632" style="zoom:33%;" />

3. A window will pop up on your screen;
   ![image-20201109153828727](https://i.loli.net/2020/12/28/ZvBzwfQNCOFp1ID.png)

   | No   |                       | Description                                                |
   | ---- | --------------------- | ---------------------------------------------------------- |
   | 1    | Target E-mail address | Type in new user's E-mail address                          |
   | 2    | Password              | Password is automatically generated by system              |
   | 3    | Copy                  | The password will copy to clipboard by clicking the button |
   | 4    | Upper stream user     | The WIE number which the new user will bind under          |
   | 5    | Create                | Finish creating by clicking                                |

   

4. A notice will be sent to the E-mail filled in to inform the password. And the WholeSaler or Installer can always pass on password to the client by pasting the password into instant messaging software.

## User Account Edit

 <img src="https://i.loli.net/2021/01/12/yODk1gzHjiwrY9C.png" width = 600 />

1. Click to select the role of the client, then use the search bar to find the client;<img src="https://i.loli.net/2020/11/09/WLxTejnkRN4UYIb.png" alt="image-20201109162102371" style="zoom:33%;" />

2. You can search by WIE ID, Nickname or Account (E-mail address);
   ![image-20201109162244368](https://i.loli.net/2020/12/28/6h2QKPNVsIpMZJW.png)

3. Click on more button to activate popup;
   <img src="https://i.loli.net/2020/11/09/qNMaTCZ7zBmELjl.png" alt="image-20201109162337702" style="zoom:50%;" />

4. Several functions can be done on this popup:

   <img src="https://i.loli.net/2020/12/28/QxfMPlbmUvw4DZJ.png" alt="image-20201109163450348" width = 450 align="left"/>

   1. By clicking on **Reset Password** (1) button, Upper-stream account can reset password for a client. A notice mail will be sent to this client's E-mail address. Upper-stream account user can also click button (2) to copy new password to clipboard.
   2. By clicking on **Unbind** (3) button, this client will break the link to Upper-stream account.
   3. Now, this client's account is available to switch role levels and bind under other account.
      <img src="https://i.loli.net/2020/11/10/I6zZCjqmhRiP2t5.png" alt="image-20201109165854636" style="zoom: 50%;" />

## View detail

 <img src="https://i.loli.net/2021/01/12/yODk1gzHjiwrY9C.png" width = 600 />

Click any part of red box area, the user detail popup window shows.

 <img src="https://i.loli.net/2020/11/10/MdyNbz85gpQIfv2.png" alt="image-20201110171058038" width=800 />

Plants/Inverters/Gateways owned by this account is shown on the right.

Upper-stream account's WIE ID to this account is shown under the avatar.

 <img src="https://i.loli.net/2020/11/10/htYj1wqo2FApkSC.png" alt="image-20201110171035137" width=400 />

A list of down-stream account to this account will shown by clicking on the red button **View Subordinate**.

# Messaging

**[Under Construction]**

# Log

**[Under Construction]**

# FFR

**[Under Construction]**

# Alerts

**[Under Construction]**

# CONTACT

Please jump to this page:  [Contact](Contact.md) to view detailed contact info.