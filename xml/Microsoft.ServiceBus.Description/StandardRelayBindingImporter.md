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
    <summary><span data-ttu-id="91860-101">WSDL コントラクトとポリシー アサーションを Azure Service Bus は、標準バインディングにマップします。</span><span class="sxs-lookup"><span data-stu-id="91860-101">Maps WSDL contracts and policy assertions into Azure Service Bus standard bindings.</span></span></summary>
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
        <param name="wsdlDocuments"><span data-ttu-id="91860-102">サービスをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="91860-102">Describes the service.</span></span></param>
        <param name="xmlSchemas"><span data-ttu-id="91860-103">について説明します、<paramref name="wsdlDocuments" />です。</span><span class="sxs-lookup"><span data-stu-id="91860-103">Describes the <paramref name="wsdlDocuments" />.</span></span></param>
        <param name="policy"><span data-ttu-id="91860-104">ポリシー要素が含まれています。</span><span class="sxs-lookup"><span data-stu-id="91860-104">Contains the policy elements.</span></span></param>
        <summary><span data-ttu-id="91860-105">標準バインドと関連付けられたメタデータ ドキュメントをインポートする前に呼び出します。</span><span class="sxs-lookup"><span data-stu-id="91860-105">Called prior to importing the metadata documents associated with the standard binding.</span></span></summary>
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
        <param name="importer"> <span data-ttu-id="91860-106">インポートおよび WSDL メタデータを解決するための WSDL インポーター。</span><span class="sxs-lookup"><span data-stu-id="91860-106">The WSDL importer for importing and resolving WSDL metadata.</span></span></param>
        <param name="context"> <span data-ttu-id="91860-107">WSDL からサービスの説明への変換のコンテキストを提供します。</span><span class="sxs-lookup"><span data-stu-id="91860-107">Provides the context for the conversion from WSDL to the service description.</span></span></param>
        <summary><span data-ttu-id="91860-108">標準バインドに対する WSDL コントラクト情報をインポートします。</span><span class="sxs-lookup"><span data-stu-id="91860-108">Imports WSDL contract information for standard bindings.</span></span></summary>
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
        <param name="importer"> <span data-ttu-id="91860-109">インポートおよび WSDL メタデータを解決するための WSDL インポーター。</span><span class="sxs-lookup"><span data-stu-id="91860-109">The WSDL importer for importing and resolving WSDL metadata.</span></span></param>
        <param name="endpointContext"> <span data-ttu-id="91860-110">変換のコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="91860-110">The context for the conversion.</span></span></param>
        <summary><span data-ttu-id="91860-111">サービスの説明を WSDL で定義されているエンドポイントにマップします。</span><span class="sxs-lookup"><span data-stu-id="91860-111">Maps endpoints defined in WSDL into the service description.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>