<Type Name="UserAccount" FullName="Microsoft.Azure.Management.Batch.Models.UserAccount">
  <TypeSignature Language="C#" Value="public class UserAccount" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserAccount extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.UserAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class UserAccount" />
  <TypeSignature Language="F#" Value="type UserAccount = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dc118-101">Azure Batch のノードにユーザーを作成するためのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="dc118-101">Properties used to create a user on an Azure Batch node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.UserAccount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc118-102">UserAccount クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc118-102">Initializes a new instance of the UserAccount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserAccount (string name, string password, Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; elevationLevel = null, Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration linuxUserConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string password, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; elevationLevel, class Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration linuxUserConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.UserAccount.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Batch.Models.ElevationLevel},Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.UserAccount : string * string * Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; * Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration -&gt; Microsoft.Azure.Management.Batch.Models.UserAccount" Usage="new Microsoft.Azure.Management.Batch.Models.UserAccount (name, password, elevationLevel, linuxUserConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="elevationLevel" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt;" />
        <Parameter Name="linuxUserConfiguration" Type="Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="dc118-103">ユーザー アカウント名。</span><span class="sxs-lookup"><span data-stu-id="dc118-103">The name of the user account.</span></span></param>
        <param name="password"><span data-ttu-id="dc118-104">ユーザー アカウントのパスワードです。</span><span class="sxs-lookup"><span data-stu-id="dc118-104">The password for the user account.</span></span></param>
        <param name="elevationLevel"><span data-ttu-id="dc118-105">ユーザー アカウントの昇格レベル。</span><span class="sxs-lookup"><span data-stu-id="dc118-105">The elevation level of the user account.</span></span></param>
        <param name="linuxUserConfiguration"><span data-ttu-id="dc118-106">ユーザー アカウントの Linux 固有のユーザーの構成。</span><span class="sxs-lookup"><span data-stu-id="dc118-106">The Linux-specific user configuration for the user account.</span></span></param>
        <summary>
            <span data-ttu-id="dc118-107">UserAccount クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc118-107">Initializes a new instance of the UserAccount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElevationLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; ElevationLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; ElevationLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.UserAccount.ElevationLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ElevationLevel As Nullable(Of ElevationLevel)" />
      <MemberSignature Language="F#" Value="member this.ElevationLevel : Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.UserAccount.ElevationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="elevationLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.ElevationLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc118-108">取得またはユーザー アカウントの昇格のレベルを設定します。</span><span class="sxs-lookup"><span data-stu-id="dc118-108">Gets or sets the elevation level of the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="dc118-109">nonAdmin - 自動ユーザーは、管理者特権でのアクセス権のない標準ユーザーです。</span><span class="sxs-lookup"><span data-stu-id="dc118-109">nonAdmin - The auto user is a standard user without elevated access.</span></span> <span data-ttu-id="dc118-110">管理 - 自動ユーザー昇格されたアクセス権を持つユーザーは、完全な管理者アクセス許可で操作を行います。</span><span class="sxs-lookup"><span data-stu-id="dc118-110">admin - The auto user is a user with elevated access and operates with full Administrator permissions.</span></span> <span data-ttu-id="dc118-111">既定値は、nonAdmin です。</span><span class="sxs-lookup"><span data-stu-id="dc118-111">The default value is nonAdmin.</span></span> <span data-ttu-id="dc118-112">使用可能な値が含まれます: 'NonAdmin'、'Admin'</span><span class="sxs-lookup"><span data-stu-id="dc118-112">Possible values include: 'NonAdmin', 'Admin'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxUserConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration LinuxUserConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration LinuxUserConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.UserAccount.LinuxUserConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property LinuxUserConfiguration As LinuxUserConfiguration" />
      <MemberSignature Language="F#" Value="member this.LinuxUserConfiguration : Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.UserAccount.LinuxUserConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="linuxUserConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc118-113">ユーザー アカウントの構成を Linux 固有のユーザー設定を取得またはします。</span><span class="sxs-lookup"><span data-stu-id="dc118-113">Gets or sets the Linux-specific user configuration for the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="dc118-114">Windows のプールで指定した場合、このプロパティは無視されます。</span><span class="sxs-lookup"><span data-stu-id="dc118-114">This property is ignored if specified on a Windows pool.</span></span> <span data-ttu-id="dc118-115">指定しない場合、既定のオプションで、ユーザーが作成されます。</span><span class="sxs-lookup"><span data-stu-id="dc118-115">If not specified, the user is created with the default options.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.UserAccount.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.UserAccount.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc118-116">取得またはユーザー アカウントの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="dc118-116">Gets or sets the name of the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.UserAccount.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.UserAccount.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc118-117">取得またはユーザー アカウントのパスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="dc118-117">Gets or sets the password for the user account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.UserAccount.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="userAccount.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dc118-118">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="dc118-118">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dc118-119">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="dc118-119">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>