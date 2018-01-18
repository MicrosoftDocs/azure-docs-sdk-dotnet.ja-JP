<Type Name="ApplicationPackageReference" FullName="Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference">
  <TypeSignature Language="C#" Value="public class ApplicationPackageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationPackageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationPackageReference" />
  <TypeSignature Language="F#" Value="type ApplicationPackageReference = class" />
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
            <span data-ttu-id="959cd-101">Batch アカウントの内部アプリケーション パッケージへのリンクします。</span><span class="sxs-lookup"><span data-stu-id="959cd-101">Link to an application package inside the batch account</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="959cd-102">ApplicationPackageReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="959cd-102">Initializes a new instance of the ApplicationPackageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackageReference (string id, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference : string * string -&gt; Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference" Usage="new Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference (id, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="959cd-103">インストールするアプリケーション パッケージの ID。</span><span class="sxs-lookup"><span data-stu-id="959cd-103">The ID of the application package to install.</span></span> <span data-ttu-id="959cd-104">これは、プールと同じバッチ アカウント内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="959cd-104">This must be inside the same batch account as the pool.</span></span> <span data-ttu-id="959cd-105">これは、できます特定のバージョンまたは既定のバージョンへの参照が存在する場合。</span><span class="sxs-lookup"><span data-stu-id="959cd-105">This can either be a reference to a specific version or the default version if one exists.</span></span></param>
        <param name="version"><span data-ttu-id="959cd-106">展開するアプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="959cd-106">The version of the application to deploy.</span></span> <span data-ttu-id="959cd-107">省略した場合、既定のバージョンは展開されます。</span><span class="sxs-lookup"><span data-stu-id="959cd-107">If omitted, the default version is deployed.</span></span></param>
        <summary>
            <span data-ttu-id="959cd-108">ApplicationPackageReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="959cd-108">Initializes a new instance of the ApplicationPackageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="959cd-109">取得またはインストールするアプリケーション パッケージの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="959cd-109">Gets or sets the ID of the application package to install.</span></span> <span data-ttu-id="959cd-110">これは、プールと同じバッチ アカウント内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="959cd-110">This must be inside the same batch account as the pool.</span></span> <span data-ttu-id="959cd-111">これは、できます特定のバージョンまたは既定のバージョンへの参照が存在する場合。</span><span class="sxs-lookup"><span data-stu-id="959cd-111">This can either be a reference to a specific version or the default version if one exists.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationPackageReference.Validate " />
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
            <span data-ttu-id="959cd-112">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="959cd-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="959cd-113">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="959cd-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="959cd-114">取得または展開するアプリケーションのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="959cd-114">Gets or sets the version of the application to deploy.</span></span> <span data-ttu-id="959cd-115">省略した場合、既定のバージョンは展開されます。</span><span class="sxs-lookup"><span data-stu-id="959cd-115">If omitted, the default version is deployed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="959cd-116">これを省略すると、このアプリケーションの既定のバージョンが指定されていない場合は、要求はエラー コード InvalidApplicationPackageReferences で失敗します。</span><span class="sxs-lookup"><span data-stu-id="959cd-116">If this is omitted, and no default version is specified for this application, the request fails with the error code InvalidApplicationPackageReferences.</span></span> <span data-ttu-id="959cd-117">REST API を直接呼び出すが、HTTP ステータス コードは 409 がします。</span><span class="sxs-lookup"><span data-stu-id="959cd-117">If you are calling the REST API directly, the HTTP status code is 409.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>