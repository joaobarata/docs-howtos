# How to show records side by side in a List Record widget

## Question

 

Is it possible to customize the layout to show records side-by-side, as follows?

| Record1 | Record3 | Record5 |
|---------|---------|---------|
| Record2 | Record4 |         |

In the standard table grid layout each record is displayed below each other as follows:

| Record1 |
|---------|
| Record2 |
| Record3 |
| Record4 |
| …       |

## Answer

Use the **List Records widget **to better manipulate the way the information is displayed on your Web Screen.

![image alt text](images/How-to-show-records-side-by-side-in-a-List-Record-widget_0.png)

After you select the **List Records widget **to use in your Web Screen you just need to go to the properties of the widget and set the **Line Separator** property to **None **so the records can be displayed side-by-side.

![image alt text](images/How-to-show-records-side-by-side-in-a-List-Record-widget_1.png)

After you performed these configurations your layout may look similar to the following screenshot. You can see more useful UI patterns by looking into the [SILKUI](http://labs.outsystems.net/silkui/) component available on Forge.

![image alt text](images/How-to-show-records-side-by-side-in-a-List-Record-widget_2.png)

The following example OML shows how to use the List Records widget to provide the look and feel above.

[https://success.outsystems.com/@api/deki/files/1416/ListRecordExample.oml](https://success.outsystems.com/@api/deki/files/1416/ListRecordExample.oml?revision=1)

