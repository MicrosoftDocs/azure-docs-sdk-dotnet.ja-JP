<Type Name="IMobileServiceTableOperation" FullName="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation">
  <TypeSignature Language="C#" Value="public interface IMobileServiceTableOperation" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceTableOperation" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceTableOperation" />
  <TypeSignature Language="F#" Value="type IMobileServiceTableOperation = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="65d43-101">リモート テーブルに対するテーブル操作を表すオブジェクト</span><span class="sxs-lookup"><span data-stu-id="65d43-101">An object representing table operation against remote table</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AbortPush">
      <MemberSignature Language="C#" Value="public void AbortPush ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AbortPush() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation.AbortPush" />
      <MemberSignature Language="VB.NET" Value="Public Sub AbortPush ()" />
      <MemberSignature Language="F#" Value="abstract member AbortPush : unit -&gt; unit" Usage="iMobileServiceTableOperation.AbortPush " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="65d43-102">親のプッシュ操作を中止します。</span><span class="sxs-lookup"><span data-stu-id="65d43-102">Abort the parent push operation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt; ExecuteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JObject&gt; ExecuteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation.ExecuteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteAsync () As Task(Of JObject)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : unit -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;" Usage="iMobileServiceTableOperation.ExecuteAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="65d43-103">リモート テーブルに対する操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="65d43-103">Executes the operation against remote table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.Linq.JObject Item { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.Linq.JObject Item" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation.Item" />
      <MemberSignature Language="VB.NET" Value="Public Property Item As JObject" />
      <MemberSignature Language="F#" Value="member this.Item : Newtonsoft.Json.Linq.JObject with get, set" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Linq.JObject</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="65d43-104">操作に関連付けられている項目。</span><span class="sxs-lookup"><span data-stu-id="65d43-104">The item associated with the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As MobileServiceTableOperationKind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="65d43-105">操作の種類</span><span class="sxs-lookup"><span data-stu-id="65d43-105">The kind of operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As MobileServiceTableOperationState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationState" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.MobileServiceTableOperationState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="65d43-106">操作の状態</span><span class="sxs-lookup"><span data-stu-id="65d43-106">The state of the operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Table">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTable Table { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable Table" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation.Table" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Table As IMobileServiceTable" />
      <MemberSignature Language="F#" Value="member this.Table : Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceTableOperation.Table" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTable</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="65d43-107">テーブル操作を実行する対象です。</span><span class="sxs-lookup"><span data-stu-id="65d43-107">The table that the operation will be executed against.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>