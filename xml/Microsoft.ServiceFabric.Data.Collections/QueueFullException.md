<Type Name="QueueFullException" FullName="Microsoft.ServiceFabric.Data.Collections.QueueFullException">
  <TypeSignature Language="C#" Value="public class QueueFullException : System.Fabric.FabricTransientException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QueueFullException extends System.Fabric.FabricTransientException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueFullException&#xA;Inherits FabricTransientException" />
  <TypeSignature Language="F#" Value="type QueueFullException = class&#xA;    inherit FabricTransientException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricTransientException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e1cbc-101">によってスローされた<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />ときのキューの容量に達しています。</span><span class="sxs-lookup"><span data-stu-id="e1cbc-101">Thrown by <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> when the queue capacity has been reached.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="e1cbc-102">再試行が可能です。この例外を発生すると、呼び出し元必要がありますいくつかの待機時間追加エンキュー操作別デキューを発行する前に。</span><span class="sxs-lookup"><span data-stu-id="e1cbc-102">Retriable; when encountering this exception, the caller should wait some time for additional enqueue operations before issuing another dequeue.</span></span>
            </para>
      <para>
            <span data-ttu-id="e1cbc-103">キューの容量は現在実装されていません。</span><span class="sxs-lookup"><span data-stu-id="e1cbc-103">Queue capacity is not currently implemented.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueFullException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.QueueFullException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e1cbc-104">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="e1cbc-104">Initializes a new Instance of the <see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueFullException (string msg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string msg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.QueueFullException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (msg As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Collections.QueueFullException : string -&gt; Microsoft.ServiceFabric.Data.Collections.QueueFullException" Usage="new Microsoft.ServiceFabric.Data.Collections.QueueFullException msg" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="msg" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="msg"><span data-ttu-id="e1cbc-105">エラーを説明するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="e1cbc-105">The message that describes the error.</span></span></param>
        <summary>
            <span data-ttu-id="e1cbc-106">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" />指定したエラー メッセージを使用します。</span><span class="sxs-lookup"><span data-stu-id="e1cbc-106">Initializes a new Instance of the <see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueFullException (string msg, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string msg, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.QueueFullException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (msg As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Collections.QueueFullException : string * Exception -&gt; Microsoft.ServiceFabric.Data.Collections.QueueFullException" Usage="new Microsoft.ServiceFabric.Data.Collections.QueueFullException (msg, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="msg" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="msg"><span data-ttu-id="e1cbc-107">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="e1cbc-107">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="e1cbc-108">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="e1cbc-108">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="e1cbc-109">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e1cbc-109">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>