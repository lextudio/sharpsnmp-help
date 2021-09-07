# TaggedElementType Class
 


## Inheritance Hierarchy
<a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">System.Object</a><br />&nbsp;&nbsp;<a href="T_Lextm_SharpSnmpPro_Mib_ElementType">Lextm.SharpSnmpPro.Mib.ElementType</a><br />&nbsp;&nbsp;&nbsp;&nbsp;Lextm.SharpSnmpPro.Mib.TaggedElementType<br />
**Namespace:**&nbsp;<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib</a><br />**Assembly:**&nbsp;SharpSnmpPro.Mib (in SharpSnmpPro.Mib.dll) Version: 2.1.2

## Syntax

**C#**<br />
``` C#
public class TaggedElementType : ElementType, 
	ISmiType, IConstruct, IValidatable
```

**VB**<br />
``` VB
Public Class TaggedElementType
	Inherits ElementType
	Implements ISmiType, IConstruct, IValidatable
```

**C++**<br />
``` C++
public ref class TaggedElementType : public ElementType, 
	ISmiType, IConstruct, IValidatable
```

**F#**<br />
``` F#
type TaggedElementType =  
    class
        inherit ElementType
        interface ISmiType
        interface IConstruct
        interface IValidatable
    end
```

The TaggedElementType type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_TaggedElementType__ctor">TaggedElementType</a></td><td>
Initializes a new instance of the TaggedElementType class</td></tr></table>&nbsp;
<a href="#taggedelementtype-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_TaggedElementType_BaseType">BaseType</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_ElementType_CharPositionInLine">CharPositionInLine</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_ElementType">ElementType</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_ElementType_Default">Default</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_ElementType">ElementType</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_ElementType_Line">Line</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_ElementType">ElementType</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_ElementType_Module">Module</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_ElementType">ElementType</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_ElementType_Name">Name</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_ElementType">ElementType</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_ElementType_Optional">Optional</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_ElementType">ElementType</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_ElementType_Subtype">Subtype</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_ElementType">ElementType</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_ElementType_Tag">Tag</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_ElementType">ElementType</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_ElementType_TagDefault">TagDefault</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_ElementType">ElementType</a>.)</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_Lextm_SharpSnmpPro_Mib_ElementType_Value">Value</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_ElementType">ElementType</a>.)</td></tr></table>&nbsp;
<a href="#taggedelementtype-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_ElementType_Append">Append</a></td><td> (Inherited from <a href="T_Lextm_SharpSnmpPro_Mib_ElementType">ElementType</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.equals#System_Object_Equals_System_Object_" target="_blank" rel="noopener noreferrer">Equals</a></td><td>
Determines whether the specified object is equal to the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.finalize#System_Object_Finalize" target="_blank" rel="noopener noreferrer">Finalize</a></td><td>
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gethashcode#System_Object_GetHashCode" target="_blank" rel="noopener noreferrer">GetHashCode</a></td><td>
Serves as the default hash function.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.gettype#System_Object_GetType" target="_blank" rel="noopener noreferrer">GetType</a></td><td>
Gets the <a href="https://docs.microsoft.com/dotnet/api/system.type" target="_blank" rel="noopener noreferrer">Type</a> of the current instance.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.memberwiseclone#System_Object_MemberwiseClone" target="_blank" rel="noopener noreferrer">MemberwiseClone</a></td><td>
Creates a shallow copy of the current <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="https://docs.microsoft.com/dotnet/api/system.object.tostring#System_Object_ToString" target="_blank" rel="noopener noreferrer">ToString</a></td><td>
Returns a string that represents the current object.
 (Inherited from <a href="https://docs.microsoft.com/dotnet/api/system.object" target="_blank" rel="noopener noreferrer">Object</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_TaggedElementType_Validate">Validate</a></td><td /></tr></table>&nbsp;
<a href="#taggedelementtype-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_SmiTypeExtensions_GetLastType">GetLastType</a></td><td>
The true base type of a syntax.
 (Defined by <a href="T_Lextm_SharpSnmpPro_Mib_SmiTypeExtensions">SmiTypeExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_Lextm_SharpSnmpPro_Mib_SmiTypeExtensions_Verify">Verify</a></td><td>
Verifies the input data against the syntax.
 (Defined by <a href="T_Lextm_SharpSnmpPro_Mib_SmiTypeExtensions">SmiTypeExtensions</a>.)</td></tr></table>&nbsp;
<a href="#taggedelementtype-class">Back to Top</a>

## See Also


#### Reference
<a href="N_Lextm_SharpSnmpPro_Mib">Lextm.SharpSnmpPro.Mib Namespace</a><br />