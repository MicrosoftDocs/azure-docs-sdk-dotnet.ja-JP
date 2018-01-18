<Type Name="BufferPoolManager" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager">
  <TypeSignature Language="C#" Value="public sealed class BufferPoolManager : Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BufferPoolManager extends System.Object implements class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BufferPoolManager&#xA;Implements IBufferPoolManager" />
  <TypeSignature Language="F#" Value="type BufferPoolManager = class&#xA;    interface IBufferPoolManager" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="b3265-101">バッファー プールの管理には、BufferManager クラスを使用できます。</span><span class="sxs-lookup"><span data-stu-id="b3265-101">You can use the BufferManager class to manage a buffer pool.</span></span> <span data-ttu-id="b3265-102">このクラスをインスタンス化するときは、プールが作成されます。</span><span class="sxs-lookup"><span data-stu-id="b3265-102">The pool is created when you instantiate this class .</span></span> <span data-ttu-id="b3265-103">プールで使用されていないバッファーがない場合に、バッファーがインスタンス化されます。</span><span class="sxs-lookup"><span data-stu-id="b3265-103">Buffer is instantiated when there are no unused buffers in the pool.</span></span>
            <span data-ttu-id="b3265-104">バッファー プールがガベージ コレクションによって回収されるときに破棄されます。</span><span class="sxs-lookup"><span data-stu-id="b3265-104">Destroyed when the buffer pool is reclaimed by garbage collection.</span></span> <span data-ttu-id="b3265-105">バッファーを使用する必要があるときはいつでも、バッファーをプールから取得して使用し、終わったらプールに戻します。</span><span class="sxs-lookup"><span data-stu-id="b3265-105">Every time you need to use a buffer, you take one from the pool, use it, and return it to the pool when done.</span></span> <span data-ttu-id="b3265-106">バッファーを使用する必要があるたびにバッファーを作成して破棄するよりも、このプロセスの方がはるかに高速です。</span><span class="sxs-lookup"><span data-stu-id="b3265-106">This process is much faster than creating and destroying a buffer every time you need to use one.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BufferPoolManager (int segmentSize = 4096, int bufferLimit = 100);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 segmentSize, int32 bufferLimit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager.#ctor(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional segmentSize As Integer = 4096, Optional bufferLimit As Integer = 100)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager : int * int -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager" Usage="new Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager (segmentSize, bufferLimit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="segmentSize" Type="System.Int32" />
        <Parameter Name="bufferLimit" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="segmentSize"></param>
        <param name="bufferLimit"></param>
        <summary>
            <span data-ttu-id="b3265-107">BufferPoolManager クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b3265-107">Initializes a new instance of the BufferPoolManager class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnBuffer">
      <MemberSignature Language="C#" Value="public bool ReturnBuffer (Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer buffer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ReturnBuffer(class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer buffer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager.ReturnBuffer(Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReturnBuffer (buffer As IPooledBuffer) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member ReturnBuffer : Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer -&gt; bool&#xA;override this.ReturnBuffer : Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer -&gt; bool" Usage="bufferPoolManager.ReturnBuffer buffer" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager.ReturnBuffer(Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="buffer" Type="Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer" />
      </Parameters>
      <Docs>
        <param name="buffer"></param>
        <summary>
            <span data-ttu-id="b3265-108">バッファーをプールに返します。</span><span class="sxs-lookup"><span data-stu-id="b3265-108">Returns a buffer to the pool.</span></span>
            <span data-ttu-id="b3265-109">制限を越えている場合、バッファーはプールに返さはありません。</span><span class="sxs-lookup"><span data-stu-id="b3265-109">if limit crosses, buffer won't be returned to the Pool.</span></span>
            <span data-ttu-id="b3265-110">これは、バッファーが返されない場合は、false を返します。</span><span class="sxs-lookup"><span data-stu-id="b3265-110">It return false , if buffer is not returned.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TakeBuffer">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer TakeBuffer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer TakeBuffer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.BufferPoolManager.TakeBuffer" />
      <MemberSignature Language="VB.NET" Value="Public Function TakeBuffer () As IPooledBuffer" />
      <MemberSignature Language="F#" Value="abstract member TakeBuffer : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer&#xA;override this.TakeBuffer : unit -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer" Usage="bufferPoolManager.TakeBuffer " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IBufferPoolManager.TakeBuffer</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.Messaging.IPooledBuffer</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b3265-111">バッファーをプールから取得します。</span><span class="sxs-lookup"><span data-stu-id="b3265-111">Gets a buffer from the pool.</span></span>
            <span data-ttu-id="b3265-112">すべての未使用のバッファーが見つからない場合は、新しいバッファーがインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="b3265-112">if it doesn't find any unused buffer , it instantiate new buffer.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>