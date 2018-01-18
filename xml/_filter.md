<?xml version="1.0" encoding="utf-8"?>
<filter>
  <apiFilter apply="true">
    <namespaceFilter name="Microsoft.Practices.EnterpriseLibrary.TransientFaultHandling">
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <namespaceFilter name="Microsoft.IdentityModel.Clients.ActiveDirectory.Exceptions">
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <namespaceFilter name="Microsoft.Azure.Graphs">
      <typeFilter name="GraphCommand" expose="false">
      </typeFilter>
      <typeFilter name="__" expose="false">
      </typeFilter>
      <typeFilter name="PartitionStrategy" expose="false">
      </typeFilter>
      <typeFilter name="PartitionStrategy.Builder" expose="false">
      </typeFilter>
      <typeFilter name="T" expose="false">
      </typeFilter>
    </namespaceFilter>
    <namespaceFilter name="Microsoft.Azure.Graphs">
      <typeFilter name="GraphTraversal" expose="false">
      </typeFilter>
    </namespaceFilter>
    <namespaceFilter name="Microsoft.Azure.Graphs.Common">
      <typeFilter name="*" expose="false">
      </typeFilter>
    </namespaceFilter>
        <namespaceFilter name="Microsoft.Azure.Graphs.Translator">
      <typeFilter name="*" expose="false">
      </typeFilter>
    </namespaceFilter>
        <namespaceFilter name="Microsoft.Azure.Graphs.Translator.Enums">
      <typeFilter name="*" expose="false">
      </typeFilter>
    </namespaceFilter>
        <namespaceFilter name="Microsoft.Azure.Graphs">
      <typeFilter name="GraphCommand" expose="false">
      </typeFilter>
    </namespaceFilter>
    <namespaceFilter name="Mono.CompilerServices.SymbolWriter">
      <typeFilter name="*" expose="false">
      </typeFilter>
    </namespaceFilter>
    <namespaceFilter name="Mono.Security.Cryptography">
      <typeFilter name="*" expose="false">
      </typeFilter>
    </namespaceFilter>
    <namespaceFilter name="Mono.CSharp.Nullable">
      <typeFilter name="*" expose="false">
      </typeFilter>
    </namespaceFilter>
    <namespaceFilter name="Mono.CSharp.Linq">
      <typeFilter name="*" expose="false">
      </typeFilter>
    </namespaceFilter>
    <namespaceFilter name="Mono.CSharp">
      <typeFilter name="*" expose="false">
      </typeFilter>
    </namespaceFilter>
    <namespaceFilter name="*">
      <typeFilter name="*">
        <attributeFilter name="System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)" expose="false"/>
        <attributeFilter name="NativeCppClass" expose="false"/>
        <memberFilter name="*">
          <attributeFilter name="System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)" expose="false"/>
        </memberFilter>
      </typeFilter>
    </namespaceFilter>
  </apiFilter>
  <attributeFilter apply="true">
    <!-- Most attributes in System.ComponentModel control designer behavior. Don't show them. -->
    <!-- The exceptions are attributes relating to data binding. Do show them. -->
    <namespaceFilter name="System.ComponentModel">
      <typeFilter name="BindableAttribute" expose="true" />
      <typeFilter name="BrowsableAttribute" expose="true" />
      <typeFilter name="ComplexBindingPropertiesAttribute" expose="true" />
      <typeFilter name="DataObjectAttribute" expose="true" />
      <typeFilter name="DefaultBindingPropertyAttribute" expose="true" />
      <typeFilter name="ListBindableAttribute" expose="true" />
      <typeFilter name="LookupBindingPropertiesAttribute" expose="true" />
      <typeFilter name="SettingsBindableAttribute" expose="true" />
      <typeFilter name="TypeConverterAttribute" expose="true" />
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <namespaceFilter name="System.ComponentModel.Design">
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <namespaceFilter name="System.ComponentModel.Design.Serialization">
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <!-- Most attributes in System.Diagnostics control debugger behavior. Don't show them. -->
    <namespaceFilter name="System.Diagnostics">
      <typeFilter name="ConditionalAttribute" expose="true" />
      <typeFilter name="EventLogPermissionAttribute" expose="true" />
      <typeFilter name="PerformanceCounterPermissionAttribute" expose="true" />
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <!-- Attributes in System.Diagnostics.CodeAnalysis control interaction with FxCop. Don't show them. -->
    <namespaceFilter name="System.Diagnostics.CodeAnalysis">
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <!-- Attributes in System.EnterpriseServices control obscure details of COM+ interop. Don't show them. -->
    <namespaceFilter name="System.EnterpriseServices">
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <!-- The DefaultMember attribute is usually compiler-generated. Users will see it from the member syntax. -->
    <namespaceFilter name="System.Reflection">
      <typeFilter name="DefaultMemberAttribute" expose="false" />
      <typeFilter name="*" expose="true" />
    </namespaceFilter>
    <!-- Attributes in System.Runtime.CompilerServices control obscure details of compilation. Don't show them. -->
    <namespaceFilter name="System.Runtime.CompilerServices">
      <typeFilter name="ExtensionAttribute" expose="true" />
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <!-- Attributes in System.Runtime.ConstrinedExecution control obscure details of compilation. Don't show them. -->
    <namespaceFilter name="System.Runtime.ConstrainedExecution">
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <!-- Most attributes in System.Runtime.InteropServices control obscure details of COM interop. Don't show them. -->
    <namespaceFilter name="System.Runtime.InteropServices">
      <typeFilter name="ComVisibleAttribute" expose="true" />
      <typeFilter name="GuidAttribute" expose="true" />
      <typeFilter name="ClassInterfaceAttribute" expose="true" />
      <typeFilter name="InterfaceTypeAttribute" expose="true" />
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <!-- Attributes in System.Runtime.Versioning control details of resource loading. Don't show them. -->
    <namespaceFilter name="System.Runtime.Versioning">
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <!-- Attributes in System.Security might hint as security implementation details. Don't show them. -->
    <namespaceFilter name="System.Security">
      <typeFilter name="SecurityCriticalAttribute" expose="true" />
      <typeFilter name="SecurityTreatAsSafeAttribute" expose="true" />
      <typeFilter name="AllowPartiallyTrustedCallersAttribute" expose="true" />
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <!-- Attributes in System.Web.Compilation control interaction with the Expression designer. Don't show them. -->
    <namespaceFilter name="System.Web.Compilation">
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <!-- The ASP.NET team only wants these attributes exposed from their namespace. Their logic ecscapes me, but here it is. -->
    <namespaceFilter name="System.Web.UI">
      <typeFilter name="ControlValuePropertyAttribute" expose="true" />
      <typeFilter name="PersistenceModeAttribute" expose="true" />
      <typeFilter name="ValidationPropertyAttribute" expose="true" />
      <typeFilter name="WebResourceAttribute" expose="true" />
      <typeFilter name="TemplateContainerAttribute" expose="true" />
      <typeFilter name="ThemeableAttribute" expose="true" />
      <typeFilter name="TemplateInstanceAttribute" expose="true" />
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <!-- Don't show attributes related to XAML serialization details. -->
    <namespaceFilter name="System.Windows.Markup">
      <typeFilter name="ConstructorArgumentAttribute" expose="false" />
      <typeFilter name="DesignerSerializationOptionsAttribute" expose="false" />
      <typeFilter name="ValueSerializerAttribute" expose="false" />
      <typeFilter name="XmlnsCompatibleWithAttribute" expose="false" />
      <typeFilter name="XmlnsDefinitionAttribute" expose="false" />
      <typeFilter name="XmlnsPrefixAttribute" expose="false" />
      <typeFilter name="*" expose="true" />
    </namespaceFilter>
    <!-- Attributes in System.Xml.Serialization control obscure details of XML serialization. Don't show them.-->
    <namespaceFilter name="System.Xml.Serialization">
      <typeFilter name="*" expose="false" />
    </namespaceFilter>
    <!-- The GeneratedCodeAttribute is useful only to tools, and should be hidden from end users.-->
    <namespaceFilter name="System.CodeDom.Compiler">
      <typeFilter name="GeneratedCodeAttribute" expose="false" />
      <typeFilter name="*" expose="true" />
    </namespaceFilter>
    <namespaceFilter name="*">
      <typeFilter name="*" expose="true" />
    </namespaceFilter>
  </attributeFilter>
</filter>