Name : JTrouve
Category : Productivity
Platform : Android, IOS, Windows Phone
Framework : Xamarin.Forms
design pattern : MVVM , Prism
local database : SqLite
Backend for online database : Applicasa, kumulos, and other

when offline the aplication will be using sqlite db

HARDWARE REQUIEREMENT
=====================
- use of camera
- use of microphone
- use of gallery
- connectivity (Wifi - Mobile data)
- GPS
- Location

API REQUIREMENT
===============
- Android : 4.2 or later
- IOS : IOS 7 or later
- Windows Phone : 8.1

 
TYPE OF ACCOUNTS
================
- Bronze(normal account with limited features on Ads)
- Gold (have a bit of gain access on Ads)
- Platinum( this is for commercial)

there is a possibility to upgrade an account to any type

BASIC FUNCTIONALITIES
=====================
- Liste places : 
	- hotels: name, address, city
 	- restaurant : name, address, city
	- Amusement : name, addresse, city 
	- Parks : name, addresse, city, 
- liste products
- publish Ads


DATABASE ENTITIES
=================

=================   ================ 		=================	=================	=========================
= PLACE TABLE   =   = PLACE TYPE   =		= PRODUCT 	=	= CATEGORY	=	= USER	   	        =	
=================   ================		=================	=================	=========================
= + Id		=   = + id	   =		= + Id		=	= + Id		=	= + iD			=
= + Name	=   = + Name	   =		= + Name	=	= + Name	=	= + Username		=		
= + Description =   ================		= + Price	=	=================	= + Firstname		=
= + Adress	=   ================		= + Currency	=				= + Lastname		=
= + TypeId	=   = LOCATION TABL=		= + Description =	=================	= + Email		=
= + LocationId	=   ================		= + CategoryId  =	= ACCOUNT TYPE  =	= + Password		=
= + AuthorId	=   = + id	   =		= + PlaceId	=	=================	= + Phonenumber		=
=		=   = 		   =		= + Photo	=	= + Id		=	= + CurrentLocationId	=
=================   = + Name	   =		= + AuthorId	=	= + Name	=	= + ProfilePhoto	=
		    ================		=================	=================	= + AccountTypeId		=
												=========================

 

