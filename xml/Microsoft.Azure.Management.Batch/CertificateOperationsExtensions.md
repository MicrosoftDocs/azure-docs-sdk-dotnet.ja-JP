<Type Name="CertificateOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificateOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificateOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificateOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificateOperationsExtensions = class" />
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
            <span data-ttu-id="c7480-101">CertificateOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="c7480-101">Extension methods for CertificateOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate BeginCreate (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate BeginCreate(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String, parameters As CertificateCreateOrUpdateParameters, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Certificate" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreate (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-103">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-103">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-104">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-104">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-105">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-105">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-106">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-106">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-107">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-107">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c7480-108">証明書の作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c7480-108">Additional parameters for certificate creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c7480-109">更新する証明書のエンティティの状態 (ETag) のバージョン。</span><span class="sxs-lookup"><span data-stu-id="c7480-109">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="c7480-110">値"\*"を証明書が既に存在する場合にのみ、操作を適用するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="c7480-110">A value of "\*" can be used to apply the operation only if the certificate already exists.</span></span> <span data-ttu-id="c7480-111">省略した場合、この操作常に使用されます。</span><span class="sxs-lookup"><span data-stu-id="c7480-111">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="c7480-112">設定 ' \*'、新しい証明書を作成するが、既存の証明書の更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="c7480-112">Set to '\*' to allow a new certificate to be created, but to prevent updating an existing certificate.</span></span> <span data-ttu-id="c7480-113">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="c7480-113">Other values will be ignored.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-114">指定されたアカウント内の新しい証明書を作成します。</span><span class="sxs-lookup"><span data-stu-id="c7480-114">Creates a new certificate inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; BeginCreateAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; BeginCreateAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;BeginCreateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-116">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-116">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-117">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-117">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-118">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-118">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-119">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-119">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-120">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-120">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c7480-121">証明書の作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c7480-121">Additional parameters for certificate creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c7480-122">更新する証明書のエンティティの状態 (ETag) のバージョン。</span><span class="sxs-lookup"><span data-stu-id="c7480-122">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="c7480-123">値"\*"を証明書が既に存在する場合にのみ、操作を適用するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="c7480-123">A value of "\*" can be used to apply the operation only if the certificate already exists.</span></span> <span data-ttu-id="c7480-124">省略した場合、この操作常に使用されます。</span><span class="sxs-lookup"><span data-stu-id="c7480-124">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="c7480-125">設定 ' \*'、新しい証明書を作成するが、既存の証明書の更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="c7480-125">Set to '\*' to allow a new certificate to be created, but to prevent updating an existing certificate.</span></span> <span data-ttu-id="c7480-126">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="c7480-126">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7480-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7480-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-128">指定されたアカウント内の新しい証明書を作成します。</span><span class="sxs-lookup"><span data-stu-id="c7480-128">Creates a new certificate inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders BeginDelete (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders BeginDelete(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As CertificateDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDelete (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-129">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-130">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-130">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-131">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-131">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-132">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-132">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-133">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-133">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-134">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-134">For example SHA1-a3d1c5.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-135">指定された証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="c7480-135">Deletes the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;BeginDeleteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-137">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-137">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-138">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-138">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-139">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-139">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-140">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-140">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-141">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-141">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7480-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7480-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-143">指定された証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="c7480-143">Deletes the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletion">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate CancelDeletion (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate CancelDeletion(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletion(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CancelDeletion (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As Certificate" />
      <MemberSignature Language="F#" Value="static member CancelDeletion : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletion (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-145">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-145">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-146">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-146">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-147">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-147">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-148">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-148">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-149">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-149">For example SHA1-a3d1c5.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-150">指定されたアカウントからの証明書の削除に失敗をキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="c7480-150">Cancels a failed deletion of a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c7480-151">プールで使用されている証明書を削除またはコンピューティング ノードしようとすると、証明書の状態は deleteFailed に変更します。</span><span class="sxs-lookup"><span data-stu-id="c7480-151">If you try to delete a certificate that is being used by a pool or compute node, the status of the certificate changes to deleteFailed.</span></span> <span data-ttu-id="c7480-152">証明書の使用を続行することを決定する場合をアクティブに証明書の状態を設定します。 この操作を使用できます。</span><span class="sxs-lookup"><span data-stu-id="c7480-152">If you decide that you want to continue using the certificate, you can use this operation to set the status of the certificate back to active.</span></span> <span data-ttu-id="c7480-153">証明書を削除する場合は、削除が失敗した後、この操作を実行する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="c7480-153">If you intend to delete the certificate, you do not need to run this operation after the deletion failed.</span></span> <span data-ttu-id="c7480-154">証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-154">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; CancelDeletionAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; CancelDeletionAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletionAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelDeletionAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletionAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;CancelDeletionAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-156">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-156">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-157">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-157">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-158">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-158">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-159">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-159">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-160">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-160">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7480-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7480-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-162">指定されたアカウントからの証明書の削除に失敗をキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="c7480-162">Cancels a failed deletion of a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="c7480-163">プールで使用されている証明書を削除またはコンピューティング ノードしようとすると、証明書の状態は deleteFailed に変更します。</span><span class="sxs-lookup"><span data-stu-id="c7480-163">If you try to delete a certificate that is being used by a pool or compute node, the status of the certificate changes to deleteFailed.</span></span> <span data-ttu-id="c7480-164">証明書の使用を続行することを決定する場合をアクティブに証明書の状態を設定します。 この操作を使用できます。</span><span class="sxs-lookup"><span data-stu-id="c7480-164">If you decide that you want to continue using the certificate, you can use this operation to set the status of the certificate back to active.</span></span> <span data-ttu-id="c7480-165">証明書を削除する場合は、削除が失敗した後、この操作を実行する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="c7480-165">If you intend to delete the certificate, you do not need to run this operation after the deletion failed.</span></span> <span data-ttu-id="c7480-166">証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-166">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate Create (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate Create(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Create(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String, parameters As CertificateCreateOrUpdateParameters, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Certificate" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Create (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-168">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-168">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-169">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-169">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-170">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-170">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-171">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-171">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-172">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-172">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c7480-173">証明書の作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c7480-173">Additional parameters for certificate creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c7480-174">更新する証明書のエンティティの状態 (ETag) のバージョン。</span><span class="sxs-lookup"><span data-stu-id="c7480-174">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="c7480-175">値"\*"を証明書が既に存在する場合にのみ、操作を適用するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="c7480-175">A value of "\*" can be used to apply the operation only if the certificate already exists.</span></span> <span data-ttu-id="c7480-176">省略した場合、この操作常に使用されます。</span><span class="sxs-lookup"><span data-stu-id="c7480-176">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="c7480-177">設定 ' \*'、新しい証明書を作成するが、既存の証明書の更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="c7480-177">Set to '\*' to allow a new certificate to be created, but to prevent updating an existing certificate.</span></span> <span data-ttu-id="c7480-178">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="c7480-178">Other values will be ignored.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-179">指定されたアカウント内の新しい証明書を作成します。</span><span class="sxs-lookup"><span data-stu-id="c7480-179">Creates a new certificate inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; CreateAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; CreateAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-180">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-181">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-181">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-182">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-182">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-183">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-183">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-184">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-184">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-185">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-185">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c7480-186">証明書の作成に追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c7480-186">Additional parameters for certificate creation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c7480-187">更新する証明書のエンティティの状態 (ETag) のバージョン。</span><span class="sxs-lookup"><span data-stu-id="c7480-187">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="c7480-188">値"\*"を証明書が既に存在する場合にのみ、操作を適用するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="c7480-188">A value of "\*" can be used to apply the operation only if the certificate already exists.</span></span> <span data-ttu-id="c7480-189">省略した場合、この操作常に使用されます。</span><span class="sxs-lookup"><span data-stu-id="c7480-189">If omitted, this operation will always be applied.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="c7480-190">設定 ' \*'、新しい証明書を作成するが、既存の証明書の更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="c7480-190">Set to '\*' to allow a new certificate to be created, but to prevent updating an existing certificate.</span></span> <span data-ttu-id="c7480-191">その他の値は無視されます。</span><span class="sxs-lookup"><span data-stu-id="c7480-191">Other values will be ignored.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7480-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7480-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-193">指定されたアカウント内の新しい証明書を作成します。</span><span class="sxs-lookup"><span data-stu-id="c7480-193">Creates a new certificate inside the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders Delete (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders Delete(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Delete(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As CertificateDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Delete (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-195">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-195">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-196">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-196">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-197">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-197">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-198">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-198">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-199">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-199">For example SHA1-a3d1c5.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-200">指定された証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="c7480-200">Deletes the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-202">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-202">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-203">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-203">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-204">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-204">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-205">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-205">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-206">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-206">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7480-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7480-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-208">指定された証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="c7480-208">Deletes the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate Get (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate Get(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Get(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As Certificate" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Get (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-209">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-210">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-210">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-211">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-211">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-212">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-212">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-213">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-213">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-214">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-214">For example SHA1-a3d1c5.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-215">指定された証明書に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c7480-215">Gets information about the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; GetAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; GetAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-216">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-216">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-217">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-217">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-218">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-218">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-219">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-219">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-220">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-220">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-221">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-221">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7480-222">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7480-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-223">指定された証明書に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c7480-223">Gets information about the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccount (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccount(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccount(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBatchAccount (operations As ICertificateOperations, resourceGroupName As String, accountName As String, Optional maxresults As Nullable(Of Integer) = null, Optional select As String = null, Optional filter As String = null) As IPage(Of Certificate)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccount : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * Nullable&lt;int&gt; * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccount (operations, resourceGroupName, accountName, maxresults, select, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-224">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-224">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-225">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-225">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-226">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-226">The name of the Batch account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="c7480-227">応答で返されるアイテムの最大数。</span><span class="sxs-lookup"><span data-stu-id="c7480-227">The maximum number of items to return in the response.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="c7480-228">コンマ区切りのプロパティの一覧を返す必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-228">Comma separated list of properties that should be returned.</span></span> <span data-ttu-id="c7480-229">例:"のプロパティ/provisioningState"です。</span><span class="sxs-lookup"><span data-stu-id="c7480-229">e.g. "properties/provisioningState".</span></span> <span data-ttu-id="c7480-230">のみの上位レベル のプロパティのプロパティ/選択に対して有効です。</span><span class="sxs-lookup"><span data-stu-id="c7480-230">Only top level properties under properties/ are valid for selection.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="c7480-231">OData フィルター式です。</span><span class="sxs-lookup"><span data-stu-id="c7480-231">OData filter expression.</span></span> <span data-ttu-id="c7480-232">フィルター処理の有効なプロパティは"のプロパティ/provisioningState"、"のプロパティ/provisioningStateTransitionTime"、"name"です。</span><span class="sxs-lookup"><span data-stu-id="c7480-232">Valid properties for filtering are "properties/provisioningState", "properties/provisioningStateTransitionTime", "name".</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-233">すべての指定されたアカウントの証明書の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="c7480-233">Lists all of the certificates in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * Nullable&lt;int&gt; * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountAsync (operations, resourceGroupName, accountName, maxresults, select, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;ListByBatchAccountAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-234">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-235">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-235">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-236">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-236">The name of the Batch account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="c7480-237">応答で返されるアイテムの最大数。</span><span class="sxs-lookup"><span data-stu-id="c7480-237">The maximum number of items to return in the response.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="c7480-238">コンマ区切りのプロパティの一覧を返す必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-238">Comma separated list of properties that should be returned.</span></span> <span data-ttu-id="c7480-239">例:"のプロパティ/provisioningState"です。</span><span class="sxs-lookup"><span data-stu-id="c7480-239">e.g. "properties/provisioningState".</span></span> <span data-ttu-id="c7480-240">のみの上位レベル のプロパティのプロパティ/選択に対して有効です。</span><span class="sxs-lookup"><span data-stu-id="c7480-240">Only top level properties under properties/ are valid for selection.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="c7480-241">OData フィルター式です。</span><span class="sxs-lookup"><span data-stu-id="c7480-241">OData filter expression.</span></span> <span data-ttu-id="c7480-242">フィルター処理の有効なプロパティは"のプロパティ/provisioningState"、"のプロパティ/provisioningStateTransitionTime"、"name"です。</span><span class="sxs-lookup"><span data-stu-id="c7480-242">Valid properties for filtering are "properties/provisioningState", "properties/provisioningStateTransitionTime", "name".</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7480-243">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7480-243">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-244">すべての指定されたアカウントの証明書の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="c7480-244">Lists all of the certificates in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccountNext (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccountNext(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNext(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBatchAccountNext (operations As ICertificateOperations, nextPageLink As String) As IPage(Of Certificate)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountNext : Microsoft.Azure.Management.Batch.ICertificateOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-245">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-245">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c7480-246">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c7480-246">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-247">すべての指定されたアカウントの証明書の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="c7480-247">Lists all of the certificates in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountNextAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountNextAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNextAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountNextAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;ListByBatchAccountNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-248">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-248">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c7480-249">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c7480-249">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7480-250">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7480-250">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-251">すべての指定されたアカウントの証明書の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="c7480-251">Lists all of the certificates in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate Update (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate Update(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Update(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String, parameters As CertificateCreateOrUpdateParameters, Optional ifMatch As String = null) As Certificate" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Update (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-252">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-252">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-253">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-253">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-254">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-254">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-255">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-255">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-256">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-256">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-257">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-257">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c7480-258">証明書を更新するエンティティ。</span><span class="sxs-lookup"><span data-stu-id="c7480-258">Certificate entity to update.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c7480-259">更新する証明書のエンティティの状態 (ETag) のバージョン。</span><span class="sxs-lookup"><span data-stu-id="c7480-259">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="c7480-260">この値を省略するかに設定することができます"\*"を無条件で操作を適用します。</span><span class="sxs-lookup"><span data-stu-id="c7480-260">This value can be omitted or set to "\*" to apply the operation unconditionally.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-261">既存の証明書のプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="c7480-261">Updates the properties of an existing certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; UpdateAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; UpdateAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;UpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c7480-262">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="c7480-262">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c7480-263">Batch アカウントが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-263">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="c7480-264">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="c7480-264">The name of the Batch account.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c7480-265">証明書の識別子。</span><span class="sxs-lookup"><span data-stu-id="c7480-265">The identifier for the certificate.</span></span> <span data-ttu-id="c7480-266">これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c7480-266">This must be made up of algorithm and thumbprint separated by a dash, and must match the certificate data in the request.</span></span> <span data-ttu-id="c7480-267">たとえば SHA1 a3d1c5 です。</span><span class="sxs-lookup"><span data-stu-id="c7480-267">For example SHA1-a3d1c5.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c7480-268">証明書を更新するエンティティ。</span><span class="sxs-lookup"><span data-stu-id="c7480-268">Certificate entity to update.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="c7480-269">更新する証明書のエンティティの状態 (ETag) のバージョン。</span><span class="sxs-lookup"><span data-stu-id="c7480-269">The entity state (ETag) version of the certificate to update.</span></span> <span data-ttu-id="c7480-270">この値を省略するかに設定することができます"\*"を無条件で操作を適用します。</span><span class="sxs-lookup"><span data-stu-id="c7480-270">This value can be omitted or set to "\*" to apply the operation unconditionally.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c7480-271">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c7480-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c7480-272">既存の証明書のプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="c7480-272">Updates the properties of an existing certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>