<Type Name="ProxyBase" FullName="Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase">
  <TypeSignature Language="C#" Value="public abstract class ProxyBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ProxyBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ProxyBase" />
  <TypeSignature Language="F#" Value="type ProxyBase = class" />
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
            リモート インターフェイスのプロキシを生成するコード ジェネレーターのリモート処理によって使用される基本クラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ProxyBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            ProxyBase クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueWith">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task ContinueWith (System.Threading.Tasks.Task&lt;object&gt; task);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task ContinueWith(class System.Threading.Tasks.Task`1&lt;object&gt; task) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.ContinueWith(System.Threading.Tasks.Task{System.Object})" />
      <MemberSignature Language="F#" Value="member this.ContinueWith : System.Threading.Tasks.Task&lt;obj&gt; -&gt; System.Threading.Tasks.Task" Usage="proxyBase.ContinueWith task" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase/&lt;ContinueWith&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="task" Type="System.Threading.Tasks.Task&lt;System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="task">リモート メソッド呼び出しの非同期操作を表すタスク。</param>
        <summary>
            応答本文を取得する値を持たない後も続行する、生成されたプロキシ クラスによって呼び出されます。
            </summary>
        <returns>リモート メソッド呼び出しの非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueWithResult&lt;TRetval&gt;">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;TRetval&gt; ContinueWithResult&lt;TRetval&gt; (int interfaceId, int methodId, System.Threading.Tasks.Task&lt;object&gt; task);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;!!TRetval&gt; ContinueWithResult&lt;TRetval&gt;(int32 interfaceId, int32 methodId, class System.Threading.Tasks.Task`1&lt;object&gt; task) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.ContinueWithResult``1(System.Int32,System.Int32,System.Threading.Tasks.Task{System.Object})" />
      <MemberSignature Language="VB.NET" Value="Protected Function ContinueWithResult(Of TRetval) (interfaceId As Integer, methodId As Integer, task As Task(Of Object)) As Task(Of TRetval)" />
      <MemberSignature Language="F#" Value="member this.ContinueWithResult : int * int * System.Threading.Tasks.Task&lt;obj&gt; -&gt; System.Threading.Tasks.Task&lt;'Retval&gt;" Usage="proxyBase.ContinueWithResult (interfaceId, methodId, task)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase/&lt;ContinueWithResult&gt;d__4`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TRetval&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TRetval" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="interfaceId" Type="System.Int32" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="task" Type="System.Threading.Tasks.Task&lt;System.Object&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TRetval">
          <see cref="T:System.Type" />リモート メソッドの値を返します。</typeparam>
        <param name="interfaceId">リモート インターフェイスのインターフェイス Id です。</param>
        <param name="methodId">リモート メソッドのメソッドの Id。</param>
        <param name="task">リモート メソッド呼び出しの非同期操作を表すタスク。</param>
        <summary>
            結果を得るため、応答本文から生成されたプロキシ クラスによって呼び出されます。
            </summary>
        <returns>リモート メソッド呼び出しの非同期操作を表すタスク。
            TRetval の値には、リモート メソッドの戻り値が含まれています。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueWithResultV2&lt;TRetval&gt;">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;TRetval&gt; ContinueWithResultV2&lt;TRetval&gt; (System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; task);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;!!TRetval&gt; ContinueWithResultV2&lt;TRetval&gt;(class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; task) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.ContinueWithResultV2``1(System.Threading.Tasks.Task{Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody})" />
      <MemberSignature Language="VB.NET" Value="Protected Function ContinueWithResultV2(Of TRetval) (task As Task(Of IServiceRemotingResponseMessageBody)) As Task(Of TRetval)" />
      <MemberSignature Language="F#" Value="member this.ContinueWithResultV2 : System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; -&gt; System.Threading.Tasks.Task&lt;'Retval&gt;" Usage="proxyBase.ContinueWithResultV2 task" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase/&lt;ContinueWithResultV2&gt;d__15`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TRetval&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TRetval" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="task" Type="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TRetval">
          <see cref="T:System.Type" />リモート メソッドの値を返します。</typeparam>
        <param name="task">リモート メソッド呼び出しの非同期操作を表すタスク。</param>
        <summary>
            結果を得るため、応答本文から生成されたプロキシ クラスによって呼び出されます。
            </summary>
        <returns>リモート メソッド呼び出しの非同期操作を表すタスク。
            TRetval の値には、リモート メソッドの戻り値が含まれています。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRequestMessageBodyV2">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody CreateRequestMessageBodyV2 (string interfaceName, string methodName, int parameterCount);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody CreateRequestMessageBodyV2(string interfaceName, string methodName, int32 parameterCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.CreateRequestMessageBodyV2(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateRequestMessageBodyV2 (interfaceName As String, methodName As String, parameterCount As Integer) As IServiceRemotingRequestMessageBody" />
      <MemberSignature Language="F#" Value="abstract member CreateRequestMessageBodyV2 : string * string * int -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody&#xA;override this.CreateRequestMessageBodyV2 : string * string * int -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" Usage="proxyBase.CreateRequestMessageBodyV2 (interfaceName, methodName, parameterCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceName" Type="System.String" />
        <Parameter Name="methodName" Type="System.String" />
        <Parameter Name="parameterCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="interfaceName">この呼び出しを呼び出す対象のサービス インターフェイスの完全な名前</param>
        <param name="methodName">この呼び出しを呼び出す対象のサービス インターフェイスのメソッド名</param>
        <param name="parameterCount">サービス内のパラメーターの数のインターフェイス メソッド</param>
        <summary>
            リモート処理の要求メッセージの本文を作成します。 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReturnValue">
      <MemberSignature Language="C#" Value="protected abstract object GetReturnValue (int interfaceId, int methodId, object responseBody);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance object GetReturnValue(int32 interfaceId, int32 methodId, object responseBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.GetReturnValue(System.Int32,System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function GetReturnValue (interfaceId As Integer, methodId As Integer, responseBody As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetReturnValue : int * int * obj -&gt; obj" Usage="proxyBase.GetReturnValue (interfaceId, methodId, responseBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceId" Type="System.Int32" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="responseBody" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="interfaceId">アクター インターフェイスのインターフェイス Id です。</param>
        <param name="methodId">アクター メソッドのメソッドの Id。</param>
        <param name="responseBody">応答本文です。</param>
        <summary>
            キャスト、応答本文を入力して、値を抽出し、派生クラスによって実装されます。
            </summary>
        <returns>戻り値としてのメソッド呼び出しの<see cref="T:System.Object" />します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Invoke">
      <MemberSignature Language="C#" Value="protected void Invoke (int interfaceId, int methodId, object requestMsgBodyValue);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Invoke(int32 interfaceId, int32 methodId, object requestMsgBodyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.Invoke(System.Int32,System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Invoke (interfaceId As Integer, methodId As Integer, requestMsgBodyValue As Object)" />
      <MemberSignature Language="F#" Value="member this.Invoke : int * int * obj -&gt; unit" Usage="proxyBase.Invoke (interfaceId, methodId, requestMsgBodyValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceId" Type="System.Int32" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestMsgBodyValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="interfaceId">リモート インターフェイスの id です。</param>
        <param name="methodId">Invokved するリモート メソッドの id です。</param>
        <param name="requestMsgBodyValue">リモート オブジェクトに送信されるメッセージの本文。</param>
        <summary>
            リモート オブジェクトにメッセージを送信する、生成されたプロキシ クラスによって呼び出されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeAsync">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;object&gt; InvokeAsync (int interfaceId, int methodId, object requestMsgBodyValue, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;object&gt; InvokeAsync(int32 interfaceId, int32 methodId, object requestMsgBodyValue, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.InvokeAsync(System.Int32,System.Int32,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeAsync : int * int * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="proxyBase.InvokeAsync (interfaceId, methodId, requestMsgBodyValue, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase/&lt;InvokeAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceId" Type="System.Int32" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestMsgBodyValue" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="interfaceId">リモート インターフェイスの id です。</param>
        <param name="methodId">Invokved するリモート メソッドの id です。</param>
        <param name="requestMsgBodyValue">要求本文です。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            リモート オブジェクトに要求を送信し、応答を受け取るに生成されたプロキシ クラスによって呼び出されます。
            </summary>
        <returns>表す非同期操作の非同期タスクは、リモート オブジェクトを呼び出します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeAsyncV2">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; InvokeAsyncV2 (int interfaceId, int methodId, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestMsgBodyValue, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; InvokeAsyncV2(int32 interfaceId, int32 methodId, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestMsgBodyValue, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.InvokeAsyncV2(System.Int32,System.Int32,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeAsyncV2 : int * int * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;" Usage="proxyBase.InvokeAsyncV2 (interfaceId, methodId, requestMsgBodyValue, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase/&lt;InvokeAsyncV2&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceId" Type="System.Int32" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestMsgBodyValue" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="interfaceId">リモート インターフェイスの id です。</param>
        <param name="methodId">Invokved するリモート メソッドの id です。</param>
        <param name="requestMsgBodyValue">要求本文です。</param>
        <param name="cancellationToken">キャンセル トークン</param>
        <summary>
            リモート オブジェクトに要求を送信し、応答を受け取るに生成されたプロキシ クラスによって呼び出されます。
            </summary>
        <returns>表す非同期操作の非同期タスクは、リモート オブジェクトを呼び出します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeV2">
      <MemberSignature Language="C#" Value="protected void InvokeV2 (int interfaceId, int methodId, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestMsgBodyValue);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void InvokeV2(int32 interfaceId, int32 methodId, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestMsgBodyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.InvokeV2(System.Int32,System.Int32,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub InvokeV2 (interfaceId As Integer, methodId As Integer, requestMsgBodyValue As IServiceRemotingRequestMessageBody)" />
      <MemberSignature Language="F#" Value="member this.InvokeV2 : int * int * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody -&gt; unit" Usage="proxyBase.InvokeV2 (interfaceId, methodId, requestMsgBodyValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceId" Type="System.Int32" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestMsgBodyValue" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
      </Parameters>
      <Docs>
        <param name="interfaceId">リモート インターフェイスの id です。</param>
        <param name="methodId">Invokved するリモート メソッドの id です。</param>
        <param name="requestMsgBodyValue">リモート オブジェクトに送信されるメッセージの本文。</param>
        <summary>
            リモート オブジェクトに、requestMessage を送信する、生成されたプロキシ クラスによって呼び出されます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>