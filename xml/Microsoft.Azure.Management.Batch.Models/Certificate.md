<Type Name="Certificate" FullName="Microsoft.Azure.Management.Batch.Models.Certificate">
  <TypeSignature Language="C#" Value="public class Certificate : Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Certificate extends Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.Certificate" />
  <TypeSignature Language="VB.NET" Value="Public Class Certificate&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type Certificate = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Batch.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="76b4e-101">証明書に関する情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="76b4e-101">Contains information about a certificate.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Certificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Certificate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="76b4e-102">証明書のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="76b4e-102">Initializes a new instance of the Certificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Certificate (string id = null, string name = null, string type = null, string etag = null, string thumbprintAlgorithm = null, string thumbprint = null, Microsoft.Azure.Management.Batch.Models.CertificateFormat format = Microsoft.Azure.Management.Batch.Models.CertificateFormat.Pfx, Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState provisioningState = Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState.Succeeded, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState previousProvisioningState = Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState.Succeeded, Nullable&lt;DateTime&gt; previousProvisioningStateTransitionTime = null, string publicData = null, Microsoft.Azure.Management.Batch.Models.DeleteCertificateError deleteCertificateError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string etag, string thumbprintAlgorithm, string thumbprint, valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat format, valuetype Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState previousProvisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; previousProvisioningStateTransitionTime, string publicData, class Microsoft.Azure.Management.Batch.Models.DeleteCertificateError deleteCertificateError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Certificate.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateFormat,Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState,System.Nullable{System.DateTime},Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.Batch.Models.DeleteCertificateError)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.Certificate : string * string * string * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateFormat * Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.Batch.Models.DeleteCertificateError -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="new Microsoft.Azure.Management.Batch.Models.Certificate (id, name, type, etag, thumbprintAlgorithm, thumbprint, format, provisioningState, provisioningStateTransitionTime, previousProvisioningState, previousProvisioningStateTransitionTime, publicData, deleteCertificateError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.Batch.Models.CertificateFormat" />
        <Parameter Name="provisioningState" Type="Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="previousProvisioningState" Type="Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState" />
        <Parameter Name="previousProvisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="publicData" Type="System.String" />
        <Parameter Name="deleteCertificateError" Type="Microsoft.Azure.Management.Batch.Models.DeleteCertificateError" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="76b4e-103">リソースの ID。</span><span class="sxs-lookup"><span data-stu-id="76b4e-103">The ID of the resource.</span></span></param>
        <param name="name"><span data-ttu-id="76b4e-104">リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="76b4e-104">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="76b4e-105">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="76b4e-105">The type of the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="76b4e-106">同時実行ステートメントの使用、リソースの ETag。</span><span class="sxs-lookup"><span data-stu-id="76b4e-106">The ETag of the resource, used for concurrency statements.</span></span></param>
        <param name="thumbprintAlgorithm"><span data-ttu-id="76b4e-107">証明書のサムプリントのアルゴリズム</span><span class="sxs-lookup"><span data-stu-id="76b4e-107">The algorithm of the certificate thumbprint</span></span></param>
        <param name="thumbprint"><span data-ttu-id="76b4e-108">証明書の拇印</span><span class="sxs-lookup"><span data-stu-id="76b4e-108">The thumbprint of the certificate</span></span></param>
        <param name="format"><span data-ttu-id="76b4e-109">証明書の Cer または Pfx のいずれかの形式。</span><span class="sxs-lookup"><span data-stu-id="76b4e-109">The format of the certificate - either Pfx or Cer.</span></span> <span data-ttu-id="76b4e-110">省略した場合、既定値は Pfx にします。</span><span class="sxs-lookup"><span data-stu-id="76b4e-110">If omitted, the default is Pfx.</span></span> <span data-ttu-id="76b4e-111">使用可能な値が含まれます: 'Pfx'、'Cer'</span><span class="sxs-lookup"><span data-stu-id="76b4e-111">Possible values include: 'Pfx', 'Cer'</span></span></param>
        <param name="provisioningState"><span data-ttu-id="76b4e-112">リソースのプロビジョニングの状態</span><span class="sxs-lookup"><span data-stu-id="76b4e-112">The provisioned state of the resource</span></span></param>
        <param name="provisioningStateTransitionTime"><span data-ttu-id="76b4e-113">証明書が、現在の状態を入力する時刻。</span><span class="sxs-lookup"><span data-stu-id="76b4e-113">The time at which the certificate entered its current state.</span></span></param>
        <param name="previousProvisioningState"><span data-ttu-id="76b4e-114">リソースの状態を以前にプロビジョニングします。</span><span class="sxs-lookup"><span data-stu-id="76b4e-114">The previous provisioned state of the resource.</span></span> <span data-ttu-id="76b4e-115">使用可能な値が含まれます: '成功'、'削除'、'失敗'</span><span class="sxs-lookup"><span data-stu-id="76b4e-115">Possible values include: 'Succeeded', 'Deleting', 'Failed'</span></span></param>
        <param name="previousProvisioningStateTransitionTime"><span data-ttu-id="76b4e-116">証明書が以前の状態を入力する時刻。</span><span class="sxs-lookup"><span data-stu-id="76b4e-116">The time at which the certificate entered its previous state.</span></span></param>
        <param name="publicData"><span data-ttu-id="76b4e-117">証明書の公開キー。</span><span class="sxs-lookup"><span data-stu-id="76b4e-117">The public key of the certificate.</span></span></param>
        <param name="deleteCertificateError"><span data-ttu-id="76b4e-118">証明書の削除中に発生したエラー</span><span class="sxs-lookup"><span data-stu-id="76b4e-118">The error which occurred while deleting the certificate</span></span></param>
        <summary>
            <span data-ttu-id="76b4e-119">証明書のクラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="76b4e-119">Initializes a new instance of the Certificate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.DeleteCertificateError DeleteCertificateError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.DeleteCertificateError DeleteCertificateError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.DeleteCertificateError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeleteCertificateError As DeleteCertificateError" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificateError : Microsoft.Azure.Management.Batch.Models.DeleteCertificateError" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.DeleteCertificateError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deleteCertificateError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.DeleteCertificateError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76b4e-120">証明書の削除中に発生したエラーを取得します。</span><span class="sxs-lookup"><span data-stu-id="76b4e-120">Gets the error which occurred while deleting the certificate</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="76b4e-121">証明書 provisioningState は '失敗' ときにのみ返されます。</span><span class="sxs-lookup"><span data-stu-id="76b4e-121">This is only returned when the certificate provisioningState is 'Failed'.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As CertificateFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.Batch.Models.CertificateFormat with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76b4e-122">取得または証明書の Cer または Pfx のいずれかの形式を設定します。</span><span class="sxs-lookup"><span data-stu-id="76b4e-122">Gets or sets the format of the certificate - either Pfx or Cer.</span></span> <span data-ttu-id="76b4e-123">省略した場合、既定値は Pfx にします。</span><span class="sxs-lookup"><span data-stu-id="76b4e-123">If omitted, the default is Pfx.</span></span> <span data-ttu-id="76b4e-124">使用可能な値が含まれます: 'Pfx'、'Cer'</span><span class="sxs-lookup"><span data-stu-id="76b4e-124">Possible values include: 'Pfx', 'Cer'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState PreviousProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState PreviousProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.PreviousProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousProvisioningState As CertificateProvisioningState" />
      <MemberSignature Language="F#" Value="member this.PreviousProvisioningState : Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.PreviousProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.previousProvisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76b4e-125">リソースの以前のプロビジョニング状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="76b4e-125">Gets the previous provisioned state of the resource.</span></span> <span data-ttu-id="76b4e-126">使用可能な値が含まれます: '成功'、'削除'、'失敗'</span><span class="sxs-lookup"><span data-stu-id="76b4e-126">Possible values include: 'Succeeded', 'Deleting', 'Failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.PreviousProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.PreviousProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.previousProvisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76b4e-127">証明書が以前の状態を入力する時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="76b4e-127">Gets the time at which the certificate entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As CertificateProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="76b4e-128">リソースのプロビジョニングの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="76b4e-128">Gets the provisioned state of the resource</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="76b4e-129">値は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="76b4e-129">Values are:</span></span>
            
             <span data-ttu-id="76b4e-130">成功 - 証明書は、プールで使用可能です。</span><span class="sxs-lookup"><span data-stu-id="76b4e-130">Succeeded - The certificate is available for use in pools.</span></span>
             <span data-ttu-id="76b4e-131">削除すると、ユーザーが証明書が削除されることを要求しましたが、削除操作がまだ完了していません。</span><span class="sxs-lookup"><span data-stu-id="76b4e-131">Deleting - The user has requested that the certificate be deleted, but the delete operation has not yet completed.</span></span> <span data-ttu-id="76b4e-132">証明書の作成またはプールを更新する場合は参照できません。</span><span class="sxs-lookup"><span data-stu-id="76b4e-132">You may not reference the certificate when creating or updating pools.</span></span>
             <span data-ttu-id="76b4e-133">ユーザー要求に失敗しました - 証明書が削除されること、またはも、証明書への参照が残っているプールが 1 つまたは複数のコンピューティング ノードにまだインストールされています。</span><span class="sxs-lookup"><span data-stu-id="76b4e-133">Failed - The user requested that the certificate be deleted, but there are pools that still have references to the certificate, or it is still installed on one or more compute nodes.</span></span> <span data-ttu-id="76b4e-134">(後者発生する可能性が証明書は、プールから削除されましたが、ノードがまだ再起動されていない場合。</span><span class="sxs-lookup"><span data-stu-id="76b4e-134">(The latter can occur if the certificate has been removed from the pool, but the node has not yet restarted.</span></span> <span data-ttu-id="76b4e-135">ノードの更新の証明書は再起動時にのみ。)削除、[キャンセル] を [キャンセル] 証明書の削除操作または削除を再試行する delete 証明書の操作を使用することがあります。</span><span class="sxs-lookup"><span data-stu-id="76b4e-135">Nodes refresh their certificates only when they restart.) You may use the cancel certificate delete operation to cancel the delete, or the delete certificate operation to retry the delete.</span></span> <span data-ttu-id="76b4e-136">使用可能な値が含まれます: '成功'、'削除'、'失敗'</span><span class="sxs-lookup"><span data-stu-id="76b4e-136">Possible values include: 'Succeeded', 'Deleting', 'Failed'</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76b4e-137">証明書が、現在の状態を入力するされた時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="76b4e-137">Gets the time at which the certificate entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicData">
      <MemberSignature Language="C#" Value="public string PublicData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.PublicData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicData As String" />
      <MemberSignature Language="F#" Value="member this.PublicData : string" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.PublicData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76b4e-138">証明書の公開キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="76b4e-138">Gets the public key of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76b4e-139">取得または設定、証明書の拇印</span><span class="sxs-lookup"><span data-stu-id="76b4e-139">Gets or sets the thumbprint of the certificate</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="76b4e-140">これにより、名と拇印が一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="76b4e-140">This must match the thumbprint from the name.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.ThumbprintAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprintAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="76b4e-141">取得または設定、証明書のサムプリントのアルゴリズム</span><span class="sxs-lookup"><span data-stu-id="76b4e-141">Gets or sets the algorithm of the certificate thumbprint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="76b4e-142">これは、証明書名の最初の部分と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="76b4e-142">This must match the first portion of the certificate name.</span></span>
            <span data-ttu-id="76b4e-143">'SHA1' 現在必要です。</span><span class="sxs-lookup"><span data-stu-id="76b4e-143">Currently required to be 'SHA1'.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Certificate.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificate.Validate " />
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
            <span data-ttu-id="76b4e-144">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="76b4e-144">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76b4e-145">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76b4e-145">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>