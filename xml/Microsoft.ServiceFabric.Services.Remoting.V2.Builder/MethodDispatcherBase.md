<Type Name="MethodDispatcherBase" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Builder.MethodDispatcherBase">
  <TypeSignature Language="C#" Value="public abstract class MethodDispatcherBase : Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MethodDispatcherBase extends Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Builder.MethodDispatcherBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MethodDispatcherBase&#xA;Inherits MethodDispatcherBase" />
  <TypeSignature Language="F#" Value="type MethodDispatcherBase = class&#xA;    inherit MethodDispatcherBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6ce2f-101">このクラスは、リモート オブジェクトのインターフェイスまたはメソッドに、クライアントからの要求をディスパッチします。</span><span class="sxs-lookup"><span data-stu-id="6ce2f-101">This class dispatches requests from the client to the interface/method of the remoted object.</span></span>
            <span data-ttu-id="6ce2f-102">このクラスは、リモート処理のコード ジェネレーターによって使用されます。</span><span class="sxs-lookup"><span data-stu-id="6ce2f-102">This class is used by remoting code generator.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MethodDispatcherBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Builder.MethodDispatcherBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueWithResult&lt;TRetVal&gt;">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; ContinueWithResult&lt;TRetVal&gt; (string interfaceName, string methodName, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory remotingMessageBodyFactory, System.Threading.Tasks.Task&lt;TRetVal&gt; task);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; ContinueWithResult&lt;TRetVal&gt;(string interfaceName, string methodName, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory remotingMessageBodyFactory, class System.Threading.Tasks.Task`1&lt;!!TRetVal&gt; task) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Builder.MethodDispatcherBase.ContinueWithResult``1(System.String,System.String,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory,System.Threading.Tasks.Task{``0})" />
      <MemberSignature Language="VB.NET" Value="Protected Function ContinueWithResult(Of TRetVal) (interfaceName As String, methodName As String, remotingMessageBodyFactory As IServiceRemotingMessageBodyFactory, task As Task(Of TRetVal)) As Task(Of IServiceRemotingResponseMessageBody)" />
      <MemberSignature Language="F#" Value="member this.ContinueWithResult : string * string * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory * System.Threading.Tasks.Task&lt;'RetVal&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;" Usage="methodDispatcherBase.ContinueWithResult (interfaceName, methodName, remotingMessageBodyFactory, task)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TRetVal" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="interfaceName" Type="System.String" />
        <Parameter Name="methodName" Type="System.String" />
        <Parameter Name="remotingMessageBodyFactory" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" />
        <Parameter Name="task" Type="System.Threading.Tasks.Task&lt;TRetVal&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TRetVal">To be added.</typeparam>
        <param name="interfaceName"></param>
        <param name="methodName"></param>
        <param name="remotingMessageBodyFactory"></param>
        <param name="task"><span data-ttu-id="6ce2f-103">継続タスク</span><span class="sxs-lookup"><span data-stu-id="6ce2f-103">continuation task</span></span></param>
        <summary>
            <span data-ttu-id="6ce2f-104">内部 - サービスのリモート処理で使用されます。</span><span class="sxs-lookup"><span data-stu-id="6ce2f-104">Internal - used by Service remoting</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6ce2f-105">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="6ce2f-105">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateResponseMessageBody">
      <MemberSignature Language="C#" Value="protected Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody CreateResponseMessageBody (string interfaceName, string methodName, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory remotingMessageBodyFactory, object response);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody CreateResponseMessageBody(string interfaceName, string methodName, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory remotingMessageBodyFactory, object response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Builder.MethodDispatcherBase.CreateResponseMessageBody(System.String,System.String,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Function CreateResponseMessageBody (interfaceName As String, methodName As String, remotingMessageBodyFactory As IServiceRemotingMessageBodyFactory, response As Object) As IServiceRemotingResponseMessageBody" />
      <MemberSignature Language="F#" Value="member this.CreateResponseMessageBody : string * string * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory * obj -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody" Usage="methodDispatcherBase.CreateResponseMessageBody (interfaceName, methodName, remotingMessageBodyFactory, response)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceName" Type="System.String" />
        <Parameter Name="methodName" Type="System.String" />
        <Parameter Name="remotingMessageBodyFactory" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" />
        <Parameter Name="response" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="interfaceName"></param>
        <param name="methodName"></param>
        <param name="remotingMessageBodyFactory"></param>
        <param name="response"></param>
        <summary>
            <span data-ttu-id="6ce2f-106">このメソッドは使用 ti は、指定された戻り値のリモート処理の応答を作成します。</span><span class="sxs-lookup"><span data-stu-id="6ce2f-106">This method is used ti create the remoting response from the specified return value</span></span> 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispatch">
      <MemberSignature Language="C#" Value="public void Dispatch (object objectImplementation, int methodId, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestMessageBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Dispatch(object objectImplementation, int32 methodId, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestMessageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Builder.MethodDispatcherBase.Dispatch(System.Object,System.Int32,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispatch (objectImplementation As Object, methodId As Integer, requestMessageBody As IServiceRemotingRequestMessageBody)" />
      <MemberSignature Language="F#" Value="override this.Dispatch : obj * int * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody -&gt; unit" Usage="methodDispatcherBase.Dispatch (objectImplementation, methodId, requestMessageBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectImplementation" Type="System.Object" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestMessageBody" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
      </Parameters>
      <Docs>
        <param name="objectImplementation"></param>
        <param name="methodId"></param>
        <param name="requestMessageBody"></param>
        <summary>
            <span data-ttu-id="6ce2f-107">このメソッドは、リモート オブジェクトによって実装されるインターフェイスの指定したメソッド Id に一方向のメッセージのディスパッチに使用します。</span><span class="sxs-lookup"><span data-stu-id="6ce2f-107">This method is used to dispatch one way messages to the specified methodId of the interface implemented by the remoted object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispatch">
      <MemberSignature Language="C#" Value="public override void Dispatch (object objectImplementation, int methodId, object messageBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Dispatch(object objectImplementation, int32 methodId, object messageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Builder.MethodDispatcherBase.Dispatch(System.Object,System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Dispatch (objectImplementation As Object, methodId As Integer, messageBody As Object)" />
      <MemberSignature Language="F#" Value="override this.Dispatch : obj * int * obj -&gt; unit" Usage="methodDispatcherBase.Dispatch (objectImplementation, methodId, messageBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectImplementation" Type="System.Object" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="messageBody" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="objectImplementation">To be added.</param>
        <param name="methodId">To be added.</param>
        <param name="messageBody">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="DispatchAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;object&gt; DispatchAsync (object objectImplementation, int methodId, object requestBody, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;object&gt; DispatchAsync(object objectImplementation, int32 methodId, object requestBody, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Builder.MethodDispatcherBase.DispatchAsync(System.Object,System.Int32,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.DispatchAsync : obj * int * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="methodDispatcherBase.DispatchAsync (objectImplementation, methodId, requestBody, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectImplementation" Type="System.Object" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestBody" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="objectImplementation">To be added.</param>
        <param name="methodId">To be added.</param>
        <param name="requestBody">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="DispatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; DispatchAsync (object objectImplementation, int methodId, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestBody, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory remotingMessageBodyFactory, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; DispatchAsync(object objectImplementation, int32 methodId, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestBody, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory remotingMessageBodyFactory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Builder.MethodDispatcherBase.DispatchAsync(System.Object,System.Int32,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.DispatchAsync : obj * int * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;" Usage="methodDispatcherBase.DispatchAsync (objectImplementation, methodId, requestBody, remotingMessageBodyFactory, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectImplementation" Type="System.Object" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestBody" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
        <Parameter Name="remotingMessageBodyFactory" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="objectImplementation"></param>
        <param name="methodId"></param>
        <param name="requestBody"></param>
        <param name="remotingMessageBodyFactory"></param>
        <param name="cancellationToken"></param>
        <summary>
            <span data-ttu-id="6ce2f-108">このメソッドは、リモート オブジェクトによって実装されるインターフェイスの指定したメソッド Id への要求のディスパッチに使用されます。</span><span class="sxs-lookup"><span data-stu-id="6ce2f-108">This method is used to dispatch request to the specified methodId of the interface implemented by the remoted object.</span></span>
             </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispatch">
      <MemberSignature Language="C#" Value="protected abstract void OnDispatch (int methodId, object remotedObject, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDispatch(int32 methodId, object remotedObject, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Builder.MethodDispatcherBase.OnDispatch(System.Int32,System.Object,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnDispatch (methodId As Integer, remotedObject As Object, requestBody As IServiceRemotingRequestMessageBody)" />
      <MemberSignature Language="F#" Value="abstract member OnDispatch : int * obj * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody -&gt; unit" Usage="methodDispatcherBase.OnDispatch (methodId, remotedObject, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="remotedObject" Type="System.Object" />
        <Parameter Name="requestBody" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
      </Parameters>
      <Docs>
        <param name="methodId"></param>
        <param name="remotedObject"></param>
        <param name="requestBody"></param>
        <summary>
            <span data-ttu-id="6ce2f-109">このメソッドは、リモート オブジェクトによって実装されるインターフェイスの指定したメソッド Id に一方向のメッセージをディスパッチする生成されたメソッドのディスパッチャーによって実装されます。</span><span class="sxs-lookup"><span data-stu-id="6ce2f-109">This method is implemented by the generated method dispatcher to dispatch one way messages to the specified methodId of the interface implemented by the remoted object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispatchAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; OnDispatchAsync (int methodId, object remotedObject, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestBody, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory remotingMessageBodyFactory, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; OnDispatchAsync(int32 methodId, object remotedObject, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestBody, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory remotingMessageBodyFactory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Builder.MethodDispatcherBase.OnDispatchAsync(System.Int32,System.Object,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDispatchAsync : int * obj * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;" Usage="methodDispatcherBase.OnDispatchAsync (methodId, remotedObject, requestBody, remotingMessageBodyFactory, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="remotedObject" Type="System.Object" />
        <Parameter Name="requestBody" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
        <Parameter Name="remotingMessageBodyFactory" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingMessageBodyFactory" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="methodId">To be added.</param>
        <param name="remotedObject">To be added.</param>
        <param name="requestBody">To be added.</param>
        <param name="remotingMessageBodyFactory">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="6ce2f-110">このメソッドは、リモート オブジェクトによって実装されるインターフェイスの指定したメソッド Id への要求のディスパッチに生成されたメソッドのディスパッチャーによって実装されます。</span><span class="sxs-lookup"><span data-stu-id="6ce2f-110">This method is implemented by the generated method dispatcher to dispatch request to the specified methodId of the interface implemented by the remoted object.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>