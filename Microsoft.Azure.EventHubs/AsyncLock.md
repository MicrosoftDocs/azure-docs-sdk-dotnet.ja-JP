<Type Name="AsyncLock" FullName="Microsoft.Azure.EventHubs.AsyncLock">
  <TypeSignature Language="C#" Value="public class AsyncLock : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AsyncLock extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.AsyncLock" />
  <TypeSignature Language="VB.NET" Value="Public Class AsyncLock&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type AsyncLock = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="a19a3-101">Event Hubs の内部処理の非同期セマフォとして使用します。</span><span class="sxs-lookup"><span data-stu-id="a19a3-101">Used as an asynchronous semaphore for internal Event Hubs operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AsyncLock ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.AsyncLock.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a19a3-102">新しい AsyncLock を返します。</span><span class="sxs-lookup"><span data-stu-id="a19a3-102">Returns a new AsyncLock.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.AsyncLock.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="asyncLock.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a19a3-103">終了し、AsyncLock に関連付けられているすべてのリソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="a19a3-103">Closes and releases any resources associated with the AsyncLock.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.AsyncLock.LockRelease&gt; LockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.Azure.EventHubs.AsyncLock/LockRelease&gt; LockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.AsyncLock.LockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function LockAsync () As Task(Of AsyncLock.LockRelease)" />
      <MemberSignature Language="F#" Value="member this.LockAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.AsyncLock.LockRelease&gt;" Usage="asyncLock.LockAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.AsyncLock+LockRelease&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a19a3-104">ロックを設定します。</span><span class="sxs-lookup"><span data-stu-id="a19a3-104">Sets a lock.</span></span>
            </summary>
        <returns><span data-ttu-id="a19a3-105">非同期操作</span><span class="sxs-lookup"><span data-stu-id="a19a3-105">An asynchronous operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.AsyncLock.LockRelease&gt; LockAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.Azure.EventHubs.AsyncLock/LockRelease&gt; LockAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.AsyncLock.LockAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.LockAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.AsyncLock.LockRelease&gt;" Usage="asyncLock.LockAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.AsyncLock+LockRelease&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="a19a3-106"><see cref="T:System.Threading.CancellationToken" />ロック [キャンセル] を使用できます。</span><span class="sxs-lookup"><span data-stu-id="a19a3-106">The <see cref="T:System.Threading.CancellationToken" /> which can be used to cancel the lock</span></span></param>
        <summary>
            <span data-ttu-id="a19a3-107">キャンセルできるロックの設定を使用して、<see cref="T:System.Threading.CancellationToken" />です。</span><span class="sxs-lookup"><span data-stu-id="a19a3-107">Sets a lock, which allows for cancellation, using a <see cref="T:System.Threading.CancellationToken" />.</span></span>
            </summary>
        <returns><span data-ttu-id="a19a3-108">非同期操作</span><span class="sxs-lookup"><span data-stu-id="a19a3-108">An asynchronous operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>