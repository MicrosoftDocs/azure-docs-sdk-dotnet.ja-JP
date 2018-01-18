<Type Name="HybridConnectionStream" FullName="Microsoft.Azure.Relay.HybridConnectionStream">
  <TypeSignature Language="C#" Value="public abstract class HybridConnectionStream : System.IO.Stream" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit HybridConnectionStream extends System.IO.Stream" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.HybridConnectionStream" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class HybridConnectionStream&#xA;Inherits Stream" />
  <TypeSignature Language="F#" Value="type HybridConnectionStream = class&#xA;    inherit Stream" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.Stream</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2aafb-101">接続されている HybridConnection を表すストリーム。</span><span class="sxs-lookup"><span data-stu-id="2aafb-101">A Stream representing a connected HybridConnection.</span></span>  <span data-ttu-id="2aafb-102">発生しているその他のストリームの追加すると、この接続の相手側に通知するためのシャット ダウン メソッドのシャット ダウンするように使用します。</span><span class="sxs-lookup"><span data-stu-id="2aafb-102">Use it just like any other Stream with the addition of a Shutdown method for notifying the other side of this connection that shutdown is occurring.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionStream.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionStream/&lt;CloseAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2aafb-103">観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2aafb-103">A cancellation token to observe.</span></span></param>
        <summary>
            <span data-ttu-id="2aafb-104">これを閉じます<see cref="T:Microsoft.Azure.Relay.HybridConnectionStream" />インスタンスを使用して非同期的に、<see cref="T:System.Threading.CancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="2aafb-104">Closes this <see cref="T:Microsoft.Azure.Relay.HybridConnectionStream" /> instance asynchronously using a <see cref="T:System.Threading.CancellationToken" />.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected override void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="override this.Dispose : bool -&gt; unit" Usage="hybridConnectionStream.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"><span data-ttu-id="2aafb-105">マネージ リソースとアンマネージ リソースの両方を解放する場合は true、アンマネージ リソースだけを解放する場合は false。</span><span class="sxs-lookup"><span data-stu-id="2aafb-105">true to release both managed and unmanaged resources; false to release only unmanaged resources.</span></span></param>
        <summary>
            <span data-ttu-id="2aafb-106">これを閉じます<see cref="T:Microsoft.Azure.Relay.HybridConnectionStream" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="2aafb-106">Closes this <see cref="T:Microsoft.Azure.Relay.HybridConnectionStream" /> instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionStream.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2aafb-107">観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2aafb-107">A cancellation token to observe.</span></span></param>
        <summary>
            <span data-ttu-id="2aafb-108">派生クラスでは、このメソッドにクローズ ロジックを実装します。</span><span class="sxs-lookup"><span data-stu-id="2aafb-108">Derived classes implement close logic in this method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShutdownAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task OnShutdownAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnShutdownAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.OnShutdownAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnShutdownAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionStream.OnShutdownAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2aafb-109">観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2aafb-109">A cancellation token to observe.</span></span></param>
        <summary>
            <span data-ttu-id="2aafb-110">派生クラスでは、この方法でシャット ダウン ロジックを実装します。</span><span class="sxs-lookup"><span data-stu-id="2aafb-110">Derived classes implement shutdown logic in this method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Shutdown">
      <MemberSignature Language="C#" Value="public virtual void Shutdown ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Shutdown() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.Shutdown" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Shutdown ()" />
      <MemberSignature Language="F#" Value="abstract member Shutdown : unit -&gt; unit&#xA;override this.Shutdown : unit -&gt; unit" Usage="hybridConnectionStream.Shutdown " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2aafb-111">このを介して送信することをシャット ダウンして正常な終了処理を開始する<see cref="T:Microsoft.Azure.Relay.HybridConnectionStream" />です。</span><span class="sxs-lookup"><span data-stu-id="2aafb-111">Initiates a graceful close process by shutting down sending through this <see cref="T:Microsoft.Azure.Relay.HybridConnectionStream" />.</span></span> <span data-ttu-id="2aafb-112">切断するにはクリーンにおよび非同期的にシャット ダウンを呼び出して、待ってから、読み取り/ReadAsync 0 バイトの読み取り、更新が完了し、最後に呼び出して、Stream.Close() です。</span><span class="sxs-lookup"><span data-stu-id="2aafb-112">To disconnect cleanly and asynchronously, call Shutdown, wait for Read/ReadAsync to complete with a 0 byte read, then finally call Stream.Close();</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShutdownAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ShutdownAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ShutdownAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.ShutdownAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ShutdownAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="hybridConnectionStream.ShutdownAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionStream/&lt;ShutdownAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="2aafb-113">観察するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2aafb-113">A cancellation token to observe.</span></span></param>
        <summary>
            <span data-ttu-id="2aafb-114">このを介して送信することをシャット ダウンして正常な終了処理を開始する<see cref="T:Microsoft.Azure.Relay.HybridConnectionStream" />です。</span><span class="sxs-lookup"><span data-stu-id="2aafb-114">Initiates a graceful close process by shutting down sending through this <see cref="T:Microsoft.Azure.Relay.HybridConnectionStream" />.</span></span> <span data-ttu-id="2aafb-115">切断するにはクリーンにおよび非同期的に呼び出す ShutdownAsync 待ってから、読み取り/ReadAsync 0 バイトの読み取り、更新が完了し、最後に呼び出して、Stream.CloseAsync();</span><span class="sxs-lookup"><span data-stu-id="2aafb-115">To disconnect cleanly and asynchronously, call ShutdownAsync, wait for Read/ReadAsync to complete with a 0 byte read, then finally call Stream.CloseAsync();</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionStream.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="hybridConnectionStream.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2aafb-116">現在のオブジェクトを表す文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="2aafb-116">Returns a string that represents the current object.</span></span>  <span data-ttu-id="2aafb-117">エンド ツー エンドの相関関係の TrackingId が含まれます。</span><span class="sxs-lookup"><span data-stu-id="2aafb-117">Includes a TrackingId for end to end correlation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Relay.WriteMode WriteMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Relay.WriteMode WriteMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionStream.WriteMode" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteMode As WriteMode" />
      <MemberSignature Language="F#" Value="member this.WriteMode : Microsoft.Azure.Relay.WriteMode with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionStream.WriteMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.WriteMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2aafb-118">設定またはこのストリームの WriteMode を取得します。</span><span class="sxs-lookup"><span data-stu-id="2aafb-118">Sets or gets the WriteMode for this stream.</span></span> <span data-ttu-id="2aafb-119">既定値は WriteMode.Binary</span><span class="sxs-lookup"><span data-stu-id="2aafb-119">Default is WriteMode.Binary</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>