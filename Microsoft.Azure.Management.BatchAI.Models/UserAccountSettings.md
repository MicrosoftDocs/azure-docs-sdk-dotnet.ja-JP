<Type Name="UserAccountSettings" FullName="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings">
  <TypeSignature Language="C#" Value="public class UserAccountSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserAccountSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class UserAccountSettings" />
  <TypeSignature Language="F#" Value="type UserAccountSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3a353-101">各クラスターのノード上で作成されるユーザー アカウントの設定です。</span><span class="sxs-lookup"><span data-stu-id="3a353-101">Settings for user account that gets created on each on the nodes of a cluster.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccountSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3a353-102">UserAccountSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3a353-102">Initializes a new instance of the UserAccountSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccountSettings (string adminUserName, string adminUserSshPublicKey = null, string adminUserPassword = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string adminUserName, string adminUserSshPublicKey, string adminUserPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (adminUserName As String, Optional adminUserSshPublicKey As String = null, Optional adminUserPassword As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings : string * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings" Usage="new Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings (adminUserName, adminUserSshPublicKey, adminUserPassword)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="adminUserName" Type="System.String" />
        <Parameter Name="adminUserSshPublicKey" Type="System.String" />
        <Parameter Name="adminUserPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="adminUserName"><span data-ttu-id="3a353-103">管理者アカウントの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="3a353-103">Specifies the name of the administrator account.</span></span></param>
        <param name="adminUserSshPublicKey"><span data-ttu-id="3a353-104">Vm を linux での認証に使用する SSH 公開キーに基づいています。</span><span class="sxs-lookup"><span data-stu-id="3a353-104">SSH public keys used to authenticate with linux based VMs.</span></span> <span data-ttu-id="3a353-105">これは、返されない GET 応答本文にします。</span><span class="sxs-lookup"><span data-stu-id="3a353-105">This does not get returned in a GET response body.</span></span></param>
        <param name="adminUserPassword"><span data-ttu-id="3a353-106">管理者のユーザー パスワード (linux の場合のみ)。</span><span class="sxs-lookup"><span data-stu-id="3a353-106">Admin user Password (linux only).</span></span>
            <span data-ttu-id="3a353-107">これは、返されない GET 応答本文にします。</span><span class="sxs-lookup"><span data-stu-id="3a353-107">This does not get returned in a GET response body.</span></span></param>
        <summary>
            <span data-ttu-id="3a353-108">UserAccountSettings クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3a353-108">Initializes a new instance of the UserAccountSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserName">
      <MemberSignature Language="C#" Value="public string AdminUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserName As String" />
      <MemberSignature Language="F#" Value="member this.AdminUserName : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUserName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a353-109">取得または設定は、管理者アカウントの名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="3a353-109">Gets or sets specifies the name of the administrator account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserPassword">
      <MemberSignature Language="C#" Value="public string AdminUserPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUserPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserPassword As String" />
      <MemberSignature Language="F#" Value="member this.AdminUserPassword : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUserPassword")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a353-110">取得または設定の管理ユーザーのパスワード (linux の場合のみ)。</span><span class="sxs-lookup"><span data-stu-id="3a353-110">Gets or sets admin user Password (linux only).</span></span> <span data-ttu-id="3a353-111">これは、返されない GET 応答本文にします。</span><span class="sxs-lookup"><span data-stu-id="3a353-111">This does not get returned in a GET response body.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminUserSshPublicKey">
      <MemberSignature Language="C#" Value="public string AdminUserSshPublicKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminUserSshPublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserSshPublicKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminUserSshPublicKey As String" />
      <MemberSignature Language="F#" Value="member this.AdminUserSshPublicKey : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.AdminUserSshPublicKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="adminUserSshPublicKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a353-112">取得または linux ベースの Vm での認証に使用する SSH 公開キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="3a353-112">Gets or sets SSH public keys used to authenticate with linux based VMs.</span></span> <span data-ttu-id="3a353-113">これは、返されない GET 応答本文にします。</span><span class="sxs-lookup"><span data-stu-id="3a353-113">This does not get returned in a GET response body.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="userAccountSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3a353-114">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="3a353-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3a353-115">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="3a353-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>