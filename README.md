# Menu
Android provides a standard XML format to define menu items.Then you can inflate the menu resource in your activity or fragment.
Menus are three types Options menu,Context menu,Popup menu.
Option menu are the primary menus of android.They can be used for settings,search,etc...To perform event handling on mennu items,you need 
to override onOptionsItemSelected() method of activity class.
Context menu is a floating list of menu items that appears when a user touches and holds a particular item displayed in the view,which has a
menu associated with it.
Popup menu displays the menu below the anchor text if the space is available otherwise above the anchor text.It disappears if you click 
outside the popup menu.
In this example,you will leran about options menu.The menu items should be taken in the xml file and inflate the menus in the activity.
We have taken 3 items settings,contacts,logout and icons for 3 items.when you click the menu items it overrides the onOptionItemSelected() 
method and displays the toast message which contains title of the selected item.Menus are displayed on the Appbar.
