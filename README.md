# ![SimpleDocumentCreationExample](https://github.com/BenjaminRLabVIEWExtensions/BenjaminRLabVIEWExtensions.github.io/blob/0378ea26009b234c49e65a4d3b8372088c1e4d6d/LabVIEW_Extensions_Small.png?raw=true) [BenjaminR's LabVIEW Extensions](https://benji667.github.io/LabVIEW_NPOI/about)

Several LabVIEW IDE features were designed using plugin architecture that let developers to extend their LabVIEW's editor environment with G code.

Here the list of the customizable LabVIEW editor features:

- [Quick Drop Keyboard Shortcuts](https://forums.ni.com/t5/Quick-Drop-Enthusiasts/gh-p/grp-1251): define custom shortcuts for commonly-dropped palette objects.
- [LabVIEW Shortcut Menu Plug-ins](https://forums.ni.com/t5/LabVIEW-Shortcut-Menu-Plug-Ins/tkb-p/3013): add right-click menu options to the LabVIEW editor.
- [LabVIEW Pull-down Menu plug-ins](https://forums.ni.com/t5/Developer-Center-Resources/Integrating-into-the-LabVIEW-Menus/ta-p/3518025): add environment-based or document-based editor actions to the pull-down menus (Tools, Help, or File).
- [VI Analyzer Rules](https://forums.ni.com/t5/VI-Analyzer-Enthusiasts/ct-p/7021): create custom code inspection tests.
- [Bookmark Manager](https://forums.ni.com/t5/Developer-Center-Resources/Creating-a-Custom-Bookmark-Manager-for-LabVIEW/ta-p/3513079): create custom bookmark manager to better suit application needs.
- [_Edit>Create_ SubVI](http://labviewartisan.blogspot.com/2011/08/how-to-customize-edit-create-subvi-in.html): improve the Edit > Create SubVI gesture.
- [Custom Templates and Sample Projects to Develop LabVIEW Projects](https://knowledge.ni.com/KnowledgeArticleDetails?id=kA03q000000x1k8CAA&l=en-CA): use custom projects,created as custom templates, in the Create Project dialog box.
- [Channel templates](https://forums.ni.com/t5/LabVIEW-Channel-Wires/Getting-Started-With-Channel-Wires/m-p/3505658): express custom communication between two pieces of code within the same application instance.
- [Custom Probes](https://zone.ni.com/reference/en-XX/help/371361P-01/lvhowto/creating_custom_probes/): have more control over how LabVIEW probes the data.
- [Development Environment Callback VIs](https://labviewwiki.org/wiki/Development_Environment_Event_Callback_VIs): Define new behavior for various editor actions.
- [LabVIEW Project Providers](https://forums.ni.com/t5/LabVIEW-Project-Providers/gh-p/bymqyodmkc): control and modify the LabVIEW Project window.

Using the providing mechanisms, to augment the editor, I have been able to implement some new LabVIEW features. 

- [**Insert LVClass Property Node**](https://github.com/BenjaminRLabVIEWExtensions/Insert-LVClass-Property-Node): shortcut menu plug-In to insert LVClass Property Node (Read or Write) or display dialog to choose which property to create with which access (Read, Write, Read and Write).
- [**LabVIEW Shortcut Provider**](https://github.com/BenjaminRLabVIEWExtensions/lvshortcut_provider): ability to create new Shorcut item from the popup menu that appears when My Computer is right-clicked.
