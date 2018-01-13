<Type Name="Request" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Request">
  <TypeSignature Language="C#" Value="public class Request" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Request extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Request" />
  <TypeSignature Language="VB.NET" Value="Public Class Request" />
  <TypeSignature Language="F#" Value="type Request = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="17811-101">イベントを生成する要求。</span><span class="sxs-lookup"><span data-stu-id="17811-101">The request that generated the event.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Request ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Request.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="17811-102">要求クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="17811-102">Initializes a new instance of the Request class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Request (string id = null, string addr = null, string host = null, string method = null, string useragent = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string addr, string host, string method, string useragent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Request.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional addr As String = null, Optional host As String = null, Optional method As String = null, Optional useragent As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Request : string * string * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Request" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Request (id, addr, host, method, useragent)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="addr" Type="System.String" />
        <Parameter Name="host" Type="System.String" />
        <Parameter Name="method" Type="System.String" />
        <Parameter Name="useragent" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="17811-103">イベントを開始した要求の ID。</span><span class="sxs-lookup"><span data-stu-id="17811-103">The ID of the request that initiated the event.</span></span></param>
        <param name="addr"><span data-ttu-id="17811-104">IP またはホスト名および可能性のあるイベントを開始したクライアント接続のポートです。</span><span class="sxs-lookup"><span data-stu-id="17811-104">The IP or hostname and possibly port of the client connection that initiated the event.</span></span> <span data-ttu-id="17811-105">これは、標準の http 要求から RemoteAddr です。</span><span class="sxs-lookup"><span data-stu-id="17811-105">This is the RemoteAddr from the standard http request.</span></span></param>
        <param name="host"><span data-ttu-id="17811-106">受信要求の http ホスト ヘッダーで指定したとおり、レジストリのインスタンスの外部からアクセスできるホスト名です。</span><span class="sxs-lookup"><span data-stu-id="17811-106">The externally accessible hostname of the registry instance, as specified by the http host header on incoming requests.</span></span></param>
        <param name="method"><span data-ttu-id="17811-107">イベントを生成した要求メソッド。</span><span class="sxs-lookup"><span data-stu-id="17811-107">The request method that generated the event.</span></span></param>
        <param name="useragent"><span data-ttu-id="17811-108">要求のユーザー エージェント ヘッダー。</span><span class="sxs-lookup"><span data-stu-id="17811-108">The user agent header of the request.</span></span></param>
        <summary>
            <span data-ttu-id="17811-109">要求クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="17811-109">Initializes a new instance of the Request class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Addr">
      <MemberSignature Language="C#" Value="public string Addr { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Addr" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Request.Addr" />
      <MemberSignature Language="VB.NET" Value="Public Property Addr As String" />
      <MemberSignature Language="F#" Value="member this.Addr : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Request.Addr" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="addr")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17811-110">取得または IP またはホスト名および可能性のあるイベントを開始したクライアント接続のポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="17811-110">Gets or sets the IP or hostname and possibly port of the client connection that initiated the event.</span></span> <span data-ttu-id="17811-111">これは、標準の http 要求から RemoteAddr です。</span><span class="sxs-lookup"><span data-stu-id="17811-111">This is the RemoteAddr from the standard http request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public string Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Request.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As String" />
      <MemberSignature Language="F#" Value="member this.Host : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Request.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="host")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17811-112">取得または受信した要求の http ホスト ヘッダーで指定されたレジストリ インスタンスの外部からアクセスできるホスト名を設定します。</span><span class="sxs-lookup"><span data-stu-id="17811-112">Gets or sets the externally accessible hostname of the registry instance, as specified by the http host header on incoming requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Request.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Request.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17811-113">取得またはイベントを開始した要求の ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="17811-113">Gets or sets the ID of the request that initiated the event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Method">
      <MemberSignature Language="C#" Value="public string Method { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Method" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Request.Method" />
      <MemberSignature Language="VB.NET" Value="Public Property Method As String" />
      <MemberSignature Language="F#" Value="member this.Method : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Request.Method" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="method")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17811-114">取得またはイベントを生成する要求メソッドを設定します。</span><span class="sxs-lookup"><span data-stu-id="17811-114">Gets or sets the request method that generated the event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Useragent">
      <MemberSignature Language="C#" Value="public string Useragent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Useragent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Request.Useragent" />
      <MemberSignature Language="VB.NET" Value="Public Property Useragent As String" />
      <MemberSignature Language="F#" Value="member this.Useragent : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Request.Useragent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="useragent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17811-115">取得または、ユーザー エージェント要求のヘッダーを設定します。</span><span class="sxs-lookup"><span data-stu-id="17811-115">Gets or sets the user agent header of the request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>