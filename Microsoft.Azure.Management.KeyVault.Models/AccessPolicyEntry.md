<Type Name="AccessPolicyEntry" FullName="Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry">
  <TypeSignature Language="C#" Value="public class AccessPolicyEntry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AccessPolicyEntry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry" />
  <TypeSignature Language="VB.NET" Value="Public Class AccessPolicyEntry" />
  <TypeSignature Language="F#" Value="type AccessPolicyEntry = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4ca82-101">Key vault にアクセスできる id です。</span><span class="sxs-lookup"><span data-stu-id="4ca82-101">An identity that have access to the key vault.</span></span> <span data-ttu-id="4ca82-102">配列内のすべての id は、key vault のテナント ID と同じテナント ID を使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4ca82-102">All identities in the array must use the same tenant ID as the key vault's tenant ID.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessPolicyEntry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4ca82-103">AccessPolicyEntry クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4ca82-103">Initializes a new instance of the AccessPolicyEntry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessPolicyEntry (Guid tenantId, string objectId, Microsoft.Azure.Management.KeyVault.Models.Permissions permissions, Nullable&lt;Guid&gt; applicationId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid tenantId, string objectId, class Microsoft.Azure.Management.KeyVault.Models.Permissions permissions, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; applicationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry.#ctor(System.Guid,System.String,Microsoft.Azure.Management.KeyVault.Models.Permissions,System.Nullable{System.Guid})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry : Guid * string * Microsoft.Azure.Management.KeyVault.Models.Permissions * Nullable&lt;Guid&gt; -&gt; Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry" Usage="new Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry (tenantId, objectId, permissions, applicationId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tenantId" Type="System.Guid" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="permissions" Type="Microsoft.Azure.Management.KeyVault.Models.Permissions" />
        <Parameter Name="applicationId" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="tenantId"><span data-ttu-id="4ca82-104">Key vault への要求の認証に使用する Azure Active Directory テナント ID です。</span><span class="sxs-lookup"><span data-stu-id="4ca82-104">The Azure Active Directory tenant ID that should be used for authenticating requests to the key vault.</span></span></param>
        <param name="objectId"><span data-ttu-id="4ca82-105">ユーザー、サービス プリンシパルまたはコンテナーの Azure Active Directory テナントのセキュリティ グループのオブジェクト ID。</span><span class="sxs-lookup"><span data-stu-id="4ca82-105">The object ID of a user, service principal or security group in the Azure Active Directory tenant for the vault.</span></span> <span data-ttu-id="4ca82-106">オブジェクト ID は、アクセス ポリシーの一覧については一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="4ca82-106">The object ID must be unique for the list of access policies.</span></span></param>
        <param name="permissions"><span data-ttu-id="4ca82-107">に対するアクセス許可 id がキー、機密情報および証明書。</span><span class="sxs-lookup"><span data-stu-id="4ca82-107">Permissions the identity has for keys, secrets and certificates.</span></span></param>
        <param name="applicationId"> <span data-ttu-id="4ca82-108">プリンシパルに代わって要求を行っているクライアントのアプリケーション ID</span><span class="sxs-lookup"><span data-stu-id="4ca82-108">Application ID of the client making request on behalf of a principal</span></span></param>
        <summary>
            <span data-ttu-id="4ca82-109">AccessPolicyEntry クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4ca82-109">Initializes a new instance of the AccessPolicyEntry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ApplicationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ApplicationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry.ApplicationId" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ApplicationId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry.ApplicationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4ca82-110">取得またはプリンシパルに代わって要求を行っているクライアントのアプリケーション ID の設定</span><span class="sxs-lookup"><span data-stu-id="4ca82-110">Gets or sets  Application ID of the client making request on behalf of a principal</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectId">
      <MemberSignature Language="C#" Value="public string ObjectId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ObjectId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry.ObjectId" />
      <MemberSignature Language="VB.NET" Value="Public Property ObjectId As String" />
      <MemberSignature Language="F#" Value="member this.ObjectId : string with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry.ObjectId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="objectId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4ca82-111">取得またはコンテナーの Azure Active Directory テナントのユーザー、サービス プリンシパルまたはセキュリティ グループのオブジェクト ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="4ca82-111">Gets or sets the object ID of a user, service principal or security group in the Azure Active Directory tenant for the vault.</span></span> <span data-ttu-id="4ca82-112">オブジェクト ID は、アクセス ポリシーの一覧については一意である必要があります。</span><span class="sxs-lookup"><span data-stu-id="4ca82-112">The object ID must be unique for the list of access policies.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Models.Permissions Permissions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.KeyVault.Models.Permissions Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public Property Permissions As Permissions" />
      <MemberSignature Language="F#" Value="member this.Permissions : Microsoft.Azure.Management.KeyVault.Models.Permissions with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="permissions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Models.Permissions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4ca82-113">取得またはに対するアクセス許可 id がキー、機密情報および証明書を設定します。</span><span class="sxs-lookup"><span data-stu-id="4ca82-113">Gets or sets permissions the identity has for keys, secrets and certificates.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Guid TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As Guid" />
      <MemberSignature Language="F#" Value="member this.TenantId : Guid with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4ca82-114">取得または設定、Azure Active Directory テナント ID、key vault への要求を認証するために使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4ca82-114">Gets or sets the Azure Active Directory tenant ID that should be used for authenticating requests to the key vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="accessPolicyEntry.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4ca82-115">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="4ca82-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4ca82-116">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4ca82-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>