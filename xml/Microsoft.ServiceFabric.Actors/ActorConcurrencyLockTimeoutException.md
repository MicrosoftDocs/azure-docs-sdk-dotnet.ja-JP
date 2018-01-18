<Type Name="ActorConcurrencyLockTimeoutException" FullName="Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException">
  <TypeSignature Language="C#" Value="public sealed class ActorConcurrencyLockTimeoutException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit ActorConcurrencyLockTimeoutException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorConcurrencyLockTimeoutException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type ActorConcurrencyLockTimeoutException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="951b6-101">メソッドをディスパッチする同時実行のロックをランタイムが有効にするを取得できない場合に、アクター ランタイムによってスローされる例外に基づいています。</span><span class="sxs-lookup"><span data-stu-id="951b6-101">Exception thrown by actor runtime when runtime cannot acquire the turn based concurrency lock to dispatch the method.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorConcurrencyLockTimeoutException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="951b6-102"><see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="951b6-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorConcurrencyLockTimeoutException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException : string -&gt; Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" Usage="new Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="951b6-103">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="951b6-103">The error message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="951b6-104">指定したエラー メッセージを使用して、<see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="951b6-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorConcurrencyLockTimeoutException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException : string * Exception -&gt; Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" Usage="new Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="951b6-105">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="951b6-105">The error message that explains the reason for the exception.</span></span></param>
        <param name="inner"><span data-ttu-id="951b6-106">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="951b6-106">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="951b6-107">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="951b6-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>