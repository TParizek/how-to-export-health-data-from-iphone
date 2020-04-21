# How to export health data from iPhone?

1. Open the Health app
2. Click on your profile photo
3. Click on “Export All Health Data”
4. Click on “Export”

<p align="center">
      <img src="https://github.com/TParizek/how-to-export-health-data-from-iphone/raw/master/images/1.png">
</p>

It is going to take a few seconds/minutes for your iPhone to create the export. The result will be a zip file containing all of your health data. You can share this zip via AirDrop. I would not recommend you sharing it via an email, because the export is going to large (hundreds of MBs, maybe even GBs).

<p align="center">
      <img src="https://github.com/TParizek/how-to-export-health-data-from-iphone/raw/master/images/2.png">
</p>

The result ZIP file contains:
- electrocardiograms: ECG records
- workout-routes: GPS locations from your workouts (.gpx format)
- export.xml and export_cda.xml: Health records

---

I am glad Apple gives us a way of exporting the Health data, but there are some major limitations:

1. You can not specify health types you want to export.
2. You can not specify dates you want to export.
3. Health data are exported into an XML file with unnecessary complex structure.

It was frustrating for me to export health data with these limitations, thus I have decided to create an app, which would allow users to export specific health data in a specific time period while using a format that would be more usable.

<p align="center">
      <img src="https://github.com/TParizek/how-to-export-health-data-from-iphone/raw/master/images/3.png">
</p>


In the HealthExport app, you can **specify health types** and **dates** you are interested in. Health types are divided into two groups:

1. Cumulative based measurements (e.g step count): Export can be aggregated by hours, days, or months
2. Record based measurements (e.g body mass): Export contains all entries

The app exports data into a **CSV file**, which can be opened in Excel.

<p align="center">
      <img src="https://github.com/TParizek/how-to-export-health-data-from-iphone/raw/master/images/4.png">
</p>

You can get HealthExport from the [AppStore](https://apps.apple.com/cz/app/health-export-csv/id1477944755). More informations are available at [healthexport.app](https://healthexport.app/)

If you have any issues or questions while using the HealthExport app, do not hesitate to contact me via email address: [hello@healthexport.app](mailto:hello@healthexport.app)