<Type Name="ServiceBusErrorData" FullName="Microsoft.ServiceBus.ServiceBusErrorData">
  <TypeSignature Language="C#" Value="public class ServiceBusErrorData : System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusErrorData extends System.Object implements class System.Runtime.Serialization.IExtensibleDataObject" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ServiceBusErrorData" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusErrorData&#xA;Implements IExtensibleDataObject" />
  <TypeSignature Language="F#" Value="type ServiceBusErrorData = class&#xA;    interface IExtensibleDataObject" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
    <summary><span data-ttu-id="4e221-101">Service bus エラーに関連付けられているデータを表します。</span><span class="sxs-lookup"><span data-stu-id="4e221-101">Represents the data associated with the service bus error.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusErrorData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusErrorData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="4e221-102"><see cref="T:Microsoft.ServiceBus.ServiceBusErrorData" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4e221-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.ServiceBusErrorData" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public int Code { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusErrorData.Code" />
      <MemberSignature Language="VB.NET" Value="Public Property Code As Integer" />
      <MemberSignature Language="F#" Value="member this.Code : int with get, set" Usage="Microsoft.ServiceBus.ServiceBusErrorData.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="4e221-103">取得またはエラー コードを設定します。</span><span class="sxs-lookup"><span data-stu-id="4e221-103">Gets or sets the error code.</span></span></summary>
        <value><span data-ttu-id="4e221-104">エラー コード。</span><span class="sxs-lookup"><span data-stu-id="4e221-104">The error code.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Detail">
      <MemberSignature Language="C#" Value="public string Detail { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Detail" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusErrorData.Detail" />
      <MemberSignature Language="VB.NET" Value="Public Property Detail As String" />
      <MemberSignature Language="F#" Value="member this.Detail : string with get, set" Usage="Microsoft.ServiceBus.ServiceBusErrorData.Detail" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
        <summary><span data-ttu-id="4e221-105">取得またはエラーの詳細を設定します。</span><span class="sxs-lookup"><span data-stu-id="4e221-105">Gets or sets the error details.</span></span></summary>
        <value><span data-ttu-id="4e221-106">エラーの詳細です。</span><span class="sxs-lookup"><span data-stu-id="4e221-106">The error details.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DetailTag">
      <MemberSignature Language="C#" Value="public const string DetailTag;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DetailTag" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ServiceBusErrorData.DetailTag" />
      <MemberSignature Language="VB.NET" Value="Public Const DetailTag As String " />
      <MemberSignature Language="F#" Value="val mutable DetailTag : string" Usage="Microsoft.ServiceBus.ServiceBusErrorData.DetailTag" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4e221-107">エラーの詳細についてタグです。</span><span class="sxs-lookup"><span data-stu-id="4e221-107">The tag for the error detail.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionData">
      <MemberSignature Language="C#" Value="public System.Runtime.Serialization.ExtensionDataObject ExtensionData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Runtime.Serialization.ExtensionDataObject ExtensionData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.ServiceBusErrorData.ExtensionData" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionData As ExtensionDataObject" />
      <MemberSignature Language="F#" Value="member this.ExtensionData : System.Runtime.Serialization.ExtensionDataObject with get, set" Usage="Microsoft.ServiceBus.ServiceBusErrorData.ExtensionData" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Runtime.Serialization.IExtensibleDataObject.ExtensionData</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.ExtensionDataObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4e221-108">取得またはエラーの拡張データ オブジェクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="4e221-108">Gets or sets the extension data objects for the error.</span></span></summary>
        <value><span data-ttu-id="4e221-109">エラーの拡張データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4e221-109">The extension data objects for the error.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceBusErrorData">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.ServiceBusErrorData GetServiceBusErrorData (System.IO.Stream responseStream);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.ServiceBusErrorData GetServiceBusErrorData(class System.IO.Stream responseStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusErrorData.GetServiceBusErrorData(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetServiceBusErrorData (responseStream As Stream) As ServiceBusErrorData" />
      <MemberSignature Language="F#" Value="static member GetServiceBusErrorData : System.IO.Stream -&gt; Microsoft.ServiceBus.ServiceBusErrorData" Usage="Microsoft.ServiceBus.ServiceBusErrorData.GetServiceBusErrorData responseStream" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ServiceBusErrorData</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="responseStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="responseStream">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceBusErrorData">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.ServiceBusErrorData GetServiceBusErrorData (System.Net.HttpWebResponse webResponse);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.ServiceBusErrorData GetServiceBusErrorData(class System.Net.HttpWebResponse webResponse) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.ServiceBusErrorData.GetServiceBusErrorData(System.Net.HttpWebResponse)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetServiceBusErrorData (webResponse As HttpWebResponse) As ServiceBusErrorData" />
      <MemberSignature Language="F#" Value="static member GetServiceBusErrorData : System.Net.HttpWebResponse -&gt; Microsoft.ServiceBus.ServiceBusErrorData" Usage="Microsoft.ServiceBus.ServiceBusErrorData.GetServiceBusErrorData webResponse" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ServiceBusErrorData</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webResponse" Type="System.Net.HttpWebResponse" />
      </Parameters>
      <Docs>
        <param name="webResponse"><span data-ttu-id="4e221-110">HTTP web 応答です。</span><span class="sxs-lookup"><span data-stu-id="4e221-110">The HTTP web response.</span></span></param>
        <summary><span data-ttu-id="4e221-111">Service bus のエラー データの値を取得します。</span><span class="sxs-lookup"><span data-stu-id="4e221-111">Gets the value of the service bus error data.</span></span></summary>
        <returns><span data-ttu-id="4e221-112">Service bus のエラー データの値。</span><span class="sxs-lookup"><span data-stu-id="4e221-112">The value of the service bus error data.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusCodeTag">
      <MemberSignature Language="C#" Value="public const string HttpStatusCodeTag;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string HttpStatusCodeTag" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ServiceBusErrorData.HttpStatusCodeTag" />
      <MemberSignature Language="VB.NET" Value="Public Const HttpStatusCodeTag As String " />
      <MemberSignature Language="F#" Value="val mutable HttpStatusCodeTag : string" Usage="Microsoft.ServiceBus.ServiceBusErrorData.HttpStatusCodeTag" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4e221-113">HTTP 状態コードのタグ。</span><span class="sxs-lookup"><span data-stu-id="4e221-113">The tag for the HTTP status code.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RootTag">
      <MemberSignature Language="C#" Value="public const string RootTag;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string RootTag" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ServiceBusErrorData.RootTag" />
      <MemberSignature Language="VB.NET" Value="Public Const RootTag As String " />
      <MemberSignature Language="F#" Value="val mutable RootTag : string" Usage="Microsoft.ServiceBus.ServiceBusErrorData.RootTag" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="4e221-114">タグのルートです。</span><span class="sxs-lookup"><span data-stu-id="4e221-114">The tag root.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>