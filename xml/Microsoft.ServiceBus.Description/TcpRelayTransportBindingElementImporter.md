<Type Name="TcpRelayTransportBindingElementImporter" FullName="Microsoft.ServiceBus.Description.TcpRelayTransportBindingElementImporter">
  <TypeSignature Language="C#" Value="public class TcpRelayTransportBindingElementImporter : System.ServiceModel.Description.IPolicyImportExtension, System.ServiceModel.Description.IWsdlImportExtension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TcpRelayTransportBindingElementImporter extends System.Object implements class System.ServiceModel.Description.IPolicyImportExtension, class System.ServiceModel.Description.IWsdlImportExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Description.TcpRelayTransportBindingElementImporter" />
  <TypeSignature Language="VB.NET" Value="Public Class TcpRelayTransportBindingElementImporter&#xA;Implements IPolicyImportExtension, IWsdlImportExtension" />
  <TypeSignature Language="F#" Value="type TcpRelayTransportBindingElementImporter = class&#xA;    interface IWsdlImportExtension&#xA;    interface IPolicyImportExtension" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IPolicyImportExtension</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IWsdlImportExtension</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="edc04-101">WSDL コントラクトとポリシー アサーションを Azure サービス バス TcpRelayTransport バインディングにマップします。</span><span class="sxs-lookup"><span data-stu-id="edc04-101">Maps WSDL contracts and policy assertions into Azure Service Bus TcpRelayTransport bindings.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TcpRelayTransportBindingElementImporter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Description.TcpRelayTransportBindingElementImporter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="edc04-102"><see cref="T:Microsoft.ServiceBus.Description.TcpRelayTransportBindingElementImporter" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="edc04-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Description.TcpRelayTransportBindingElementImporter" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IPolicyImportExtension.ImportPolicy">
      <MemberSignature Language="C#" Value="void IPolicyImportExtension.ImportPolicy (System.ServiceModel.Description.MetadataImporter importer, System.ServiceModel.Description.PolicyConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IPolicyImportExtension.ImportPolicy(class System.ServiceModel.Description.MetadataImporter importer, class System.ServiceModel.Description.PolicyConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Description.TcpRelayTransportBindingElementImporter.System#ServiceModel#Description#IPolicyImportExtension#ImportPolicy(System.ServiceModel.Description.MetadataImporter,System.ServiceModel.Description.PolicyConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ImportPolicy (importer As MetadataImporter, context As PolicyConversionContext) Implements IPolicyImportExtension.ImportPolicy" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IPolicyImportExtension.ImportPolicy(System.ServiceModel.Description.MetadataImporter,System.ServiceModel.Description.PolicyConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importer" Type="System.ServiceModel.Description.MetadataImporter" />
        <Parameter Name="context" Type="System.ServiceModel.Description.PolicyConversionContext" />
      </Parameters>
      <Docs>
        <param name="importer"><span data-ttu-id="edc04-103">使用中の MetadataImporter オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="edc04-103">The MetadataImporter object in use.</span></span></param>
        <param name="context"><span data-ttu-id="edc04-104">インポートできる、両方のポリシー アサーションを含む PolicyConversionContext とバインド要素をバインディング要素を実装することができますの追加先のコレクション。</span><span class="sxs-lookup"><span data-stu-id="edc04-104">The PolicyConversionContext that contains both the policy assertions that can be imported and the collections of binding elements to which implementing binding elements can be added.</span></span></param>
        <summary>
            <span data-ttu-id="edc04-105">カスタム ポリシー アサーションをインポートし、実装するバインド要素を追加</span><span class="sxs-lookup"><span data-stu-id="edc04-105">Import custom policy assertions and add implementing binding elements</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IWsdlImportExtension.BeforeImport">
      <MemberSignature Language="C#" Value="void IWsdlImportExtension.BeforeImport (System.Web.Services.Description.ServiceDescriptionCollection wsdlDocuments, System.Xml.Schema.XmlSchemaSet xmlSchemas, System.Collections.Generic.ICollection&lt;System.Xml.XmlElement&gt; policy);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IWsdlImportExtension.BeforeImport(class System.Web.Services.Description.ServiceDescriptionCollection wsdlDocuments, class System.Xml.Schema.XmlSchemaSet xmlSchemas, class System.Collections.Generic.ICollection`1&lt;class System.Xml.XmlElement&gt; policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Description.TcpRelayTransportBindingElementImporter.System#ServiceModel#Description#IWsdlImportExtension#BeforeImport(System.Web.Services.Description.ServiceDescriptionCollection,System.Xml.Schema.XmlSchemaSet,System.Collections.Generic.ICollection{System.Xml.XmlElement})" />
      <MemberSignature Language="VB.NET" Value="Sub BeforeImport (wsdlDocuments As ServiceDescriptionCollection, xmlSchemas As XmlSchemaSet, policy As ICollection(Of XmlElement)) Implements IWsdlImportExtension.BeforeImport" />
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
        <param name="wsdlDocuments"><span data-ttu-id="edc04-106">インポートする WSDL ドキュメントのコレクション。</span><span class="sxs-lookup"><span data-stu-id="edc04-106">The collection of WSDL documents that are to be imported.</span></span></param>
        <param name="xmlSchemas"><span data-ttu-id="edc04-107">インポートする XML スキーマ ドキュメントのコレクション。</span><span class="sxs-lookup"><span data-stu-id="edc04-107">The collection of XML Schema documents that are to be imported.</span></span></param>
        <param name="policy"><span data-ttu-id="edc04-108">インポートするポリシー アサーションのコレクション。</span><span class="sxs-lookup"><span data-stu-id="edc04-108">The collection of policy assertions that are to be imported.</span></span></param>
        <summary>
            <span data-ttu-id="edc04-109">インポートする WSDL ドキュメントの WSDL バインドにカスタム ポリシー アサーションを追加します。</span><span class="sxs-lookup"><span data-stu-id="edc04-109">Adds custom policy assertions to the WSDL bindings in WSDL documents that are to be imported.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IWsdlImportExtension.ImportContract">
      <MemberSignature Language="C#" Value="void IWsdlImportExtension.ImportContract (System.ServiceModel.Description.WsdlImporter importer, System.ServiceModel.Description.WsdlContractConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IWsdlImportExtension.ImportContract(class System.ServiceModel.Description.WsdlImporter importer, class System.ServiceModel.Description.WsdlContractConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Description.TcpRelayTransportBindingElementImporter.System#ServiceModel#Description#IWsdlImportExtension#ImportContract(System.ServiceModel.Description.WsdlImporter,System.ServiceModel.Description.WsdlContractConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ImportContract (importer As WsdlImporter, context As WsdlContractConversionContext) Implements IWsdlImportExtension.ImportContract" />
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
        <param name="importer"><span data-ttu-id="edc04-110">インポーター。</span><span class="sxs-lookup"><span data-stu-id="edc04-110">The importer.</span></span></param>
        <param name="context"><span data-ttu-id="edc04-111">変更するインポート コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="edc04-111">The import context to be modified.</span></span></param>
        <summary>
            <span data-ttu-id="edc04-112">コントラクトをインポートするときに呼び出します。</span><span class="sxs-lookup"><span data-stu-id="edc04-112">Called when importing a contract.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IWsdlImportExtension.ImportEndpoint">
      <MemberSignature Language="C#" Value="void IWsdlImportExtension.ImportEndpoint (System.ServiceModel.Description.WsdlImporter importer, System.ServiceModel.Description.WsdlEndpointConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IWsdlImportExtension.ImportEndpoint(class System.ServiceModel.Description.WsdlImporter importer, class System.ServiceModel.Description.WsdlEndpointConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Description.TcpRelayTransportBindingElementImporter.System#ServiceModel#Description#IWsdlImportExtension#ImportEndpoint(System.ServiceModel.Description.WsdlImporter,System.ServiceModel.Description.WsdlEndpointConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ImportEndpoint (importer As WsdlImporter, context As WsdlEndpointConversionContext) Implements IWsdlImportExtension.ImportEndpoint" />
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
        <Parameter Name="context" Type="System.ServiceModel.Description.WsdlEndpointConversionContext" />
      </Parameters>
      <Docs>
        <param name="importer"><span data-ttu-id="edc04-113">インポーター。</span><span class="sxs-lookup"><span data-stu-id="edc04-113">The importer.</span></span></param>
        <param name="context"><span data-ttu-id="edc04-114">変更するインポート コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="edc04-114">The import context to be modified.</span></span></param>
        <summary>
            <span data-ttu-id="edc04-115">エンドポイントのインポート時に呼び出します。</span><span class="sxs-lookup"><span data-stu-id="edc04-115">Called when importing an endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>