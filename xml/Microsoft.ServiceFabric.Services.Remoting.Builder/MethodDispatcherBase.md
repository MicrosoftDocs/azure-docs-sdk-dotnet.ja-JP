<Type Name="MethodDispatcherBase" FullName="Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase">
  <TypeSignature Language="C#" Value="public abstract class MethodDispatcherBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MethodDispatcherBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MethodDispatcherBase" />
  <TypeSignature Language="F#" Value="type MethodDispatcherBase = class&#xA;    interface IMethodDispatcher" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="700a6-101">このクラスは、リモート オブジェクトのインターフェイスまたはメソッドに、クライアントからの要求をディスパッチします。</span><span class="sxs-lookup"><span data-stu-id="700a6-101">This class dispatches requests from the client to the interface/method of the remoted object.</span></span>
            <span data-ttu-id="700a6-102">このクラスは、リモート処理のコード ジェネレーターによって使用されます。</span><span class="sxs-lookup"><span data-stu-id="700a6-102">This class is used by remoting code generator.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MethodDispatcherBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase.#ctor" />
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
    <Member MemberName="ContinueWith">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;object&gt; ContinueWith (System.Threading.Tasks.Task task);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;object&gt; ContinueWith(class System.Threading.Tasks.Task task) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase.ContinueWith(System.Threading.Tasks.Task)" />
      <MemberSignature Language="F#" Value="member this.ContinueWith : System.Threading.Tasks.Task -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="methodDispatcherBase.ContinueWith task" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="task" Type="System.Threading.Tasks.Task" />
      </Parameters>
      <Docs>
        <param name="task"><span data-ttu-id="700a6-103">継続タスク</span><span class="sxs-lookup"><span data-stu-id="700a6-103">continuation task</span></span></param>
        <summary>
            <span data-ttu-id="700a6-104">内部 - サービスのリモート処理で使用されます。</span><span class="sxs-lookup"><span data-stu-id="700a6-104">Internal - used by Service remoting</span></span>
            </summary>
        <returns>
            <span data-ttu-id="700a6-105">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="700a6-105">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispatch">
      <MemberSignature Language="C#" Value="public abstract void Dispatch (object objectImplementation, int methodId, object messageBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispatch(object objectImplementation, int32 methodId, object messageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase.Dispatch(System.Object,System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Sub Dispatch (objectImplementation As Object, methodId As Integer, messageBody As Object)" />
      <MemberSignature Language="F#" Value="abstract member Dispatch : obj * int * obj -&gt; unit" Usage="methodDispatcherBase.Dispatch (objectImplementation, methodId, messageBody)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.IMethodDispatcher.Dispatch(System.Object,System.Int32,System.Object)</InterfaceMember>
      </Implements>
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
        <param name="objectImplementation"></param>
        <param name="methodId"></param>
        <param name="messageBody"></param>
        <summary>
            <span data-ttu-id="700a6-106">このメソッドは、リモート オブジェクトによって実装されるインターフェイスの指定したメソッド Id に一方向のメッセージのディスパッチに使用します。</span><span class="sxs-lookup"><span data-stu-id="700a6-106">This method is used to dispatch one way messages to the specified methodId of the interface implemented by the remoted object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DispatchAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;object&gt; DispatchAsync (object objectImplementation, int methodId, object requestBody, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;object&gt; DispatchAsync(object objectImplementation, int32 methodId, object requestBody, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase.DispatchAsync(System.Object,System.Int32,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DispatchAsync : obj * int * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="methodDispatcherBase.DispatchAsync (objectImplementation, methodId, requestBody, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.IMethodDispatcher.DispatchAsync(System.Object,System.Int32,System.Object,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
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
        <param name="objectImplementation"></param>
        <param name="methodId"></param>
        <param name="requestBody"></param>
        <param name="cancellationToken"></param>
        <summary>
            <span data-ttu-id="700a6-107">このメソッドは、リモート オブジェクトによって実装されるインターフェイスの指定したメソッド Id への要求のディスパッチに使用されます。</span><span class="sxs-lookup"><span data-stu-id="700a6-107">This method is used to dispatch request to the specified methodId of the interface implemented by the remoted object.</span></span>
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMethodName">
      <MemberSignature Language="C#" Value="public string GetMethodName (int methodId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetMethodName(int32 methodId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase.GetMethodName(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMethodName (methodId As Integer) As String" />
      <MemberSignature Language="F#" Value="abstract member GetMethodName : int -&gt; string&#xA;override this.GetMethodName : int -&gt; string" Usage="methodDispatcherBase.GetMethodName methodId" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Remoting.IMethodDispatcher.GetMethodName(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="methodId"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterfaceId">
      <MemberSignature Language="C#" Value="public int InterfaceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 InterfaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase.InterfaceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InterfaceId As Integer" />
      <MemberSignature Language="F#" Value="member this.InterfaceId : int" Usage="Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase.InterfaceId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Services.Remoting.IMethodDispatcher.InterfaceId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="700a6-108">インターフェイス Id を使用して、リモート処理インターフェイスを識別します。</span><span class="sxs-lookup"><span data-stu-id="700a6-108">Interface Id is used to identify remoting Interfaces.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>