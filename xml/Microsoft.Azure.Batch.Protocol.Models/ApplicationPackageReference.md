<Type Name="ApplicationPackageReference" FullName="Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference">
  <TypeSignature Language="C#" Value="public class ApplicationPackageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationPackageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationPackageReference" />
  <TypeSignature Language="F#" Value="type ApplicationPackageReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="47ea8-101">コンピューティング ノードを展開するアプリケーション パッケージへの参照。</span><span class="sxs-lookup"><span data-stu-id="47ea8-101">A reference to an application package to be deployed to compute nodes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="47ea8-102">ApplicationPackageReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="47ea8-102">Initializes a new instance of the ApplicationPackageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackageReference (string applicationId, string version = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string applicationId, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationId As String, Optional version As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference : string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference" Usage="new Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference (applicationId, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationId"><span data-ttu-id="47ea8-103">展開するアプリケーションの ID。</span><span class="sxs-lookup"><span data-stu-id="47ea8-103">The ID of the application to deploy.</span></span></param>
        <param name="version"><span data-ttu-id="47ea8-104">展開するアプリケーションのバージョン。</span><span class="sxs-lookup"><span data-stu-id="47ea8-104">The version of the application to deploy.</span></span> <span data-ttu-id="47ea8-105">省略した場合、既定のバージョンは展開されます。</span><span class="sxs-lookup"><span data-stu-id="47ea8-105">If omitted, the default version is deployed.</span></span></param>
        <summary>
            <span data-ttu-id="47ea8-106">ApplicationPackageReference クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="47ea8-106">Initializes a new instance of the ApplicationPackageReference class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationId">
      <MemberSignature Language="C#" Value="public string ApplicationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.ApplicationId" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationId As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.ApplicationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="47ea8-107">取得または展開するアプリケーションの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="47ea8-107">Gets or sets the ID of the application to deploy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationPackageReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="47ea8-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="47ea8-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="47ea8-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="47ea8-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="47ea8-110">取得または展開するアプリケーションのバージョンを設定します。</span><span class="sxs-lookup"><span data-stu-id="47ea8-110">Gets or sets the version of the application to deploy.</span></span> <span data-ttu-id="47ea8-111">省略した場合、既定のバージョンは展開されます。</span><span class="sxs-lookup"><span data-stu-id="47ea8-111">If omitted, the default version is deployed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="47ea8-112">プールにこれを省略するし、このアプリケーションの既定のバージョンが指定されていない、要求は、エラー コード InvalidApplicationPackageReferences と HTTP ステータス コード 409 で失敗します。</span><span class="sxs-lookup"><span data-stu-id="47ea8-112">If this is omitted on a pool, and no default version is specified for this application, the request fails with the error code InvalidApplicationPackageReferences and HTTP status code 409.</span></span> <span data-ttu-id="47ea8-113">これをタスクを省略するし、このアプリケーションの既定のバージョンが指定されていない、タスクは、処理前のエラーで失敗します。</span><span class="sxs-lookup"><span data-stu-id="47ea8-113">If this is omitted on a task, and no default version is specified for this application, the task fails with a pre-processing error.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>