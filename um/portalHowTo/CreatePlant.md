# On Web Portal

On this page, user may add a new plant.

 <img src="https://i.loli.net/2020/11/10/f1AkJUMBglSXeoL.png" alt="image-20201110154223797" width =800 />

There are two pages of information which is needed to complete the operation.

- Plant Parameters

  - Plant Name: [Mandatory] Give a name to this new plant. The system gives [Nickname + 3 digits random number] as a default plant name.
  - Capacity: [Mandatory] Sum of all solar panels power in kWp.
  - Install Date: [Mandatory] Date of today as default. Adjustable.
  - Start Generation Adjustment: If the plant started generation before the user created the new plant, user can always put a power generated here.
  - Plant Type: 
    - Grid Plant: a grid-tied system
    - Grid Storage: a grid-tied system with energy storage
    - Off-grid Storage: a off-grid system with energy storage
  - Unit Price: [Mandatory] 
    - Type:
      - Fixed Rate: The FIT is paid in a fixed rate.
      - Peak/off-peak: The FIT is paid according to generating hour of the day.
      - On-Ladder: The FIT is paid according to the amount of the generation.
    - The unit FIT (Feed in tariff) price. Please confirm it is using the right currency.
  - Set Plant Picture: User can put a photo of the plant. (a real plant shot appreciated)

   <img src="https://i.loli.net/2020/11/10/y4YLxzrVA3F2Ofv.png" alt="image-20201110155529389" width = 800 />

- Additional Info:

  To give geographic information of the plant. Country/Region and Time zone is mandatory.

# On HiPortal App
In order to monitor and configure the inverter and devices in your PV system, create a plant in HiPortal App. In plant editing page the parameters can be changed at all times once the plant is created.

**Requirements:**

To ensure correct readings of performance and quality of service, Currency, Country, Installed Capacity and Time Zone must be filled correctly.

**Procedure:**

1. In PLANTS, tap on the “+” widget on top right corner.

2. The following information of the plant must be filled correctly: 

- Name

- Capacity

- Time Zone

- Country


3. Select NEXT

4. If you wish to add a communication device (e.g. a Wi-Fi / GPRS Stick) to the plant you just created, select ADD MONITOR.

5. Scanning the QR Code on communication device(s) will be added to the plant.

Otherwise, select DONE. To add new devices to this plant, refer to [Adding New Devices](#Adding New Devices). 

The plant parameters can be changed. Please refer to **5.2** for editing plant parameters. 

**NOTE:**

Currency and Income Factor are important parameters to determine your ROI indicators and some display features in plant. Inappropriate numbers may cause display of performance to be misleading.

Once the plant is created, many calculations in HiPortal will rely on these 2 inputs. It is strongly recommended to double check and enter them correctly.

**NOTE:**

Devices need to be configured with working internet connection to be displayed in a plant. For example, GPRS Sticks, configured Wi-Fi Sticks and HiManager.

Please refer to 5.3 for internet configuration of Wi-Fi Sticks.
