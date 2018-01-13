<Type Name="SharedAccessSignatureAuthorizationRule" FullName="Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule">
  <TypeSignature Language="C#" Value="public class SharedAccessSignatureAuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessSignatureAuthorizationRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessSignatureAuthorizationRule" />
  <TypeSignature Language="F#" Value="type SharedAccessSignatureAuthorizationRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0264c-101">IoT hub 共有アクセス ポリシーのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="0264c-101">The properties of an IoT hub shared access policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessSignatureAuthorizationRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0264c-102">SharedAccessSignatureAuthorizationRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0264c-102">Initializes a new instance of the SharedAccessSignatureAuthorizationRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessSignatureAuthorizationRule (string keyName, Microsoft.Azure.Management.IotHub.Models.AccessRights rights, string primaryKey = null, string secondaryKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, valuetype Microsoft.Azure.Management.IotHub.Models.AccessRights rights, string primaryKey, string secondaryKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.#ctor(System.String,Microsoft.Azure.Management.IotHub.Models.AccessRights,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String, rights As AccessRights, Optional primaryKey As String = null, Optional secondaryKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule : string * Microsoft.Azure.Management.IotHub.Models.AccessRights * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule" Usage="new Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule (keyName, rights, primaryKey, secondaryKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="rights" Type="Microsoft.Azure.Management.IotHub.Models.AccessRights" />
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="secondaryKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName"><span data-ttu-id="0264c-103">共有アクセス ポリシーの名前。</span><span class="sxs-lookup"><span data-stu-id="0264c-103">The name of the shared access policy.</span></span></param>
        <param name="rights"><span data-ttu-id="0264c-104">共有アクセス ポリシーに割り当てられた権限。</span><span class="sxs-lookup"><span data-stu-id="0264c-104">The permissions assigned to the shared access policy.</span></span> <span data-ttu-id="0264c-105">使用可能な値が含まれます: 'RegistryRead'、'RegistryWrite'、'接続'、'DeviceConnect'、'RegistryRead、RegistryWrite'、'RegistryRead、接続、'RegistryRead, DeviceConnect'、'RegistryWrite、接続、' RegistryWrite、DeviceConnect'、'接続、DeviceConnect'、'RegistryRead、RegistryWrite、接続'、'RegistryRead、RegistryWrite、DeviceConnect'、'RegistryRead、接続、DeviceConnect'、'RegistryWrite、接続、DeviceConnect' 'RegistryRead、RegistryWrite、接続、DeviceConnect'</span><span class="sxs-lookup"><span data-stu-id="0264c-105">Possible values include: 'RegistryRead', 'RegistryWrite', 'ServiceConnect', 'DeviceConnect', 'RegistryRead, RegistryWrite', 'RegistryRead, ServiceConnect', 'RegistryRead, DeviceConnect', 'RegistryWrite, ServiceConnect', 'RegistryWrite, DeviceConnect', 'ServiceConnect, DeviceConnect', 'RegistryRead, RegistryWrite, ServiceConnect', 'RegistryRead, RegistryWrite, DeviceConnect', 'RegistryRead, ServiceConnect, DeviceConnect', 'RegistryWrite, ServiceConnect, DeviceConnect', 'RegistryRead, RegistryWrite, ServiceConnect, DeviceConnect'</span></span></param>
        <param name="primaryKey"><span data-ttu-id="0264c-106">主キー。</span><span class="sxs-lookup"><span data-stu-id="0264c-106">The primary key.</span></span></param>
        <param name="secondaryKey"><span data-ttu-id="0264c-107">セカンダリ キー。</span><span class="sxs-lookup"><span data-stu-id="0264c-107">The secondary key.</span></span></param>
        <summary>
            <span data-ttu-id="0264c-108">SharedAccessSignatureAuthorizationRule クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0264c-108">Initializes a new instance of the SharedAccessSignatureAuthorizationRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0264c-109">取得または共有アクセス ポリシーの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="0264c-109">Gets or sets the name of the shared access policy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryKey">
      <MemberSignature Language="C#" Value="public string PrimaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.PrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryKey : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.PrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0264c-110">取得または主キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="0264c-110">Gets or sets the primary key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rights">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.AccessRights Rights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.IotHub.Models.AccessRights Rights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.Rights" />
      <MemberSignature Language="VB.NET" Value="Public Property Rights As AccessRights" />
      <MemberSignature Language="F#" Value="member this.Rights : Microsoft.Azure.Management.IotHub.Models.AccessRights with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.Rights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rights")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.AccessRights</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0264c-111">取得または共有アクセス ポリシーへのアクセス許可を設定します。</span><span class="sxs-lookup"><span data-stu-id="0264c-111">Gets or sets the permissions assigned to the shared access policy.</span></span>
            <span data-ttu-id="0264c-112">使用可能な値が含まれます: 'RegistryRead'、'RegistryWrite'、'接続'、'DeviceConnect'、'RegistryRead、RegistryWrite'、'RegistryRead、接続、'RegistryRead, DeviceConnect'、'RegistryWrite、接続、' RegistryWrite、DeviceConnect'、'接続、DeviceConnect'、'RegistryRead、RegistryWrite、接続'、'RegistryRead、RegistryWrite、DeviceConnect'、'RegistryRead、接続、DeviceConnect'、'RegistryWrite、接続、DeviceConnect' 'RegistryRead、RegistryWrite、接続、DeviceConnect'</span><span class="sxs-lookup"><span data-stu-id="0264c-112">Possible values include: 'RegistryRead', 'RegistryWrite', 'ServiceConnect', 'DeviceConnect', 'RegistryRead, RegistryWrite', 'RegistryRead, ServiceConnect', 'RegistryRead, DeviceConnect', 'RegistryWrite, ServiceConnect', 'RegistryWrite, DeviceConnect', 'ServiceConnect, DeviceConnect', 'RegistryRead, RegistryWrite, ServiceConnect', 'RegistryRead, RegistryWrite, DeviceConnect', 'RegistryRead, ServiceConnect, DeviceConnect', 'RegistryWrite, ServiceConnect, DeviceConnect', 'RegistryRead, RegistryWrite, ServiceConnect, DeviceConnect'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryKey">
      <MemberSignature Language="C#" Value="public string SecondaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.SecondaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryKey : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.SecondaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0264c-113">取得またはセカンダリ キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="0264c-113">Gets or sets the secondary key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sharedAccessSignatureAuthorizationRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0264c-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="0264c-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0264c-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0264c-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>