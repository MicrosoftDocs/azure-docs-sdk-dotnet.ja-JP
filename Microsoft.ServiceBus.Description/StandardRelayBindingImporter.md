<Type Name="StandardRelayBindingImporter" FullName="Microsoft.ServiceBus.Description.StandardRelayBindingImporter">
  <TypeSignature Language="C#" Value="public class StandardRelayBindingImporter : System.ServiceModel.Description.IWsdlImportExtension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StandardRelayBindingImporter extends System.Object implements class System.ServiceModel.Description.IWsdlImportExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Description.StandardRelayBindingImporter" />
  <TypeSignature Language="VB.NET" Value="Public Class StandardRelayBindingImporter&#xA;Implements IWsdlImportExtension" />
  <TypeSignature Language="F#" Value="type StandardRelayBindingImporter = class&#xA;    interface IWsdlImportExtension" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IWsdlImportExtension</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>WSDL コントラクトとポリシー アサーションを Azure Service Bus は、標準バインディングにマップします。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StandardRelayBindingImporter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Description.StandardRelayBindingImporter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeforeImport">
      <MemberSignature Language="C#" Value="public void BeforeImport (System.Web.Services.Description.ServiceDescriptionCollection wsdlDocuments, System.Xml.Schema.XmlSchemaSet xmlSchemas, System.Collections.Generic.ICollection&lt;System.Xml.XmlElement&gt; policy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void BeforeImport(class System.Web.Services.Description.ServiceDescriptionCollection wsdlDocuments, class System.Xml.Schema.XmlSchemaSet xmlSchemas, class System.Collections.Generic.ICollection`1&lt;class System.Xml.XmlElement&gt; policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Description.StandardRelayBindingImporter.BeforeImport(System.Web.Services.Description.ServiceDescriptionCollection,System.Xml.Schema.XmlSchemaSet,System.Collections.Generic.ICollection{System.Xml.XmlElement})" />
      <MemberSignature Language="VB.NET" Value="Public Sub BeforeImport (wsdlDocuments As ServiceDescriptionCollection, xmlSchemas As XmlSchemaSet, policy As ICollection(Of XmlElement))" />
      <MemberSignature Language="F#" Value="abstract member BeforeImport : System.Web.Services.Description.ServiceDescriptionCollection * System.Xml.Schema.XmlSchemaSet * System.Collections.Generic.ICollection&lt;System.Xml.XmlElement&gt; -&gt; unit&#xA;override this.BeforeImport : System.Web.Services.Description.ServiceDescriptionCollection * System.Xml.Schema.XmlSchemaSet * System.Collections.Generic.ICollection&lt;System.Xml.XmlElement&gt; -&gt; unit" Usage="standardRelayBindingImporter.BeforeImport (wsdlDocuments, xmlSchemas, policy)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IWsdlImportExtension.BeforeImport(System.Web.Services.Description.ServiceDescriptionCollection,System.Xml.Schema.XmlSchemaSet,System.Collections.Generic.ICollection{System.Xml.XmlElement})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="wsdlDocuments" Type="System.Web.Services.Description.ServiceDescriptionCollection" />
        <Parameter Name="xmlSchemas" Type="System.Xml.Schema.XmlSchemaSet" />
        <Parameter Name="policy" Type="System.Collections.Generic.ICollection&lt;System.Xml.XmlElement&gt;" />
      </Parameters>
      <Docs>
        <param name="wsdlDocuments">サービスをについて説明します。</param>
        <param name="xmlSchemas">について説明します、<paramref name="wsdlDocuments" />です。</param>
        <param name="policy">ポリシー要素が含まれています。</param>
        <summary>標準バインドと関連付けられたメタデータ ドキュメントをインポートする前に呼び出します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportContract">
      <MemberSignature Language="C#" Value="public void ImportContract (System.ServiceModel.Description.WsdlImporter importer, System.ServiceModel.Description.WsdlContractConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ImportContract(class System.ServiceModel.Description.WsdlImporter importer, class System.ServiceModel.Description.WsdlContractConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Description.StandardRelayBindingImporter.ImportContract(System.ServiceModel.Description.WsdlImporter,System.ServiceModel.Description.WsdlContractConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ImportContract (importer As WsdlImporter, context As WsdlContractConversionContext)" />
      <MemberSignature Language="F#" Value="abstract member ImportContract : System.ServiceModel.Description.WsdlImporter * System.ServiceModel.Description.WsdlContractConversionContext -&gt; unit&#xA;override this.ImportContract : System.ServiceModel.Description.WsdlImporter * System.ServiceModel.Description.WsdlContractConversionContext -&gt; unit" Usage="standardRelayBindingImporter.ImportContract (importer, context)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IWsdlImportExtension.ImportContract(System.ServiceModel.Description.WsdlImporter,System.ServiceModel.Description.WsdlContractConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importer" Type="System.ServiceModel.Description.WsdlImporter" />
        <Parameter Name="context" Type="System.ServiceModel.Description.WsdlContractConversionContext" />
      </Parameters>
      <Docs>
        <param name="importer"> インポートおよび WSDL メタデータを解決するための WSDL インポーター。</param>
        <param name="context"> WSDL からサービスの説明への変換のコンテキストを提供します。</param>
        <summary>標準バインドに対する WSDL コントラクト情報をインポートします。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportEndpoint">
      <MemberSignature Language="C#" Value="public void ImportEndpoint (System.ServiceModel.Description.WsdlImporter importer, System.ServiceModel.Description.WsdlEndpointConversionContext endpointContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ImportEndpoint(class System.ServiceModel.Description.WsdlImporter importer, class System.ServiceModel.Description.WsdlEndpointConversionContext endpointContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Description.StandardRelayBindingImporter.ImportEndpoint(System.ServiceModel.Description.WsdlImporter,System.ServiceModel.Description.WsdlEndpointConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ImportEndpoint (importer As WsdlImporter, endpointContext As WsdlEndpointConversionContext)" />
      <MemberSignature Language="F#" Value="abstract member ImportEndpoint : System.ServiceModel.Description.WsdlImporter * System.ServiceModel.Description.WsdlEndpointConversionContext -&gt; unit&#xA;override this.ImportEndpoint : System.ServiceModel.Description.WsdlImporter * System.ServiceModel.Description.WsdlEndpointConversionContext -&gt; unit" Usage="standardRelayBindingImporter.ImportEndpoint (importer, endpointContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IWsdlImportExtension.ImportEndpoint(System.ServiceModel.Description.WsdlImporter,System.ServiceModel.Description.WsdlEndpointConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importer" Type="System.ServiceModel.Description.WsdlImporter" />
        <Parameter Name="endpointContext" Type="System.ServiceModel.Description.WsdlEndpointConversionContext" />
      </Parameters>
      <Docs>
        <param name="importer"> インポートおよび WSDL メタデータを解決するための WSDL インポーター。</param>
        <param name="endpointContext"> 変換のコンテキスト。</param>
        <summary>サービスの説明を WSDL で定義されているエンドポイントにマップします。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>