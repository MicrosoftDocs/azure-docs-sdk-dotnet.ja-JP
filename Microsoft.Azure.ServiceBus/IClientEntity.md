<Type Name="IClientEntity" FullName="Microsoft.Azure.ServiceBus.IClientEntity">
  <TypeSignature Language="C#" Value="public interface IClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="VB.NET" Value="Public Interface IClientEntity" />
  <TypeSignature Language="F#" Value="type IClientEntity = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b4db1-101">すべての Service Bus クライアント間で共通の機能を示すインターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="b4db1-101">An interface showing the common functionality between all Service Bus clients.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IClientEntity.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.Azure.ServiceBus.IClientEntity.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4db1-102">このクライアントを識別する ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="b4db1-102">Gets the ID to identify this client.</span></span> <span data-ttu-id="b4db1-103">これは、ログと例外を関連付けるために使用できます。</span><span class="sxs-lookup"><span data-stu-id="b4db1-103">This can be used to correlate logs and exceptions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks><span data-ttu-id="b4db1-104">新しいクライアントごとに一意の ID (プロセス) です。</span><span class="sxs-lookup"><span data-stu-id="b4db1-104">Every new client has a unique ID (in that process).</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IClientEntity.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iClientEntity.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b4db1-105">クライアントを閉じます。</span><span class="sxs-lookup"><span data-stu-id="b4db1-105">Closes the Client.</span></span> <span data-ttu-id="b4db1-106">これによって開かれた接続を閉じます。</span><span class="sxs-lookup"><span data-stu-id="b4db1-106">Closes the connections opened by it.</span></span>
            </summary>
        <returns><span data-ttu-id="b4db1-107">非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="b4db1-107">The asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsClosedOrClosing">
      <MemberSignature Language="C#" Value="public bool IsClosedOrClosing { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsClosedOrClosing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IClientEntity.IsClosedOrClosing" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsClosedOrClosing As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsClosedOrClosing : bool" Usage="Microsoft.Azure.ServiceBus.IClientEntity.IsClosedOrClosing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4db1-108">クライアントが閉じている場合は true または終了を返します。</span><span class="sxs-lookup"><span data-stu-id="b4db1-108">Returns true if the client is closed or closing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IClientEntity.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.IClientEntity.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4db1-109">個々 の操作がタイムアウトする期間です。</span><span class="sxs-lookup"><span data-stu-id="b4db1-109">Duration after which individual operations will timeout.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IClientEntity.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.IClientEntity.RegisteredPlugins" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b4db1-110">このクライアントの現在登録されているプラグインの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b4db1-110">Gets a list of currently registered plugins for this client.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IClientEntity.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="abstract member RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="iClientEntity.RegisterPlugin serviceBusPlugin" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceBusPlugin" Type="Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />
      </Parameters>
      <Docs>
        <param name="serviceBusPlugin"><span data-ttu-id="b4db1-111">登録する <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />。</span><span class="sxs-lookup"><span data-stu-id="b4db1-111">The <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to register.</span></span></param>
        <summary>
            <span data-ttu-id="b4db1-112">登録、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />このクライアントで使用します。</span><span class="sxs-lookup"><span data-stu-id="b4db1-112">Registers a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to be used with this client.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IClientEntity.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="abstract member UnregisterPlugin : string -&gt; unit" Usage="iClientEntity.UnregisterPlugin serviceBusPluginName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceBusPluginName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceBusPluginName"><span data-ttu-id="b4db1-113">名前<see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" />登録解除する</span><span class="sxs-lookup"><span data-stu-id="b4db1-113">The name <see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" /> to be unregistered</span></span></param>
        <summary>
            <span data-ttu-id="b4db1-114">登録を解除、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />です。</span><span class="sxs-lookup"><span data-stu-id="b4db1-114">Unregisters a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>