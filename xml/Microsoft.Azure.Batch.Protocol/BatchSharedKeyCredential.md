<Type Name="BatchSharedKeyCredential" FullName="Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential">
  <TypeSignature Language="C#" Value="public class BatchSharedKeyCredential : Microsoft.Rest.ServiceClientCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchSharedKeyCredential extends Microsoft.Rest.ServiceClientCredentials" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchSharedKeyCredential&#xA;Inherits ServiceClientCredentials" />
  <TypeSignature Language="F#" Value="type BatchSharedKeyCredential = class&#xA;    inherit ServiceClientCredentials" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClientCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5a7fa-101">Azure Batch アカウントのキーの資格情報を共有します。</span><span class="sxs-lookup"><span data-stu-id="5a7fa-101">Shared key credentials for an Azure Batch account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchSharedKeyCredential (string accountName, string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential : string * string -&gt; Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential" Usage="new Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential (accountName, keyValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName"><span data-ttu-id="5a7fa-102">Batch アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5a7fa-102">The name of the Batch account.</span></span></param>
        <param name="keyValue"><span data-ttu-id="5a7fa-103">Base64 でエンコードされた文字列として、Batch アカウントのアクセス キー。</span><span class="sxs-lookup"><span data-stu-id="5a7fa-103">The access key of the Batch account, as a Base64-encoded string.</span></span></param>
        <summary>
            <span data-ttu-id="5a7fa-104"><see cref="T:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5a7fa-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.AccountName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a7fa-105">Batch アカウント名を取得します。</span><span class="sxs-lookup"><span data-stu-id="5a7fa-105">Gets the Batch account name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyValue">
      <MemberSignature Language="C#" Value="public string KeyValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.KeyValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyValue As String" />
      <MemberSignature Language="F#" Value="member this.KeyValue : string" Usage="Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.KeyValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5a7fa-106">Base64 でエンコードされた文字列として、アカウント アクセス キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="5a7fa-106">Gets the account access key, as a Base64-encoded string.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessHttpRequestAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task ProcessHttpRequestAsync (System.Net.Http.HttpRequestMessage httpRequest, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task ProcessHttpRequestAsync(class System.Net.Http.HttpRequestMessage httpRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.ProcessHttpRequestAsync(System.Net.Http.HttpRequestMessage,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ProcessHttpRequestAsync : System.Net.Http.HttpRequestMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="batchSharedKeyCredential.ProcessHttpRequestAsync (httpRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpRequest" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="httpRequest"><span data-ttu-id="5a7fa-107">HTTP 要求</span><span class="sxs-lookup"><span data-stu-id="5a7fa-107">The HTTP request</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5a7fa-108">A<see cref="T:System.Threading.CancellationToken" />要求します。</span><span class="sxs-lookup"><span data-stu-id="5a7fa-108">A <see cref="T:System.Threading.CancellationToken" /> for the request.</span></span></param>
        <summary>
            <span data-ttu-id="5a7fa-109">現在の資格情報を持つ記号、HTTP 要求。</span><span class="sxs-lookup"><span data-stu-id="5a7fa-109">Signs a HTTP request with the current credentials.</span></span>
            </summary>
        <returns><span data-ttu-id="5a7fa-110">A<see cref="T:System.Threading.Tasks.Task" />非同期署名操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="5a7fa-110">A <see cref="T:System.Threading.Tasks.Task" /> representing the asynchronous signing operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>