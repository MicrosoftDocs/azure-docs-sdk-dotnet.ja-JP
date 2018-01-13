<Type Name="IDiagnosticSettingsCategoryOperations" FullName="Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsCategoryOperations">
  <TypeSignature Language="C#" Value="public interface IDiagnosticSettingsCategoryOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDiagnosticSettingsCategoryOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsCategoryOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDiagnosticSettingsCategoryOperations" />
  <TypeSignature Language="F#" Value="type IDiagnosticSettingsCategoryOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="346d8-101">DiagnosticSettingsCategoryOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="346d8-101">DiagnosticSettingsCategoryOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource&gt;&gt; GetWithHttpMessagesAsync (string resourceUri, string name, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource&gt;&gt; GetWithHttpMessagesAsync(string resourceUri, string name, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsCategoryOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource&gt;&gt;" Usage="iDiagnosticSettingsCategoryOperations.GetWithHttpMessagesAsync (resourceUri, name, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceUri">
            <span data-ttu-id="346d8-102">リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="346d8-102">The identifier of the resource.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="346d8-103">診断設定の名前。</span><span class="sxs-lookup"><span data-stu-id="346d8-103">The name of the diagnostic setting.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="346d8-104">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="346d8-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="346d8-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="346d8-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="346d8-106">指定されたリソースの診断設定のカテゴリを取得します。</span><span class="sxs-lookup"><span data-stu-id="346d8-106">Gets the diagnostic settings category for the specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="346d8-107">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="346d8-107">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="346d8-108">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="346d8-108">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="346d8-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="346d8-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResourceCollection&gt;&gt; ListWithHttpMessagesAsync (string resourceUri, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResourceCollection&gt;&gt; ListWithHttpMessagesAsync(string resourceUri, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IDiagnosticSettingsCategoryOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResourceCollection&gt;&gt;" Usage="iDiagnosticSettingsCategoryOperations.ListWithHttpMessagesAsync (resourceUri, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsCategoryResourceCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceUri">
            <span data-ttu-id="346d8-110">リソースの識別子。</span><span class="sxs-lookup"><span data-stu-id="346d8-110">The identifier of the resource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="346d8-111">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="346d8-111">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="346d8-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="346d8-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="346d8-113">指定されたリソースの診断設定のカテゴリを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="346d8-113">Lists the diagnostic settings categories for the specified resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="346d8-114">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="346d8-114">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="346d8-115">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="346d8-115">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="346d8-116">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="346d8-116">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>