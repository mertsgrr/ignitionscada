# Paneling datas with Ignition SCADA
- Used in the Project <br>
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)<br>
<img src="https://drive.google.com/uc?export=view&id=1vp65UzMVc-4dUk7Oy8eE_np7ZGtfFa_d"> Ignition SCADA

# Download Required Files

[Click to download](https://drive.google.com/file/d/1a8iJdmicHrn-rpxTV-oO7NkLOKPzUOgl/view?usp=share_link)

# Installation

<h3>Ignition SCADA</h3>
<ul>
  <li>Login to Ignition SCADA localhost administration panel</li>
  <li>Click on the "Config" tab from the left side menu</li>
  <li>On the screen that comes up, click the "Connections" tab under the "Databases" section</li>
  <li>Add a new database by clicking on the link "Create new Database Connection..."</li>
  <li>Select MySQL (The official MySQL JDBC Driver, Connector/J must be installed on the computer)</li>
  <li>Enter the information with the database name <strong>ScadaControl</strong> and click the "Create New Database Connection" button to create the database</li>
  <li>After the database is created, import the contents of the Database you downloaded from above to the database you just created</li>
</ul>

# Usage
<ol>
  <li>Make sure <strong>Ignition Localhost</strong> is running</li>
  <li>Open <strong>Designer Launcher</strong>. </li>
  <li>Select the Designer running on Localhost and then click "Open Designer" button from bottom right</li>
  <li>Import the project you downloaded from here by clicking the "Import Project" button in the upper right part of the window that comes up.</li>
  <li>Run the project via Vision by following the "Tools/Launch Project/Launch" path from the top menu</li>
</ol>
