# Using Conan for C++ Pkg management with JFrog Repository

Contents conanfile.py
-----------------------------

![conanfile ](imgs/conanfile.PNG)

Contents CMakeLists.txt
-----------------------------

![CMakeLists ](imgs/makerepo.PNG)

Contents conanfile.txt
-----------------------------

![conanfile ](imgs/conanf.PNG)

JFROG UI
-----------------------------

![JFROG ](imgs/jfrog.PNG)

After creating repo in jfrog, we can create a repo 
![creating ](imgs/jfrog-repo.PNG)

Conan Create 
![creating ](imgs/conan-create.PNG)

Conan Search for the created repo 
![Search ](imgs/conan-search.PNG)

Conan add the created artifact details to the project
![remote ](imgs/conan-remote-add.PNG)

Authorize Jfrog

![JFROG ](imgs/jfrog-login.PNG)


Conan upload the artifact to Jfrog
![artifact ](imgs/upload-jfrog.PNG)

Remove the local artifact and when trying conan install .. inside build folder it will search for jfrog repo and download from there

![remove ](imgs/remove.PNG)

![download ](imgs/remote-download.PNG)

