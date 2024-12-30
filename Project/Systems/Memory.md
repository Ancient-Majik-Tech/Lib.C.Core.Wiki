[Page]:https://github.com/Ancient-Majik-Tech/Lib.C.Core.Wiki/blob/main/Project/Systems/Memory.md

[Page Home]:https://github.com/Ancient-Majik-Tech/Lib.C.Core.Wiki/blob/main/README.md
[Page Project Home]:https://github.com/Ancient-Majik-Tech/Lib.C.Core.Wiki/blob/main/Project/Project_Home.md
[Page Learn Home]:https://github.com/Ancient-Majik-Tech/Lib.C.Core.Wiki/blob/main/Learn/Learn_Home.md
[Page Changes Home]:https://github.com/Ancient-Majik-Tech/Lib.C.Core.Wiki/blob/main/Changes/Changes_Home.md

[Sec Welcome]:link#welcome
[Sec Details]:link#system-details
[Sec Features]:link#features

[SysTag RawC]:link
[SysTag OOPClass]:link

[Feat Create]:link
[Feat Release]:link
[Feat Clean]:link

# Realms Tutorial Collections: "Realms Core" - Systems - Device Memory System

## Site Index

- [Home][Page Home]
	- [Project][Page Proj Home]
		- Library Host System (You are here)
	- [Learning][Page Learn Home]
	- [Changes][Page Changes Home]

## Page Index

- Page
	- [Welcome][Sec Welcome]
	- [System Details][Sec Details]
	- [Features][Sec Features]

### Welcome

Welcome to the Device Memory System's documentation page. This page is dedicated to helping you understand the system and its features. However please note that for understanding how to use the project you should check out [Learning][Page Learn Home] for all the dedicated learning for the given project.

### System Details

- Details
	- Name: Binary Memory System
	- SystemID: Core.Memory
	- IDPiece: Memory
	- Version: V 0.5.0
	- Implimented Version: V D 0.0.1.0
	- Last Changed: V D 0.0.26.0
	- Last Changed Reason: Update to Match Primitive Side
	- Tags
		- [Prim C][SysTag PrimC]
		- Subsystem Builder:{ Parent:LibHost }
		

This system is used to create, handle and work with the binary memory that objects are on the device being used to provide a framework for working with Raw C memory objects.

### Features

- Features
	- [Object Creation][Feat Create]
	- [Object Recycle][Feat Release]
	- [Memory Cleaning][Feat Clean]
	- [Memory Data Copying][Feat Copy]
	- [Delayed Project-Systems helper Building][Feat DelayHelper]

#### Object Creation Feature

This feature helps create binary memory blocks of objects.

- Details
	- Status: Active
	- Version: V 3.0
	- FeatureID: Memory.CreateFeat
	- Impliment System Version: V 0.1.0
	- Last Change: V 0.5.0
	
#### Object Recycle Feature

This feature helps recycle of objects in memory.

- Details
	- Status: Active
	- Version: V 3.0
	- FeatureID: Memory.RecycleFeat
	- Impliment System Version: V 0.1.0
	- Last Change: V 0.5.0

#### Memory Cleaning Feature

This feature is used to clean memory when releasing so that data is protected slightly better.

- Details
	- Status: Active
	- Version: V 2.0
	- FeatureID: Memory.CleanFeat
	- Impliment System Version: V 0.1.0
	- Last Change: V 0.5.0

#### Memory Data Coping Feature

This feature is used to copy memory chunks to allow for quicker processing and handling.


- Details
	- Status: Active
	- Version: V 2.0
	- FeatureID: Memory.CopyFeat
	- Impliment System Version: V 0.3.0
	- Last Change: V 0.5.0

#### Delayed Project Systems Helper Building Feature

This feature is used to allow the system to use the project systems helper but to delay it till the given classes are available and useable.


- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: Memory.DelayHelperFeat
	- Impliment System Version: V 0.5.0
	- Last Change: V 0.5.0

#### Null Objects Handling Feature

This feature register a way of handling null in all three levels of OOP provided by Realms Core.


- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: Memory.NullFeat
	- Impliment System Version: V 0.5.0
	- Last Change: V 0.5.0

#### Void Handling Feature

This feature provides a way for some parts of OOP to handle functions with no returns by building a type to be used.


- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: Memory.VoidFeat
	- Impliment System Version: V 0.5.0
	- Last Change: V 0.5.0

#### Memory Pointer Handling Feature

This feature is used to allow the use of memory pointers in all three levels of OOP but also used to power some features in the Realms OOP level.


- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: Memory.MemoryPointersFeat
	- Impliment System Version: V 0.5.0
	- Last Change: V 0.5.0

#### Memory Address Size Number Feature

This feature is used to provide a value the depends on the computer/device is capable. IE 64 bit PC uses a PrimUInt64 or PrimUInt32 if on 32 bit machines, though support starts with only 64 bit. 


- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: Memory.MemoryAddressSizeFeat
	- Impliment System Version: V 0.5.0
	- Last Change: V 0.5.0

#### Binary Numbers Basics Feature

This feature is used to provide the basis for binary handling with both signed and unsighed bytes, which is why there is no Int8 class.


- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: Memory.BinaryFeat
	- Impliment System Version: V 0.5.0
	- Last Change: V 0.5.0