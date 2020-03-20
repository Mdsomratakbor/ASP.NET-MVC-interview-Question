### What is MVC?
`MVC Stands for MODEL-VIEW-CONTROLLER is a Software Architectural Pattern. Which has been implemented across multiple development platforms and languages. It is divided into three components Model, View and Controller.`

### Explain Model, View and Controller in MVC?
`View used to display the User interface and basically a HTML template. Model contains real world objects, data and business login, Controller handles user interaction and loads the appropriate models and views.`

### Which assembly defines MVC framework?
`The MVC framework is defined in System.Web.Mvc`

### What is the latest version of MVC in .Net development?
`MVC5 is the latest version of MVC architectural pattern as of 2017 which runs on .Net 4.7 framework.`

### What are the different types of Session management in MVC?
`The different ways of managing Session in MVC are TempData, ViewData, and ViewBag.`

### Explain the difference between TempData, ViewData and ViewBag?
`TempData is used to move data form one controller to another or from one action to another also it internally uses ViewData. ViewData is used to transfer data from Controller to View. ViewBag is used to transfer data without casting as it uses dynamic keyword and internally implements ViewData.`

### Explain Partial Views in MVC?
`Partial Views is a reusable chunk html code that can be inserted into existing View. They are used to display dynamic content in View with Static layout page. it does not contain a layout page and hence does't consist of mark up.`

### Explain Validation in MVC?
`Three things are needed to handle vlidation in MVC:`
- `Data annotations which are nothing but attributes which can used on model Properties.`
- `ValidateMessagesFor which is an html helper class must be used to display the error.`
- `ModelState.IsValid must be used in contorller to take action accroding to user Response.`

### What is Razor View in MVC?
`Razor is a lightweight View engine in MVC3.`
`Razor View can be created with two extensions: .cshtml for c# .vbhtml for Visual Basic.`

### What are Filtes in MVC?
`Filters are used to add logic code that will execute before or after a controller executes an Action method.`</br>
`Types of Filters :`
- `Action Filters`
- `Authorization Filters`
- `Result Filters`
- `Exception Filters`

### Explain Html Helpers in MVC?
`Html Helpers in MVC work in almost the same way as Server Control as they are used to generate Html elements which might be needed for links, Images and for from Elements, These Html Helpers are light weight as they do not contain View State and event model attached to them.`

### What are the Advantages of MVC?
- `Applications developed are lightweight also it suited to develop applications that are complex.`
- `Separation of Concerns allows for compartmentalization of Presentation (UI) Business which allows high productivity and development time whith large teams.`
- `MVC application have extensible URL Support making it easy to use option for the End user.`















