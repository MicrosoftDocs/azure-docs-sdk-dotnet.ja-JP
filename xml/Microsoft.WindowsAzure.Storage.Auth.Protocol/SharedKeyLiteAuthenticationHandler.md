<Type Name="SharedKeyLiteAuthenticationHandler" FullName="Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler">
  <TypeSignature Language="C#" Value="public sealed class SharedKeyLiteAuthenticationHandler : Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedKeyLiteAuthenticationHandler extends System.Object implements class Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedKeyLiteAuthenticationHandler&#xA;Implements IAuthenticationHandler" />
  <TypeSignature Language="F#" Value="type SharedKeyLiteAuthenticationHandler = class&#xA;    interface IAuthenticationHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Use SharedKeyAuthenticationHandler")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9d559-101">共有キーを使用して HTTP 要求に署名するハンドラーを表します。</span><span class="sxs-lookup"><span data-stu-id="9d559-101">Represents a handler that signs HTTP requests with a shared key.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedKeyLiteAuthenticationHandler (Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer canonicalizer, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials, string resourceAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer canonicalizer, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials, string resourceAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler.#ctor(Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (canonicalizer As ICanonicalizer, credentials As StorageCredentials, resourceAccountName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler : Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials * string -&gt; Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler" Usage="new Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler (canonicalizer, credentials, resourceAccountName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="canonicalizer" Type="Microsoft.WindowsAzure.Storage.Core.Auth.ICanonicalizer" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
        <Parameter Name="resourceAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="canonicalizer"><span data-ttu-id="9d559-102">HTTP 要求データを署名するための適切な標準形式に変換するカノニカライザーです。</span><span class="sxs-lookup"><span data-stu-id="9d559-102">A canonicalizer that converts HTTP request data into a standard form appropriate for signing.</span></span></param>
        <param name="credentials"><span data-ttu-id="9d559-103">A<see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />要求の資格情報を提供するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9d559-103">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object providing credentials for the request.</span></span></param>
        <param name="resourceAccountName"><span data-ttu-id="9d559-104">HTTP 要求にアクセスするストレージ アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="9d559-104">The name of the storage account that the HTTP request will access.</span></span></param>
        <summary>
            <span data-ttu-id="9d559-105"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="9d559-105">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignRequest">
      <MemberSignature Language="C#" Value="public void SignRequest (System.Net.HttpWebRequest request, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SignRequest(class System.Net.HttpWebRequest request, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.Protocol.SharedKeyLiteAuthenticationHandler.SignRequest(System.Net.HttpWebRequest,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SignRequest : System.Net.HttpWebRequest * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SignRequest : System.Net.HttpWebRequest * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="sharedKeyLiteAuthenticationHandler.SignRequest (request, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler.SignRequest(System.Net.HttpWebRequest,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="9d559-106">署名する HTTP 要求。</span><span class="sxs-lookup"><span data-stu-id="9d559-106">The HTTP request to sign.</span></span></param>
        <param name="operationContext"><span data-ttu-id="9d559-107"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="9d559-107">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="9d559-108">共有キーを持つ指定された HTTP 要求に署名します。</span><span class="sxs-lookup"><span data-stu-id="9d559-108">Signs the specified HTTP request with a shared key.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>