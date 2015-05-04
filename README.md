# magnet-winforms
A .NET sticky forms that actually works

Features
~~~~~~~~
* Edge-to-edge and edge-to-corner magnets
* Joint move and resize of child from when main form moves or resizes
* Simple and clean implementation  

Usage
~~~~~
Simply include MagnetWinForms.cs in your project and create an instance in the form constructor, ie:

    public Form()
    {
    	InitializeComponent();
	
		m_MagnetWinForms = new MagnetWinForms(this);
	}

NOTE: While all forms need to create a MagnetWinForms instance, the Main form should be the first one to do it.

