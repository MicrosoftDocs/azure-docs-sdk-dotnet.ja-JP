<Type Name="ServiceBusErrorData" FullName="Microsoft.Azure.NotificationHubs.ServiceBusErrorData">
  <TypeSignature Language="C#" Value="public class ServiceBusErrorData : System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusErrorData extends System.Object implements class System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ServiceBusErrorData" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusErrorData&#xA;Implements IExtensibleDataObject" />
  <TypeSignature Language="F#" Value="type ServiceBusErrorData = class&#xA;    interface IExtensibleDataObject" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Runtime.Serialization.IExtensibleDataObject</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="Error", Namespace="")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="8290b-101">Service bus エラーに関連付けられているデータを表します。</span><span class="sxs-lookup"><span data-stu-id="8290b-101">Represents the data associated with the service bus error.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusErrorData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusErrorData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="8290b-102"><see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusErrorData" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8290b-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.ServiceBusErrorData" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public int Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusErrorData.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As Integer" />
      <MemberSignature Language="F#" Value="member this.Code : int with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusErrorData.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Code", Order=101)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8290b-103">取得またはエラー コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="8290b-103">Gets or sets the error code.</span></span></summary>
        <value><span data-ttu-id="8290b-104">エラー コード。</span><span class="sxs-lookup"><span data-stu-id="8290b-104">The error code.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Detail">
      <MemberSignature Language="C#" Value="public string Detail { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Detail" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusErrorData.Detail" />
      <MemberSignature Language="VB.NET" Value="Public Property Detail As String" />
      <MemberSignature Language="F#" Value="member this.Detail : string with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusErrorData.Detail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="Detail", Order=102)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8290b-105">取得またはエラーの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="8290b-105">Gets or sets the error details.</span></span></summary>
        <value><span data-ttu-id="8290b-106">エラーの詳細です。</span><span class="sxs-lookup"><span data-stu-id="8290b-106">The error details.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailTag">
      <MemberSignature Language="C#" Value="public const string DetailTag;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DetailTag" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ServiceBusErrorData.DetailTag" />
      <MemberSignature Language="VB.NET" Value="Public Const DetailTag As String " />
      <MemberSignature Language="F#" Value="val mutable DetailTag : string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusErrorData.DetailTag" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8290b-107">エラーの詳細についてのタグ。</span><span class="sxs-lookup"><span data-stu-id="8290b-107">The tags for the error detail.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionData">
      <MemberSignature Language="C#" Value="public System.Runtime.Serialization.ExtensionDataObject ExtensionData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Runtime.Serialization.ExtensionDataObject ExtensionData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.ServiceBusErrorData.ExtensionData" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionData As ExtensionDataObject" />
      <MemberSignature Language="F#" Value="member this.ExtensionData : System.Runtime.Serialization.ExtensionDataObject with get, set" Usage="Microsoft.Azure.NotificationHubs.ServiceBusErrorData.ExtensionData" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Runtime.Serialization.IExtensibleDataObject.ExtensionData</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.ExtensionDataObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8290b-108">取得またはエラーの拡張データ オブジェクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="8290b-108">Gets or sets the extension data objects for the error.</span></span></summary>
        <value><span data-ttu-id="8290b-109">エラーの拡張データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="8290b-109">The extension data objects for the error.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceBusErrorData">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.ServiceBusErrorData GetServiceBusErrorData (System.Net.HttpWebResponse webResponse);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.ServiceBusErrorData GetServiceBusErrorData(class System.Net.HttpWebResponse webResponse) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.ServiceBusErrorData.GetServiceBusErrorData(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetServiceBusErrorData (webResponse As HttpWebResponse) As ServiceBusErrorData" />
      <MemberSignature Language="F#" Value="static member GetServiceBusErrorData : System.Net.HttpWebResponse -&gt; Microsoft.Azure.NotificationHubs.ServiceBusErrorData" Usage="Microsoft.Azure.NotificationHubs.ServiceBusErrorData.GetServiceBusErrorData webResponse" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ServiceBusErrorData</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webResponse" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="webResponse"><span data-ttu-id="8290b-110">HTTP web 応答です。</span><span class="sxs-lookup"><span data-stu-id="8290b-110">The HTTP web response.</span></span></param>
        <summary><span data-ttu-id="8290b-111">Service bus のエラー データの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="8290b-111">Gets the value of the service bus error data.</span></span></summary>
        <returns><span data-ttu-id="8290b-112">Service bus のエラー データの値。</span><span class="sxs-lookup"><span data-stu-id="8290b-112">The value of the service bus error data.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusCodeTag">
      <MemberSignature Language="C#" Value="public const string HttpStatusCodeTag;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string HttpStatusCodeTag" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ServiceBusErrorData.HttpStatusCodeTag" />
      <MemberSignature Language="VB.NET" Value="Public Const HttpStatusCodeTag As String " />
      <MemberSignature Language="F#" Value="val mutable HttpStatusCodeTag : string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusErrorData.HttpStatusCodeTag" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8290b-113">HTTP 状態コードのタグ。</span><span class="sxs-lookup"><span data-stu-id="8290b-113">The tag for the HTTP status code.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RootTag">
      <MemberSignature Language="C#" Value="public const string RootTag;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string RootTag" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ServiceBusErrorData.RootTag" />
      <MemberSignature Language="VB.NET" Value="Public Const RootTag As String " />
      <MemberSignature Language="F#" Value="val mutable RootTag : string" Usage="Microsoft.Azure.NotificationHubs.ServiceBusErrorData.RootTag" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8290b-114">タグのルートです。</span><span class="sxs-lookup"><span data-stu-id="8290b-114">The tag root.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>