

1. add in build.gradle : 
   
   compile 'com.github;SandroMachado:openalpr-android:1.1.2'
   compile 'com.squareup.picasso:picasso:2.5.2'
   compile 'com.google.code.gson:gson:2.6.2'
   
2.create a folder assets and add a folder runtime_data and copy openalpr_conf
  LINK : https://github.com/SandroMachado/openalpr-android/blob/master/openalpr.conf
3. change in file openalpr.conf the package in runtime_dir by project package
4. for plate in eu in recognizationWithCountryRegionNConfig method first param will be : "eu"

link project : 
https://github.com/SandroMachado/openalpr-android