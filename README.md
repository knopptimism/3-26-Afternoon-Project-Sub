# 3-26-Afternoon-Project-Sub
Nick and Jeremiah



1.) Choose a pattern and find an instance where it’s been used. 
  
  N: I choose Delegation Pattern, we used it to communicate between the custom cell and our table view controller in the Reading List Project.

	J: I choose singleton and I point to the Astronomy project, which passes one MarsRoverClient() through the app. In that case the object isn’t marked private, but it is one instance being passed through the whole thing. 

2.) Look through the documentation and find one UIKit class that uses singleton: 
  N: UserDefault.standard, URLSession.shared, NotificationCenter.default,FileManager.default,..
  J: UIWindow - Passes one container through the app.

3.) Think about a time we used the facade pattern. 
  Both: The firebase chat app had multiple controllers and a master controller that incorporated it all, I think. 

4.) Write code to post a notification when a button is tapped indicating a bell has rung. In another class, sign up to be notified when this notification is posted, and make sure it works.
  See 3_26Notification.zip

5.) See ios-astronomy-unit-testing.zip




