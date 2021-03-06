---
title: "Add OleObject to Excel Worksheet"
type: docs
url: /add-oleobject-to-excel-worksheet/
weight: 20
---

## **Introduction**
This example shows how to add an OleObject to a worksheet, using Aspose.Cells Cloud API in your applications. You can use our REST API with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/cells/{name}/worksheets/{sheetName}/oleobjects|PUT|Add an OLE object in worksheet|[PutWorksheetOleObject](https://apireference.aspose.cloud/cells/#/OleObjects/PutWorksheetOleObject)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X PUT "http://api.aspose.com/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet1/oleobjects" -d '{"ImageSourceFullName":"aspose-logo.png", "IsAutoSize":true, "SourceFullName":"Sample_Book2.xls", "UpperLeftRow":15, "Top":10, "UpperLeftColumn":5, "Left":10,"Width":400, "Height":400}' -H "Content-Type: application/json" -H "Accept: application/json"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{

  "OleObject": {

    "DisplayAsIcon": false,

    "FileFormatType": "Default",

    "ImageSourceFullName": "aspose-logo.png",

    "IsAutoSize": false,

    "IsLink": false,

    "ProgID": "Excel.Sheet.8",

    "SourceFullName": "Sample_Book2.xls",

    "Name": "OleObject 1",

    "MsoDrawingType": "OleObject",

    "AutoShapeType": "PictureFrame",

    "Placement": "Move",

    "UpperLeftRow": 15,

    "Top": 10,

    "UpperLeftColumn": 5,

    "Left": 10,

    "LowerRightRow": 39,

    "Bottom": 2,

    "LowerRightColumn": 11,

    "Right": 26,

    "Width": 400,

    "Height": 400,

    "X": 330,

    "Y": 275,

    "RotationAngle": 0.0,

    "AlternativeText": "",

    "TextHorizontalAlignment": "Left",

    "TextHorizontalOverflow": "Overflow",

    "TextOrientationType": "NoRotation",

    "TextVerticalOverflow": "Overflow",

    "IsGroup": false,

    "IsHidden": false,

    "IsLockAspectRatio": false,

    "IsLocked": false,

    "IsPrintable": false,

    "IsTextWrapped": false,

    "IsWordArt": false,

    "ZOrderPosition": 0,

    "link": {

      "Href": "http://api.aspose.cloud/v3.0/cells/Sample_Test_Book.xls/worksheets/Sheet1/oleobjects/0",

      "Rel": "self"

    }

  },

  "Code": "200",

  "Status": "OK"

}

```

{{< /tab >}}

{{< /tabs >}}
## **SDK Source**
The Aspose.Cells Cloud SDKs can be downloaded from the following page: [Available SDKs](/cells/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="10" tabID="4" tabName1="C#" tabName2="Java" tabName3="PHP" tabName4="Ruby" tabName5="Node.js" tabName6="Python" tabName7="Android" tabName8="Swift" tabName9="Perl" tabName10="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "1e994f29ef29e752b6d02a2c5b63ea9b" "Examples-DotNET-CSharp-OleObjects-AddOleObjectsWorksheet-1.cs" >}}

{{< /tab >}}

{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "af3fea45644d431483f6df52cf3bfe26" "Examples-Java-oleobjects-AddOleObjectsWorksheet-add-ole-objects-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "5c1a68c4cea73845b221ff0d3b9ec9df" "Examples-PHP-OLEObjects-PutWorksheetOleObject-.php" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "3c5c9f9fff9898bb8251aa7ee9191641" "Examples-Ruby-OLEObject-add_ole_object-.rb" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "04e9dd952c704f334a4eceb3925d479e" "Examples-Node.js-SDK-Oleobjects-AddOleObjectsWorksheet-1.js" >}}

{{< /tab >}}

{{< tab tabNum="6" >}}

{{< gist "aspose-cloud" "5161752550311c9baf73ffa0a811ea0b" "AddOLEObjectsToExcelWorksheet.py" >}}

{{< /tab >}}

{{< tab tabNum="7" >}}

{{< gist "aspose-cloud" "9d725d4678edaac53f95c5208e17783c" "Examples-Android-oleobjects-AddOleObjectsWorksheet-add-ole-objects-worksheet.java" >}}

{{< /tab >}}

{{< tab tabNum="8" >}}

{{< /tab >}}

{{< tab tabNum="9" >}}

{{< gist "aspose-cloud" "7effbad588b0c24b5f8ed2d7c7759b72" "Examples-Perl-Oleobjects-AddOleObjectsWorksheet-1.pl" >}}

{{< /tab >}}

{{< tab tabNum="10" >}}

{{< gist "aspose-cloud" "9c929ad7c5fe5078d6f5532dff537058" >}}

{{< /tab >}}

{{< /tabs >}}
