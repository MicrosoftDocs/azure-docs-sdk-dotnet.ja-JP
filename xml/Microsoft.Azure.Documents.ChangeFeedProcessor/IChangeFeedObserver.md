<Type Name="IChangeFeedObserver" FullName="Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver">
  <TypeSignature Language="C#" Value="public interface IChangeFeedObserver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IChangeFeedObserver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IChangeFeedObserver" />
  <TypeSignature Language="F#" Value="type IChangeFeedObserver = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.17.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dd79d-101">このインターフェイスを使用すると、フィードのオブザーバーを文書化する変更イベントを提供します。</span><span class="sxs-lookup"><span data-stu-id="dd79d-101">This interface is used to deliver change events to document feed observers.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext context, Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason reason);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(class Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext context, valuetype Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason reason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver.CloseAsync(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext,Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason)" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync (context As ChangeFeedObserverContext, reason As ChangeFeedObserverCloseReason) As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext * Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason -&gt; System.Threading.Tasks.Task" Usage="iChangeFeedObserver.CloseAsync (context, reason)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext" />
        <Parameter Name="reason" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverCloseReason" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="dd79d-102">このオブザーバーなどのパーティションを指定するコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="dd79d-102">The context specifying partition for this observer, etc.</span></span></param>
        <param name="reason"><span data-ttu-id="dd79d-103">理由、オブザーバーが閉じているを指定します。</span><span class="sxs-lookup"><span data-stu-id="dd79d-103">Specifies the reason the observer is closed.</span></span></param>
        <summary>
            <span data-ttu-id="dd79d-104">これは、変更のフィード オブザーバーが閉じられたときに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="dd79d-104">This is called when change feed observer is closed.</span></span>
            </summary>
        <returns><span data-ttu-id="dd79d-105">非同期実行を許可するタスク。</span><span class="sxs-lookup"><span data-stu-id="dd79d-105">A Task to allow asynchronous execution.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task OpenAsync (Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync(class Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver.OpenAsync(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext)" />
      <MemberSignature Language="VB.NET" Value="Public Function OpenAsync (context As ChangeFeedObserverContext) As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext -&gt; System.Threading.Tasks.Task" Usage="iChangeFeedObserver.OpenAsync context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="dd79d-106">このオブザーバーなどのパーティションを指定するコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="dd79d-106">The context specifying partition for this observer, etc.</span></span></param>
        <summary>
            <span data-ttu-id="dd79d-107">これは、変更のフィードのオブザーバーを開いたときに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="dd79d-107">This is called when change feed observer is opened.</span></span>
            </summary>
        <returns><span data-ttu-id="dd79d-108">非同期実行を許可するタスク。</span><span class="sxs-lookup"><span data-stu-id="dd79d-108">A Task to allow asynchronous execution.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessChangesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProcessChangesAsync (Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext context, System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Documents.Document&gt; docs);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ProcessChangesAsync(class Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext context, class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Documents.Document&gt; docs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.IChangeFeedObserver.ProcessChangesAsync(Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext,System.Collections.Generic.IReadOnlyList{Microsoft.Azure.Documents.Document})" />
      <MemberSignature Language="VB.NET" Value="Public Function ProcessChangesAsync (context As ChangeFeedObserverContext, docs As IReadOnlyList(Of Document)) As Task" />
      <MemberSignature Language="F#" Value="abstract member ProcessChangesAsync : Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext * System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Documents.Document&gt; -&gt; System.Threading.Tasks.Task" Usage="iChangeFeedObserver.ProcessChangesAsync (context, docs)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedObserverContext" />
        <Parameter Name="docs" Type="System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Documents.Document&gt;" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="dd79d-109">この変更イベントなどのパーティションを指定するコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="dd79d-109">The context specifying partition for this change event, etc.</span></span></param>
        <param name="docs"><span data-ttu-id="dd79d-110">ドキュメントが変更されました。</span><span class="sxs-lookup"><span data-stu-id="dd79d-110">The documents changed.</span></span></param>
        <summary>
            <span data-ttu-id="dd79d-111">これは、ドキュメントの変更が変更フィードで利用できる場合に呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="dd79d-111">This is called when document changes are available on change feed.</span></span>
            </summary>
        <returns><span data-ttu-id="dd79d-112">非同期実行を許可するタスク。</span><span class="sxs-lookup"><span data-stu-id="dd79d-112">A Task to allow asynchronous execution.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>