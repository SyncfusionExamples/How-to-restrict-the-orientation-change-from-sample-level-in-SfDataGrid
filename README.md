# How to restrict the orientation change from sample level for Android and iOS platforms in SfDataGrid ?
In this article, we will show you how to restrict the orientation change from sample level for Android and iOS in [.Net Maui DataGrid](https://www.syncfusion.com/maui-controls/maui-datagrid).

## Android Platform
The code below demonstrates how to restrict orientation changes at the sample level on the Android platform. The following code needs to be added to the MainActivity.cs file located under Platforms -> Android -> MainActivity.cs.
```
public class MainActivity : MauiAppCompatActivity
{
    protected override void OnCreate(Bundle? savedInstanceState)
    {
        base.OnCreate(savedInstanceState);

        RequestedOrientation = ScreenOrientation.Portrait;
    }
}
``` 

 ![AndroidDemo.gif](https://support.syncfusion.com/kb/agent/attachment/inline?token=eyJhbGciOiJodHRwOi8vd3d3LnczLm9yZy8yMDAxLzA0L3htbGRzaWctbW9yZSNobWFjLXNoYTI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjMzOTQ3Iiwib3JnaWQiOiIzIiwiaXNzIjoic3VwcG9ydC5zeW5jZnVzaW9uLmNvbSJ9.JZNX-x3hYxc7v4vjC8-NfqTwlit0KE4X69Y2_jVmhjw)

## iOS Platform.
For iOS, you can define the allowed orientations in the Info.plist. You can find the Info.Plist file loacted under platform -> iOS -> Info.Plist. 

 ![DeviceOrientaionIOS.png](https://support.syncfusion.com/kb/agent/attachment/inline?token=eyJhbGciOiJodHRwOi8vd3d3LnczLm9yZy8yMDAxLzA0L3htbGRzaWctbW9yZSNobWFjLXNoYTI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjMzOTQ4Iiwib3JnaWQiOiIzIiwiaXNzIjoic3VwcG9ydC5zeW5jZnVzaW9uLmNvbSJ9.PTYnf1nIBGE_3rxHUxHYmfbF2ZhfW1o3kxRHzjH64lQ)


[View sample in GitHub](https://github.com/SyncfusionExamples/How-to-restrict-the-orientation-change-from-sample-level-in-SfDataGrid)

Take a moment to explore this [documentation](https://help.syncfusion.com/maui/datagrid/overview), where you can find more information about Syncfusion .NET MAUI DataGrid (SfDataGrid) with code examples. Please refer to this [link](https://www.syncfusion.com/maui-controls/maui-datagrid) to learn about the essential features of Syncfusion .NET MAUI DataGrid (SfDataGrid).
 
##### Conclusion
 
I hope you enjoyed learning about how to restrict the orientation change from sample level for Android and iOS platforms in .NET MAUI DataGrid (SfDataGrid).
 
You can refer to our [.NET MAUI DataGrid’s feature tour](https://www.syncfusion.com/maui-controls/maui-datagrid) page to learn about its other groundbreaking feature representations. You can also explore our [.NET MAUI DataGrid Documentation](https://help.syncfusion.com/maui/datagrid/getting-started) to understand how to present and manipulate data. 
For current customers, you can check out our .NET MAUI components on the [License and Downloads](https://www.syncfusion.com/sales/teamlicense) page. If you are new to Syncfusion, you can try our 30-day [free trial](https://www.syncfusion.com/downloads/maui) to explore our .NET MAUI DataGrid and other .NET MAUI components.
 
If you have any queries or require clarifications, please let us know in the comments below. You can also contact us through our [support forums](https://www.syncfusion.com/forums), [Direct-Trac](https://support.syncfusion.com/create) or [feedback portal](https://www.syncfusion.com/feedback/maui?control=sfdatagrid), or the feedback portal. We are always happy to assist you!