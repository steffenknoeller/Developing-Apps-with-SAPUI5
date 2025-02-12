[![solution](https://flat.badgen.net/badge/solution/available/green?icon=github)](../../../../tree/gh-pages/ex1)
[![demo](https://flat.badgen.net/badge/demo/deployed/blue?icon=chrome)](https://dirkelko.github.io/Developing-Apps-with-SAPUI5/ex1/sensormanager/webapp/)

# Exercise 1 - Project Setup Using SAP Business Application Studio

In this exercise you'll create a new UI5 application based on a template provided by SAP Business Application Studio.

## Scenario

Your customer "Keep Cool, Inc." is an operator of several icehouses across the country. Recently, they have been upgraded with new sensors with Internet connection, so that their measuring values are available as a service. To make use of this data and improve their internal workflows, the company asked us to provide an application leveraging this sensor data, visualize it, and provide an overview of the current state of each sensor, so that they can react quickly on any issues.

## Exercise 1.1 - Create a New UI5 Application

After completing these steps you'll have created your first UI5 application.

1. Click on *Start from template* on the *Welcome* page.
    * [Optional] If you have closed the *Welcome* page accidentally, click in the header toolbar on *View*, and select *Find Command...*  Enter *Welcome*.</ul>
<br><br>![](images/01_01_0010b.png)<br><br>

2. Click on *SAP Fiori application* on as template and click *Start*.
<br><br>![](images/01_01_0015b.png)<br><br>

3. Enter the following settings in the *Floorplan Selection* step: 
    1. Select *SAPUI5 freestyle* from the dropdown box.
    2. Select *SAPUI5 Application* as application template and click *Next*.</ol>
<br>![](images/01_01_0020b.png)<br><br><ol>

4. Select *None* as Data Source, since we start without an external data source. Click *Next*
<br><br>![](images/01_01_0025b.png)<br><br>
   
5. Enter *App* as view name in the next step. (we don't really select an entity set, since we start without a data service).
<br><br>![](images/01_01_0030b.png)<br><br>

6. Enter the following settings in the *Project Attributes* step:
    1. Enter *sensormanager* as *Module name*. 
    2. Choose *Sensor Manager* as *Application title*.
    3. Enter *keepcool* as your namespace.
    4. You can leave the description
    5. Leave the Project folder path as */home/user/projects* .
    6. Select *Add deployment configuration*
    7. Click *Next*. </ol>
<br>![](images/01_01_0051b.png)<br><br><ol>

7. In the next step, select *Cloud Foundry* as target, leave the Destination name to "None" and make sure that the *Yes* is checked for adding the application to the application router and click *Finish*.  </ul>
<br><br>![](images/01_01_0065b.png)<br><br>

8. The project is generated, and a notification window appears in the lower right corner which will inform you when the project has been generated. Wait for the message that the project has been generated!

9.  Click the blue *Open Folder* button at the top left of the screen. Alternatively, click *File* in the header toolbar, select *Open Workspace* and pick the generated project.  </ul>
<br><br>![](images/01_01_0060b.png)<br><br>

10. Open the *projects* folder and select the *sensormanager* folder in the dialog and click *open*
<br><br>![](images/01_01_0071b.png)<br><br>

## Exercise 1.2 - Try out the generated Application

It's time for a first preview of your newly created application!

1. The Business Application Studio has altready created three so called Run Configurations.
    1. Click the ![](images/01_02_0005b.png) icon in the left icon bar.
    2. Click on the green run icon of the first runconfiguration named *Start sensormanager*

<br><br>![](images/01_02_0010b.png)<br><br>

2. The application is initialized. After a few seconds, the application is started in a new tab of your browser. (It might be neccessary to switch off the pop up blocker)
<br><br>![](images/01_02_0040b.png)<br><br>


## Summary

Hooray! You've successfully accomplished [Exercise 1 - Project Setup using SAP Business Application Studio](#exercise-1---project-setup-using-sap-business-applicationsstudio)!

Continue to [Exercise 2 - Basic UI5 Configuration and  View Creation](../ex2/README.md).
