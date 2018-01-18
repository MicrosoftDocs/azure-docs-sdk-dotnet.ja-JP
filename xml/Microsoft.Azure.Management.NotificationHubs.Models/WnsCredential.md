<Type Name="WnsCredential" FullName="Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential">
  <TypeSignature Language="C#" Value="public class WnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WnsCredential extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class WnsCredential" />
  <TypeSignature Language="F#" Value="type WnsCredential = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2d8ee-101">NotificationHub WnsCredential の説明です。</span><span class="sxs-lookup"><span data-stu-id="2d8ee-101">Description of a NotificationHub WnsCredential.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WnsCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2d8ee-102">WnsCredential クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2d8ee-102">Initializes a new instance of the WnsCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WnsCredential (string packageSid = null, string secretKey = null, string windowsLiveEndpoint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string packageSid, string secretKey, string windowsLiveEndpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional packageSid As String = null, Optional secretKey As String = null, Optional windowsLiveEndpoint As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential : string * string * string -&gt; Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential (packageSid, secretKey, windowsLiveEndpoint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="packageSid" Type="System.String" />
        <Parameter Name="secretKey" Type="System.String" />
        <Parameter Name="windowsLiveEndpoint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="packageSid"><span data-ttu-id="2d8ee-103">この資格情報のパッケージ ID。</span><span class="sxs-lookup"><span data-stu-id="2d8ee-103">The package ID for this credential.</span></span></param>
        <param name="secretKey"><span data-ttu-id="2d8ee-104">共有キー。</span><span class="sxs-lookup"><span data-stu-id="2d8ee-104">The secret key.</span></span></param>
        <param name="windowsLiveEndpoint"><span data-ttu-id="2d8ee-105">Windows Live のエンドポイント。</span><span class="sxs-lookup"><span data-stu-id="2d8ee-105">The Windows Live endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="2d8ee-106">WnsCredential クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2d8ee-106">Initializes a new instance of the WnsCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PackageSid">
      <MemberSignature Language="C#" Value="public string PackageSid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PackageSid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.PackageSid" />
      <MemberSignature Language="VB.NET" Value="Public Property PackageSid As String" />
      <MemberSignature Language="F#" Value="member this.PackageSid : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.PackageSid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.packageSid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d8ee-107">取得または、この資格情報のパッケージ ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="2d8ee-107">Gets or sets the package ID for this credential.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretKey">
      <MemberSignature Language="C#" Value="public string SecretKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecretKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.SecretKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretKey As String" />
      <MemberSignature Language="F#" Value="member this.SecretKey : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.SecretKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secretKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d8ee-108">取得または秘密キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="2d8ee-108">Gets or sets the secret key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsLiveEndpoint">
      <MemberSignature Language="C#" Value="public string WindowsLiveEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsLiveEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.WindowsLiveEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowsLiveEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.WindowsLiveEndpoint : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.WnsCredential.WindowsLiveEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.windowsLiveEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2d8ee-109">取得または Windows Live エンドポイントを設定します。</span><span class="sxs-lookup"><span data-stu-id="2d8ee-109">Gets or sets the Windows Live endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>