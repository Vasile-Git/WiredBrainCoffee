Course Summary:
- Build a WPF application:
  - Create a user interface in XAML;
  - Use data binding;
  - Apply the MVVM pattern;
  - Validate user input;
  
- Work with different WPF features:
  - Define resources;
  - Create data templates;
  - Use styles;
  - Edit control templates;

- Debug your WPF application  



module 2

- WPF is a UI framework that is part of .NET:
	- Build desktop apps for Windows;
- Define user interface with XAML
- The main windows consists of multiple files:
	- MainWindow.xaml;
	- MainWindow.xaml.cs (code-behind);
	- More file are generated in obj/Debug;


module 3 - Instantiating objects in XAML

- Elements are mapped to classes:
	- Except property element;
 
- Attributes are mapped to properties events
- Set properties in XAML:
	- Attribute syntax;
	- Property element syntax;
	- Content syntax;
	- Collection syntax;


module 4 - Building a User Interface

- Use the WPF layout panels:
	- Grid, StackPanel, Canvas;
- Position elements with layout properties
- Set attached properties in:
	- XAML
	- C#


module 5 - Organize code with UserControls

-  Organize code with UserControls:
	- Create and use a UserControl for the header;
	- Refactor code in the MainWindow to extract a UserControl for customers;
- Understand the XAML namespaces of WPF


module 6 - Applying Data Binding and MVVM

- Create data bindings in XAML:
	- Bind to another element
	- Know how the data context works

- Apply the MVVM pattern

- Work with data bindings:
  - Notify about property changes
  - Use the XAML Binding Failures window
  - Convert values with an IValueConverter


module 7 - Execute Code with Commands

 - Understand the ICommand interface;
 - Create a DelegateCommand class;
 - Use the DelegateCommand class
   - Define command properties
   - Bind the view to command properties
   - Raise CanExecuteChanged event


module 8 - Creating Reusable Resources

 - Define resources in XAML:
   - Elements have a Resources property
 - Reference resources with the StaticResource markup extension:
   - Resources are searched upwards in the element tree
   - Create application-wide resources in the App.xaml file
 - Move resources to a separate file
 - Merge multiple resources dictionaries


module 9 - Working with Data Templates

- WPF's flexible content model
	- ContentControl and ItemsControl;
	- UIElements are rendered;
	- For other objects ToString result is shown;
- Create and use data templates
	- Explicit data template with x:Key;
	- Implicit data template with DataType;
- Use data templates to load detail views


module 10 - Setting up Dependency Injection

- Register and use another type with dependency injection;

Summary:
- Instantiate the MainWindows in c#;
- Set up dependency injection
	- Microsoft.Extensions.DependencyInjection (NuGet package)


module 11 - Styling Your Application

- Work with styles in WPF
	- Define property values with a style;
	- Inherit a style from another style;
	- Understand explicit and implicit styles;

- Use Property Triggers in a Style;


module 12 - Mastering Control Templates

 - User controls and custom controls:
	- User controls are the components that you build in your application;
	- All WPF controls are custom controls;

- Change the look of a custom control:
	- Set the Template property;
	- Create a copy of the control template;
	- Adjust the control template;


module 13 - Validating User Input

 - Validate the firstname of a customer:
	- Create a ValidationViewModelBase Class;
	- Implement INotifyDataErrorInfo;

 - Show the Error in the User Interface:
	- In a tooltip;
	- Below the TextBox;

 - Binding sets attached properties:
	- Validation.HasError


module 14 - Debugging Your WPF Application
	
- Use the XAML debugging tools
	- Explore the Live Visual Tree
	- Inspect Properties at Runtime
- Analyze and explore WPF applications


