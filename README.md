# DRY
Tutorial by : IAmTimCorey

Link: https://www.youtube.com/watch?v=dhnsegiPXoo&list=PLLWMQd6PeGY3ob0Ga6vn1czFZfW6e-FLr&index=1

## Things I didn't do
In the tutorial he creates another application and shows how to access the EmployeeProcesser class by referencing the dll. 

Near the end of the video he recreates the EmployeeProcessor class as a .NetStandard class library. Allowing it to be used in other platforms like say Unity for example. I have no need to do this personally so I didn't bother.

## General Advice 
This advice was given at the end of the tutorial. 

Tim Corey recommends where possible to add your code as a .Net Standard Class Library. This somewhat takes DRY to the extreme as it allows you to reuse your code on other c# platforms like xamarin. 

## My Own Thoughs
I'm not sure if the .Net Standard Class Library advice will become outdated as more platforms are supported by .Net 6/7. It seems like Xamarin is on it's way out as .NET MAUI has been created. 

As a note though this tutorial was release on 22nd October 2018 so .Net wasn't in the same place it is today.

I was surprised to see unit testing in this DRY tutorial but once it was explained it made total sense. If you are constantly rerunning the app and testing things manually you are repeating yourself ad nausem.