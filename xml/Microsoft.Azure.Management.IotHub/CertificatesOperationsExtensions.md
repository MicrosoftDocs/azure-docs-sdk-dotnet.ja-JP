<Type Name="CertificatesOperationsExtensions" FullName="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificatesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificatesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificatesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificatesOperationsExtensions = class" />
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
            <span data-ttu-id="cbf83-101">CertificatesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="cbf83-101">Extension methods for CertificatesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.CertificateDescription CreateOrUpdate (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.CertificateDescription CreateOrUpdate(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription * string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificateDescription" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, resourceName, certificateName, certificateDescription, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.CertificateDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateDescription" Type="Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf83-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf83-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf83-103">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-103">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf83-104">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-104">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="cbf83-105">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="cbf83-105">The name of the certificate</span></span>
            </param>
        <param name="certificateDescription">
            <span data-ttu-id="cbf83-106">証明書の本文。</span><span class="sxs-lookup"><span data-stu-id="cbf83-106">The certificate body.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cbf83-107">証明書の ETag です。</span><span class="sxs-lookup"><span data-stu-id="cbf83-107">ETag of the Certificate.</span></span> <span data-ttu-id="cbf83-108">新しい証明書を作成するのには指定しません。</span><span class="sxs-lookup"><span data-stu-id="cbf83-108">Do not specify for creating a brand new certificate.</span></span> <span data-ttu-id="cbf83-109">既存の証明書の更新に必要です。</span><span class="sxs-lookup"><span data-stu-id="cbf83-109">Required to update an existing certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf83-110">IoT hub を証明書をアップロードします。</span><span class="sxs-lookup"><span data-stu-id="cbf83-110">Upload the certificate to the IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf83-111">新規に追加するか、既存の証明書を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="cbf83-111">Adds new or replaces existing certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription certificateDescription, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, resourceName, certificateName, certificateDescription, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateDescription" Type="Microsoft.Azure.Management.IotHub.Models.CertificateBodyDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf83-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf83-112">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf83-113">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-113">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf83-114">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-114">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="cbf83-115">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="cbf83-115">The name of the certificate</span></span>
            </param>
        <param name="certificateDescription">
            <span data-ttu-id="cbf83-116">証明書の本文。</span><span class="sxs-lookup"><span data-stu-id="cbf83-116">The certificate body.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cbf83-117">証明書の ETag です。</span><span class="sxs-lookup"><span data-stu-id="cbf83-117">ETag of the Certificate.</span></span> <span data-ttu-id="cbf83-118">新しい証明書を作成するのには指定しません。</span><span class="sxs-lookup"><span data-stu-id="cbf83-118">Do not specify for creating a brand new certificate.</span></span> <span data-ttu-id="cbf83-119">既存の証明書の更新に必要です。</span><span class="sxs-lookup"><span data-stu-id="cbf83-119">Required to update an existing certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf83-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf83-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf83-121">IoT hub を証明書をアップロードします。</span><span class="sxs-lookup"><span data-stu-id="cbf83-121">Upload the certificate to the IoT hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf83-122">新規に追加するか、既存の証明書を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="cbf83-122">Adds new or replaces existing certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.Delete(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ICertificatesOperations, resourceGroupName As String, resourceName As String, certificateName As String, ifMatch As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.Delete (operations, resourceGroupName, resourceName, certificateName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf83-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf83-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf83-124">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-124">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf83-125">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-125">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="cbf83-126">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="cbf83-126">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cbf83-127">証明書の ETag です。</span><span class="sxs-lookup"><span data-stu-id="cbf83-127">ETag of the Certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf83-128">削除、X509 証明書。</span><span class="sxs-lookup"><span data-stu-id="cbf83-128">Delete an X509 certificate.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="cbf83-129">削除、既存 X509 証明書またはが存在しない場合、何も行われません。</span><span class="sxs-lookup"><span data-stu-id="cbf83-129">Deletes an existing X509 certificate or does nothing if it does not exist.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.DeleteAsync (operations, resourceGroupName, resourceName, certificateName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf83-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf83-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf83-131">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-131">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf83-132">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-132">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="cbf83-133">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="cbf83-133">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cbf83-134">証明書の ETag です。</span><span class="sxs-lookup"><span data-stu-id="cbf83-134">ETag of the Certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf83-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf83-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf83-136">削除、X509 証明書。</span><span class="sxs-lookup"><span data-stu-id="cbf83-136">Delete an X509 certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf83-137">削除、既存 X509 証明書またはが存在しない場合、何も行われません。</span><span class="sxs-lookup"><span data-stu-id="cbf83-137">Deletes an existing X509 certificate or does nothing if it does not exist.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateVerificationCode">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription GenerateVerificationCode (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription GenerateVerificationCode(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.GenerateVerificationCode(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateVerificationCode (operations As ICertificatesOperations, resourceGroupName As String, resourceName As String, certificateName As String, ifMatch As String) As CertificateWithNonceDescription" />
      <MemberSignature Language="F#" Value="static member GenerateVerificationCode : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.GenerateVerificationCode (operations, resourceGroupName, resourceName, certificateName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf83-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf83-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf83-139">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-139">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf83-140">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-140">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="cbf83-141">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="cbf83-141">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cbf83-142">証明書の ETag です。</span><span class="sxs-lookup"><span data-stu-id="cbf83-142">ETag of the Certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf83-143">所有しているフローの証拠の確認コードを生成します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-143">Generate verification code for proof of possession flow.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf83-144">所有しているフローの証拠の確認コードを生成します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-144">Generates verification code for proof of possession flow.</span></span> <span data-ttu-id="cbf83-145">検証コードを使用して、リーフ証明書を生成するされます。</span><span class="sxs-lookup"><span data-stu-id="cbf83-145">The verification code will be used to generate a leaf certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateVerificationCodeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt; GenerateVerificationCodeAsync (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt; GenerateVerificationCodeAsync(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.GenerateVerificationCodeAsync(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateVerificationCodeAsync : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.GenerateVerificationCodeAsync (operations, resourceGroupName, resourceName, certificateName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions/&lt;GenerateVerificationCodeAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateWithNonceDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf83-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf83-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf83-147">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-147">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf83-148">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-148">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="cbf83-149">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="cbf83-149">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cbf83-150">証明書の ETag です。</span><span class="sxs-lookup"><span data-stu-id="cbf83-150">ETag of the Certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf83-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf83-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf83-152">所有しているフローの証拠の確認コードを生成します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-152">Generate verification code for proof of possession flow.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf83-153">所有しているフローの証拠の確認コードを生成します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-153">Generates verification code for proof of possession flow.</span></span> <span data-ttu-id="cbf83-154">検証コードを使用して、リーフ証明書を生成するされます。</span><span class="sxs-lookup"><span data-stu-id="cbf83-154">The verification code will be used to generate a leaf certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.CertificateDescription Get (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.CertificateDescription Get(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.Get(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ICertificatesOperations, resourceGroupName As String, resourceName As String, certificateName As String) As CertificateDescription" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificateDescription" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.Get (operations, resourceGroupName, resourceName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.CertificateDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf83-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf83-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf83-156">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-156">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf83-157">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-157">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="cbf83-158">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="cbf83-158">The name of the certificate</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf83-159">証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-159">Get the certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf83-160">証明書を返します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-160">Returns the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt; GetAsync (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt; GetAsync(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.GetAsync(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.GetAsync (operations, resourceGroupName, resourceName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf83-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf83-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf83-162">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-162">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf83-163">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-163">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="cbf83-164">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="cbf83-164">The name of the certificate</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf83-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf83-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf83-166">証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-166">Get the certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf83-167">証明書を返します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-167">Returns the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByIotHub">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.CertificateListDescription ListByIotHub (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.CertificateListDescription ListByIotHub(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.ListByIotHub(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByIotHub (operations As ICertificatesOperations, resourceGroupName As String, resourceName As String) As CertificateListDescription" />
      <MemberSignature Language="F#" Value="static member ListByIotHub : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificateListDescription" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.ListByIotHub (operations, resourceGroupName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.CertificateListDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf83-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf83-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf83-169">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-169">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf83-170">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-170">The name of the IoT hub.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf83-171">証明書の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-171">Get the certificate list.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf83-172">証明書の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-172">Returns the list of certificates.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByIotHubAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt; ListByIotHubAsync (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt; ListByIotHubAsync(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.ListByIotHubAsync(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByIotHubAsync : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.ListByIotHubAsync (operations, resourceGroupName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions/&lt;ListByIotHubAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateListDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf83-173">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf83-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf83-174">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-174">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf83-175">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-175">The name of the IoT hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf83-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf83-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf83-177">証明書の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-177">Get the certificate list.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf83-178">証明書の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-178">Returns the list of certificates.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Verify">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.IotHub.Models.CertificateDescription Verify (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.IotHub.Models.CertificateDescription Verify(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.Verify(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Verify (operations As ICertificatesOperations, resourceGroupName As String, resourceName As String, certificateName As String, certificateVerificationBody As CertificateVerificationDescription, ifMatch As String) As CertificateDescription" />
      <MemberSignature Language="F#" Value="static member Verify : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription * string -&gt; Microsoft.Azure.Management.IotHub.Models.CertificateDescription" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.Verify (operations, resourceGroupName, resourceName, certificateName, certificateVerificationBody, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.CertificateDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVerificationBody" Type="Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf83-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf83-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf83-180">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-180">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf83-181">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-181">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="cbf83-182">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="cbf83-182">The name of the certificate</span></span>
            </param>
        <param name="certificateVerificationBody">
            <span data-ttu-id="cbf83-183">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="cbf83-183">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cbf83-184">証明書の ETag です。</span><span class="sxs-lookup"><span data-stu-id="cbf83-184">ETag of the Certificate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf83-185">証明書の秘密キーを所有していることを確認します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-185">Verify certificate's private key possession.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf83-186">確認のアップロード前証明書によって発行されたリーフ証明書を提供することによって、証明書の秘密キーを所有しているを確認します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-186">Verifies the certificate's private key possession by providing the leaf cert issued by the verifying pre uploaded certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt; VerifyAsync (this Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt; VerifyAsync(class Microsoft.Azure.Management.IotHub.ICertificatesOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription certificateVerificationBody, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.VerifyAsync(Microsoft.Azure.Management.IotHub.ICertificatesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyAsync : Microsoft.Azure.Management.IotHub.ICertificatesOperations * string * string * string * Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;" Usage="Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions.VerifyAsync (operations, resourceGroupName, resourceName, certificateName, certificateVerificationBody, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.IotHub.CertificatesOperationsExtensions/&lt;VerifyAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.IotHub.Models.CertificateDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.IotHub.ICertificatesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVerificationBody" Type="Microsoft.Azure.Management.IotHub.Models.CertificateVerificationDescription" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbf83-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="cbf83-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbf83-188">IoT ハブが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-188">The name of the resource group that contains the IoT hub.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="cbf83-189">IoT hub の名前。</span><span class="sxs-lookup"><span data-stu-id="cbf83-189">The name of the IoT hub.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="cbf83-190">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="cbf83-190">The name of the certificate</span></span>
            </param>
        <param name="certificateVerificationBody">
            <span data-ttu-id="cbf83-191">証明書の名前</span><span class="sxs-lookup"><span data-stu-id="cbf83-191">The name of the certificate</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cbf83-192">証明書の ETag です。</span><span class="sxs-lookup"><span data-stu-id="cbf83-192">ETag of the Certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cbf83-193">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cbf83-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbf83-194">証明書の秘密キーを所有していることを確認します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-194">Verify certificate's private key possession.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="cbf83-195">確認のアップロード前証明書によって発行されたリーフ証明書を提供することによって、証明書の秘密キーを所有しているを確認します。</span><span class="sxs-lookup"><span data-stu-id="cbf83-195">Verifies the certificate's private key possession by providing the leaf cert issued by the verifying pre uploaded certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>