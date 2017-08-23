[![Project Status](http://opensource.box.com/badges/active.svg)](http://opensource.box.com/badges)

Configurable Time Entry Lookup intervals 
==================================
An extension that allows to have time entry lookup intervals configurable.

### Prerequisites
* Acumatica 5.30.3428 or higher
* Acumatica 6.10.0269 or higher

Quick Start
-----------

### Installation

##### Install the customization deployment package
1. Download PXConfigurableTimeSpanExtPkg.zip from this repository
2. In your Acumatica ERP instance, navigate to System -> Customization -> Customization Projects (SM204505), import PXConfigurableTimeSpanExtPkg.zip as a customization project
3. Publish the customization project.

### Usage

1. Go to Time & Expenses Preferences Screen (EP101000) and specify the interval you need.
![Screenshot](/_ReadMeImages/EP101000.png)
2. Navigate to Employee Time Card Screen (EP305000) and Time Span Lookup for Mon, Tue, Wed, Thu, Fri, Sat, Sun columns in Summary tab and Time Spent, Billable Time columns in Details tab will be based on interval specified in step # 1.
![Screenshot](/_ReadMeImages/EP305000.png)

Known Issues
------------
None at the moment

## Copyright and License

Copyright © `2017` `Acumatica`

This component is licensed under the MIT License, a copy of which is available online [here](LICENSE.md)
