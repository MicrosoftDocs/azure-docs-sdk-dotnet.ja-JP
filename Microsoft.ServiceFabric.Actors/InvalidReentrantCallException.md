<Type Name="InvalidReentrantCallException" FullName="Microsoft.ServiceFabric.Actors.InvalidReentrantCallException">
  <TypeSignature Language="C#" Value="public sealed class InvalidReentrantCallException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit InvalidReentrantCallException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class InvalidReentrantCallException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type InvalidReentrantCallException = class&#xA;    inherit FabricException" />
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
            <span data-ttu-id="fc0d7-101">同時に 1 つ以上の再入可能呼び出しチェーンはアクターのアクティブなときに、アクター ランタイムによってこの例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="fc0d7-101">This exception is thrown by actor runtime when more than one reentrant call chain is active for an actor at the same time.</span></span>
            <span data-ttu-id="fc0d7-102"><para>これは、発生場所アクター A が並列で B、C および D のアクターを呼び出すし、B、C および D、再試行を呼び出すシナリオでバックアップできます A、同時に。</para></span><span class="sxs-lookup"><span data-stu-id="fc0d7-102"><para> This can happen in scenario where actor A calls actor B, C and D in parallel and then B, C and D try to call back A at the same time. </para></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InvalidReentrantCallException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fc0d7-103"><see cref="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fc0d7-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InvalidReentrantCallException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.InvalidReentrantCallException : string -&gt; Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" Usage="new Microsoft.ServiceFabric.Actors.InvalidReentrantCallException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="fc0d7-104">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="fc0d7-104">The error message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="fc0d7-105">指定したエラー メッセージを使用して、<see cref="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fc0d7-105">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public InvalidReentrantCallException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.InvalidReentrantCallException : string * Exception -&gt; Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" Usage="new Microsoft.ServiceFabric.Actors.InvalidReentrantCallException (message, inner)" />
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
        <param name="message"><span data-ttu-id="fc0d7-106">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="fc0d7-106">The error message that explains the reason for the exception.</span></span></param>
        <param name="inner"><span data-ttu-id="fc0d7-107">内部例外が指定されていない場合、現在の例外または null 参照の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="fc0d7-107">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="fc0d7-108">指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を使用して、<see cref="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fc0d7-108">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.InvalidReentrantCallException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>