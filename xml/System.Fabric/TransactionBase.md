<Type Name="TransactionBase" FullName="System.Fabric.TransactionBase">
  <TypeSignature Language="C#" Value="public abstract class TransactionBase : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TransactionBase extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.TransactionBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TransactionBase&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type TransactionBase = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <para><span data-ttu-id="b0f9f-101">トランザクションの抽象基本クラスを提供します。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-101">Provides an abstract base class for a transaction.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionBase.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="transactionBase.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b0f9f-102">解放、リリース、またはアンマネージ リソースのリセットに関連付けられているアプリケーション定義のタスクを実行します。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-102">Performs application-defined tasks that are associated with freeing, releasing, or resetting unmanaged resources.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~TransactionBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionBase.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="transactionBase.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b0f9f-103">リソースを解放し、それがガベージ コレクションによって回収される前に、他のクリーンアップ操作を実行しようとするオブジェクトを有効にします。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-103">Enables an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Guid Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid Id" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.TransactionBase.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As Guid" />
      <MemberSignature Language="F#" Value="member this.Id : Guid" Usage="System.Fabric.TransactionBase.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b0f9f-104">トランザクションの ID を取得、<see cref="T:System.Guid" />です。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-104">Gets the ID of the transaction as a <see cref="T:System.Guid" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b0f9f-105">トランザクション ID として、<see cref="T:System.Guid" />です。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-105">The transaction ID as a <see cref="T:System.Guid" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDisposed">
      <MemberSignature Language="C#" Value="protected bool IsDisposed ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance bool IsDisposed() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionBase.IsDisposed" />
      <MemberSignature Language="VB.NET" Value="Protected Function IsDisposed () As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDisposed : unit -&gt; bool" Usage="transactionBase.IsDisposed " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b0f9f-106">オブジェクトが破棄されているかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-106">Gets a value that indicates whether the object has been disposed.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="b0f9f-107">返します<languageKeyword>true</languageKeyword>オブジェクトは破棄されている場合を返しますそれ以外の場合、 <languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-107">Returns <languageKeyword>true</languageKeyword> if the object has been disposed; otherwise, returns <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsolationLevel">
      <MemberSignature Language="C#" Value="public System.Fabric.TransactionIsolationLevel IsolationLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.TransactionIsolationLevel IsolationLevel" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.TransactionBase.IsolationLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsolationLevel As TransactionIsolationLevel" />
      <MemberSignature Language="F#" Value="member this.IsolationLevel : System.Fabric.TransactionIsolationLevel" Usage="System.Fabric.TransactionBase.IsolationLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TransactionIsolationLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b0f9f-108">トランザクションの分離レベルを取得、<see cref="T:System.Fabric.TransactionIsolationLevel" />です。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-108">Gets the isolation level of the transaction as a <see cref="T:System.Fabric.TransactionIsolationLevel" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b0f9f-109">A<see cref="T:System.Fabric.TransactionIsolationLevel" />トランザクションの分離レベルを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-109">A <see cref="T:System.Fabric.TransactionIsolationLevel" /> object that represents the isolation level of the transaction.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b0f9f-110">トランザクションの分離レベルでは、他のトランザクションが、トランザクションが完了する前に揮発性のデータへのアクセス レベルを決定します。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-110">The isolation level of a transaction determines what level of access to volatile data other transactions have before a transaction finishes.</span></span> <span data-ttu-id="b0f9f-111">分離レベルの詳細については、のドキュメントを参照して、<see cref="T:System.Fabric.TransactionIsolationLevel" />列挙します。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-111">For more information about isolation levels, see the documentation for the <see cref="T:System.Fabric.TransactionIsolationLevel" /> enumeration.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispose">
      <MemberSignature Language="C#" Value="protected internal virtual void OnDispose ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig newslot virtual instance void OnDispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.TransactionBase.OnDispose" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Sub OnDispose ()" />
      <MemberSignature Language="F#" Value="abstract member OnDispose : unit -&gt; unit&#xA;override this.OnDispose : unit -&gt; unit" Usage="transactionBase.OnDispose " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b0f9f-112">Dispose イベントからのトランザクションが破棄されるときに発生、 <languageKeyword>OnDispose</languageKeyword>メソッドです。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-112">The dispose event occurs when the transaction is disposed of through the <languageKeyword>OnDispose</languageKeyword> method.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="b0f9f-113">オーバーライドする場合<see cref="M:System.Fabric.Transaction.OnDispose" />、必ず、 <languageKeyword>OnDispose</languageKeyword>の基本クラスのメソッドです。</span><span class="sxs-lookup"><span data-stu-id="b0f9f-113">When overriding <see cref="M:System.Fabric.Transaction.OnDispose" />, be sure to call the <languageKeyword>OnDispose</languageKeyword> method on the base class.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>