<Type Name="IAlertRuleIncidentsOperations" FullName="Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations">
  <TypeSignature Language="C#" Value="public interface IAlertRuleIncidentsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAlertRuleIncidentsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAlertRuleIncidentsOperations" />
  <TypeSignature Language="F#" Value="type IAlertRuleIncidentsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="83212-101">AlertRuleIncidentsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="83212-101">AlertRuleIncidentsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string ruleName, string incidentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string ruleName, string incidentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;&gt;" Usage="iAlertRuleIncidentsOperations.GetWithHttpMessagesAsync (resourceGroupName, ruleName, incidentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="incidentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="83212-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="83212-102">The name of the resource group.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="83212-103">ルールの名前。</span><span class="sxs-lookup"><span data-stu-id="83212-103">The name of the rule.</span></span>
            </param>
        <param name="incidentName">
            <span data-ttu-id="83212-104">取得するためにインシデントの名前。</span><span class="sxs-lookup"><span data-stu-id="83212-104">The name of the incident to retrieve.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="83212-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="83212-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="83212-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="83212-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="83212-107">アラート ルールに関連付けられているインシデントを取得します。</span><span class="sxs-lookup"><span data-stu-id="83212-107">Gets an incident associated to an alert rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="83212-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83212-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="83212-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83212-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="83212-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83212-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByAlertRuleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;&gt;&gt; ListByAlertRuleWithHttpMessagesAsync (string resourceGroupName, string ruleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;&gt;&gt; ListByAlertRuleWithHttpMessagesAsync(string resourceGroupName, string ruleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.IAlertRuleIncidentsOperations.ListByAlertRuleWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByAlertRuleWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;&gt;&gt;" Usage="iAlertRuleIncidentsOperations.ListByAlertRuleWithHttpMessagesAsync (resourceGroupName, ruleName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.Incident&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="83212-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="83212-111">The name of the resource group.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="83212-112">ルールの名前。</span><span class="sxs-lookup"><span data-stu-id="83212-112">The name of the rule.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="83212-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="83212-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="83212-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="83212-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="83212-115">アラート ルールに関連付けられているインシデントの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="83212-115">Gets a list of incidents associated to an alert rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="83212-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83212-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="83212-117">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83212-117">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="83212-118">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83212-118">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>