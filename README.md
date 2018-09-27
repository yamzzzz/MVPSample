# MVPSample
Its about how to use MVP pattern for Android Application. 

<b>Main Objective:</b><br/>

Every class should have one dedicated Presenter for it. (1 to 1 relationship).
All the network calls and Preference calls should be happened in Model class.

<b>My way of using MVP architechture:</b>

* <b>Presenter</b> should have all Bussiness logics, we are using.
* <b>Connector</b> Interface acts like a 'Map' for Presenter, where we can know what functions are all happening. 
* All the Network calls, Preference calls will be happened in <b>ModelImpl</b> class.
* <b>Model</b> Interface will act like a 'Map' for ModelImpl class.

