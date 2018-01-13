<Type Name="MethodDispatcherBaseWithSerializer" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer">
  <TypeSignature Language="C#" Value="public abstract class MethodDispatcherBaseWithSerializer : Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MethodDispatcherBaseWithSerializer extends Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MethodDispatcherBaseWithSerializer&#xA;Inherits MethodDispatcherBase" />
  <TypeSignature Language="F#" Value="type MethodDispatcherBaseWithSerializer = class&#xA;    inherit MethodDispatcherBase" />
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
            クラスは、リモート objectts のインターフェイスまたはメソッドには、クライアントからの要求をディスパッチします。
            このクラスは、リモート処理のコード ジェネレーターによって使用されます。 このクラスは、シリアライザーをキャッシュします。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MethodDispatcherBaseWithSerializer ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.#ctor" />
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
    <Member MemberName="ContinueWithResult&lt;TRetval&gt;">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;object&gt; ContinueWithResult&lt;TRetval&gt; (int methodId, System.Threading.Tasks.Task&lt;TRetval&gt; task);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;object&gt; ContinueWithResult&lt;TRetval&gt;(int32 methodId, class System.Threading.Tasks.Task`1&lt;!!TRetval&gt; task) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.ContinueWithResult``1(System.Int32,System.Threading.Tasks.Task{``0})" />
      <MemberSignature Language="VB.NET" Value="Protected Function ContinueWithResult(Of TRetval) (methodId As Integer, task As Task(Of TRetval)) As Task(Of Object)" />
      <MemberSignature Language="F#" Value="member this.ContinueWithResult : int * System.Threading.Tasks.Task&lt;'Retval&gt; -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="methodDispatcherBaseWithSerializer.ContinueWithResult (methodId, task)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TRetval" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="task" Type="System.Threading.Tasks.Task&lt;TRetval&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TRetval">戻り値</typeparam>
        <param name="methodId">メソッド id</param>
        <param name="task">継続タスク</param>
        <summary>
            内部 - サービスのリモート処理で使用されます。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateResponseBody">
      <MemberSignature Language="C#" Value="protected abstract object CreateResponseBody (int methodId, object retval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance object CreateResponseBody(int32 methodId, object retval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.CreateResponseBody(System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function CreateResponseBody (methodId As Integer, retval As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member CreateResponseBody : int * obj -&gt; obj" Usage="methodDispatcherBaseWithSerializer.CreateResponseBody (methodId, retval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="retval" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="methodId">メソッドの id です。</param>
        <param name="retval">メソッドから返される値。</param>
        <summary>
            このメソッドは、応答を作成する、リモート オブジェクトをメソッドのディスパッチの結果として、指定された戻り値の生成されたメソッドのディスパッチャーによって実装されます。 
            </summary>
        <returns>A<see cref="T:System.Object">オブジェクト</see>クライアントに返送する応答の本体を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispatch">
      <MemberSignature Language="C#" Value="public override void Dispatch (object objectImplementation, int methodId, object messageBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Dispatch(object objectImplementation, int32 methodId, object messageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.Dispatch(System.Object,System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Dispatch (objectImplementation As Object, methodId As Integer, messageBody As Object)" />
      <MemberSignature Language="F#" Value="override this.Dispatch : obj * int * obj -&gt; unit" Usage="methodDispatcherBaseWithSerializer.Dispatch (objectImplementation, methodId, messageBody)" />
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
        <param name="objectImplementation"></param>
        <param name="methodId"></param>
        <param name="messageBody"></param>
        <summary>
            このメソッドは、リモート オブジェクトによって実装されるインターフェイスの指定したメソッド Id に一方向のメッセージのディスパッチに使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DispatchAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;object&gt; DispatchAsync (object objectImplementation, int methodId, object requestBody, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;object&gt; DispatchAsync(object objectImplementation, int32 methodId, object requestBody, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.DispatchAsync(System.Object,System.Int32,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.DispatchAsync : obj * int * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="methodDispatcherBaseWithSerializer.DispatchAsync (objectImplementation, methodId, requestBody, cancellationToken)" />
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
        <param name="objectImplementation"></param>
        <param name="methodId"></param>
        <param name="requestBody"></param>
        <param name="cancellationToken"></param>
        <summary>
            このメソッドは、リモート オブジェクトによって実装されるインターフェイスの指定したメソッド Id への要求のディスパッチに使用されます。
             </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispatch">
      <MemberSignature Language="C#" Value="protected abstract void OnDispatch (int methodId, object remotedObject, object messageBody);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDispatch(int32 methodId, object remotedObject, object messageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.OnDispatch(System.Int32,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnDispatch (methodId As Integer, remotedObject As Object, messageBody As Object)" />
      <MemberSignature Language="F#" Value="abstract member OnDispatch : int * obj * obj -&gt; unit" Usage="methodDispatcherBaseWithSerializer.OnDispatch (methodId, remotedObject, messageBody)" />
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
        <Parameter Name="messageBody" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="methodId">メソッドの id です。</param>
        <param name="remotedObject">リモート オブジェクト インスタンス。</param>
        <param name="messageBody">メッセージ本文</param>
        <summary>
            このメソッドは、リモート オブジェクトによって実装されるインターフェイスの指定したメソッド Id に一方向のメッセージをディスパッチする生成されたメソッドのディスパッチャーによって実装されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispatchAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;object&gt; OnDispatchAsync (int methodId, object remotedObject, object requestBody, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;object&gt; OnDispatchAsync(int32 methodId, object remotedObject, object requestBody, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.OnDispatchAsync(System.Int32,System.Object,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDispatchAsync : int * obj * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="methodDispatcherBaseWithSerializer.OnDispatchAsync (methodId, remotedObject, requestBody, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="remotedObject" Type="System.Object" />
        <Parameter Name="requestBody" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="methodId">メソッドの id です。</param>
        <param name="remotedObject">リモート オブジェクト インスタンス。</param>
        <param name="requestBody">要求本文</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            このメソッドは、リモート オブジェクトによって実装されるインターフェイスの指定したメソッド Id への要求のディスパッチに生成されたメソッドのディスパッチャーによって実装されます。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。 タスクの結果は、メソッドから戻り値です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>