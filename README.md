# aem-snippets-vscode README

This is a VSCode extension with AEM application HTL and JSP snippets for HTML, Touch and Classic UI dialogs, osgi configs and sling servlets (for now)

## Features

For now simple htl snippets, some snippets for touch ui dialogs, sling servlets, osgi configurations and json object creation

* Type 'htl.' or 'jsp.' to see available snippets inside a .html file
* Type 'aem.' or 'osgi.' to see available snippets inside a .xml or .js file
* Type 'sling.' or 'osgi.' to see available snippets inside a .java file

There are two ways of triggering the snippet, one is very verbose, sorry for that, but it was created for me or someone like me :( that might forget some stuff, and some are shorter for those with big memories (obviously not me)

### HTML - snippets (*.html files)

| Description        | Short Alias           | Verbose in case you forget |
| ------------- |:-------------|:-----|
| HTL Comments      | heco | htl.elem.comments |
| Include HTL script HTML Element      | heis | htl.elem.inc.script |
| Include HTL script HTML Attribute      | hais | htl.attr.inc.script |
| Include Java Model HTML Element      | heim | htl.elem.inc.model |
| Include Java Model HTML Attribute      | haim | htl.attr.inc.model |
| Include Component HTML Element      | heic | htl.elem.inc.component |
| Include Component HTML Attribute      | haic | htl.attr.inc.component |
| HTL List Iterator      | hel | htl.elem.list |
| Define HTL template      | hetd | htl.elem.template.define |
| Call HTL template      | hetc | htl.elem.template.call |
| HTL variable      | hev | htl.elem.variable |
| HTL Test Attribute      | het | htl.attr.test |
| Ternary WCM Edit      | hetem | htl.val.test.editMode |
| Define - Clientlibs - HTL      | hecld | htl.elem.clientlib.define |
| Define Attribute - Clientlibs - HTL      | hacld | htl.attr.clientlib.define |
| Include Js and CSS - Clientlibs - HTL      | hecia | htl.elem.clientlib.include.all |
| Include Js - Clientlibs - HTL      | hecij | htl.elem.clientlib.include.js |
| Include CSS - Clientlibs - HTL      | hecic | htl.elem.clientlib.include.css |

### JSON - Jackson - snippets (*.java files)

| Description        | Short Alias           | Verbose in case you forget |
| ------------- |:-------------|:-----|
| Jackson - JSON - Imports      | jji | json.jackson.imports |
| Create Jackson Object Mapper      | jjmap | json.jackson.mapper |
| Jackson Json Object      | jjno | json.jackson.new.object |
| Jackson Json Array      | jjna | json.jackson.new.array |
| Jackson Json Mapper      | jjtstr | json.jackson.toString |

### JSON - Regular - snippets (*.java files)

| Description        | Short Alias           | Verbose in case you forget |
| ------------- |:-------------|:-----|
| Commons - JSON - Imports      | jci | json.commons.imports |
| Json Object      | jcno | json.commons.new.object |
| Json Array      | jcna | json.commons.new.array |
| Json Object      | jctstr | json.commons.toString |

### OSGi - snippets (*.java files)

| Description        | Short Alias           | Verbose in case you forget |
| ------------- |:-------------|:-----|
| Get OSGi Bundle Version Imports      | obvi | osgi.bundle.version.imports |
| Get OSGi Bundle Version      | obvg | osgi.bundle.version.get |
| OSGi Configuration R6 Definition Imports      | oc6di | osgi.config.r6.definition.imports |
| OSGi Configuration R6 Definition Annotations      | oc6da | osgi.config.r6.definition.annotations |
| OSGi Configuration R6 Class Definition      | oc6dc | osgi.config.r6.definition.class |
| String Property - OSGi Configuration R6      | oc6ps | osgi.config.r6.definition.prop.string |
| Boolean Property - OSGi Configuration R6      | oc6pb | osgi.config.r6.definition.prop.bool |
| Int Property - OSGi Configuration R6      | oc6pi | osgi.config.r6.definition.prop.int |
| OSGi Configuration R6 Use Configuration Imports      | oc6ui | osgi.config.r6.use.imports |
| OSGi Configuration R6 Use Configuration  Annotations      | oc6ua | osgi.config.r6.use.annotations |
| OSGi Configuration R6 Use Configuration Class Definition      | oc6uc | osgi.config.r6.use.methods |
| Import package - Feature Toggles      | ofti | osgi.featuretoggles.import |
| Check if feature is enabled - Feature Toggles      | oftc | osgi.featuretoggles.check |
| Inject Feature Toggles interface - Feature Toggles      | oftis | osgi.featuretoggles.injectservice |

### Sling Models - snippets (*.java files)

| Description        | Short Alias           | Verbose in case you forget |
| ------------- |:-------------|:-----|
| Imports - Exporter - Sling Model      | smei | sling.model.exporter.imports |
| Model Annotations - Exporter - Sling Model      | smema | sling.model.exporter.annotations |
| Get Exported Type Method - Exporter - Sling Model      | smeem | sling.model.exporter.exportedTypeMethod |
| Model Definition - Exporter - Sling Model      | smemd | sling.model.exporter.modeDefinition |

### Sling Servlets - snippets (*.java files)

| Description        | Short Alias           | Verbose in case you forget |
| ------------- |:-------------|:-----|
| Sling Servlet Bound by Path Imports      | ss7i | sling.servlet.r7.imports |
| Sling Servlet Bound by Resource Type Annotations      | ss7ra | sling.servlet.r7.resource.annotations |
| Sling Servlet R7 Bound by Path Annotations      | ss7pa | sling.servlet.r7.path.annotations |
| Sling Servlet Bound by Path Imports      | ss6i | sling.servlet.r6.imports |
| Sling Servlet Bound by Resource Type Annotations      | ss6ra | sling.servlet.r6.resource.annotations |
| Sling Servlet R6 Bound by Path Annotations      | ss7pa | sling.servlet.r6.path.annotations |
| Sling Servlet SCR Imports      | sssi | sling.servlet.scr.imports |
| Sling Servlet SCR Bound by Resource Type Annotations      | sssra | sling.servlet.scr.resource.annotations |
| Sling Servlet SCR Bound by Path Annotations      | ssspa | sling.servlet.scr.path.annotations |
| Sling Servlet All Methods Class Definition      | sscall | sling.servlet.class.allMethods |
| Sling Servlet Safe Methods Class Definition      | sscsafe | sling.servlet.class.safeMethods |
| Sling Servlet JSON Response      | ssresj | sling.servlet.response.json |
| Sling Servlet HTML Response      | ssresh | sling.servlet.response.html |
| Sling Servlet PLain Text Response      | ssrespt | sling.servlet.response.plainText |
| Sling Servlet Get Query String Parameter from Request      | ssreqqs | sling.servlet.request.getQueryString |

### ReactJs - snippets (*.js files)

| Description        | Short Alias           | Verbose in case you forget |
| ------------- |:-------------|:-----|
| Component Imports - React - AEM      | arci | aem.react.component.imports |
| Component EditConfig - React - AEM      | arcec | aem.react.component.editConfig |
| Component Definition - React - AEM      | arcd | aem.react.component.definition |
| Map to AEM Component - React - AEM      | arcm | aem.react.component.mapTo |

### Touch UI - Dialogs - snippets (*.xml files)

| Description        | Short Alias           | Verbose in case you forget |
| ------------- |:-------------|:-----|
| Dialog Node - Touch UI Dialog      | adtd | aem.dlg.touch.dialog |
| Checkbox - Touch UI Dialog      | adtch | aem.dlg.touch.checkbox |
| Textfield - Touch UI Dialog      | adttf | aem.dlg.touch.textfield |
| Textarea - Touch UI Dialog      | adtta | aem.dlg.touch.textarea |
| Pathfield - Touch UI Dialog      | adtpf | aem.dlg.touch.pathfield |
| Image - Touch UI Dialog      | adti | aem.dlg.touch.image |
| DropDown - Touch UI Dialog      | adtdd | aem.dlg.touch.dropdown |
| DropDown Item - Touch UI Dialog      | adtddi | aem.dlg.touch.dropdown.item |

### OSGi configuration - snippets (*.xml files)

| Description        | Short Alias           | Verbose in case you forget |
| ------------- |:-------------|:-----|
| OSGi config header      | ocxh | osgi.config.xml.header |
| Feature Toggles - OSGi config      | ocxff | osgi.config.xml.featureFlag |

### Classic UI - Dialogs - snippets (*.xml files)

| Description        | Short Alias           | Verbose in case you forget |
| ------------- |:-------------|:-----|
| Dialog Node - Classic UI Dialog      | adcd | aem.dlg.classic.dialog |
| Checkbox - Classic UI Dialog      | adcch | aem.dlg.classic.checkbox |
| Textfield - Classic UI Dialog      | adctf | aem.dlg.classic.textfield |
| Textarea - Classic UI Dialog      | adcta | aem.dlg.classic.textarea |
| Pathfield - Classic UI Dialog      | adcpf | aem.dlg.classic.pathfield |
| DropDown - Classic UI Dialog      | adcdd | aem.dlg.classic.dropdown |
| DropDown Item - Classic UI Dialog      | adcddi | aem.dlg.classic.dropdown.item |
| Include Fragment - Classic UI Dialog      | adcif | aem.dlg.classic.includefragment |

### JSP - snippets (*.html files)

| Description        | Short Alias           | Verbose in case you forget |
| ------------- |:-------------|:-----|
| JSP Comments      | jeco | jsp.elem.comments |
| Include Global Objects      | jeigo | jsp.elem.inc.globalobjects |
| Get OSGi Bundle Version Imports      | jeif | jsp.elem.if |
| JSP choose conditional Element      | jecho | jsp.elem.choose |
| JSP When - choose conditional Element      | jechow | jsp.elem.choose.when |
| JSP Otherwise - choose conditional Element      | jechot | jsp.elem.choose.otherwise |
| JSP For Element      | jefor | jsp.elem.for |
| JSP Foreach Element      | jeforeach | jsp.elem.foreach |


## Known Issues

NONE for now :D

## Release Notes

## 0.9.0

Fixed prefix and descriptions for a couple of the touch and htl snippets and also added snippets for Classic UI dialogs and jsp files

## 0.8.0

Fixed prefix and descriptions for a couple of the snippets and also added the existing list of snippets to the README.md file

## 0.7.0

Feature toggle, ReactJs snippets and also HTL snippets for HTML files for lists, clientlibs, templates, variables and new field types for Touch UI dialogs

## 0.6.0

Snippets for creating r6 configurations, use them and also for creating json objects manually

## 0.5.0

Sling servlet snippets for older annotations

## 0.4.0

Sling servlet and osgi snippets

## 0.3.0

Touch UI Dialog Textfield and checkbox snippets

### 0.1.0

Simple htl snippets for incluiding components, scripts and models into an htl script
