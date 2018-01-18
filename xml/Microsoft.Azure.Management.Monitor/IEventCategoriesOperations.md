<Type Name="IEventCategoriesOperations" FullName="Microsoft.Azure.Management.Monitor.IEventCategoriesOperations">
  <TypeSignature Language="C#" Value="public interface IEventCategoriesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEventCategoriesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.IEventCategoriesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEventCategoriesOperations" />
  <TypeSignature Language="F#" Value="type IEventCategoriesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7c6f5-101">EventCategoriesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="7c6f5-101">EventCategoriesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.IEventCategoriesOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt;&gt;&gt;" Usage="iEventCategoriesOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.LocalizableString&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="7c6f5-102">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7c6f5-102">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c6f5-103">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c6f5-103">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c6f5-104">アクティビティ ログ サービスでサポートされている使用可能なイベント カテゴリの一覧を取得します。&lt;br&gt;現在のリストには、次が含まれています: 管理ユーザー、セキュリティ、ServiceHealth、アラート、推奨設定、ポリシー。</span><span class="sxs-lookup"><span data-stu-id="7c6f5-104">Get the list of available event categories supported in the Activity Logs Service.&lt;br&gt;The current list includes the following: Administrative, Security, ServiceHealth, Alert, Recommendation, Policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Models.ErrorResponseException">
            <span data-ttu-id="7c6f5-105">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c6f5-105">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7c6f5-106">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c6f5-106">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7c6f5-107">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7c6f5-107">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>