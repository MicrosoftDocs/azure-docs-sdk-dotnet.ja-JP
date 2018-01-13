<Type Name="HybridConnectionClient" FullName="Microsoft.Azure.Relay.HybridConnectionClient">
  <TypeSignature Language="C#" Value="public class HybridConnectionClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HybridConnectionClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.HybridConnectionClient" />
  <TypeSignature Language="VB.NET" Value="Public Class HybridConnectionClient" />
  <TypeSignature Language="F#" Value="type HybridConnectionClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            新しい送信側 HybridConnections を開始するため、クライアントを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : string -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient connectionString" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">使用する接続文字列。  この接続文字列には、EntityPath プロパティを含める必要があります。</param>
        <summary>新しいインスタンスを作成<see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" />指定された接続文字列を使用します。</summary>
        <returns>新しく作成された<see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" />インスタンス。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">場合にスローされるの形式、<paramref name="connectionString" />パラメーターが正しくありません。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : Uri -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address">HybridConnections をリッスンするアドレス。  このアドレスは、"sb://contoso.servicebus.windows.net/yourhybridconnection"の形式でなければなりません。</param>
        <summary>
            クライアント認証は必要ありません HybridConnections を開始するための新しい HybridConnectionClient インスタンスを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (string connectionString, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String, path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : string * string -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient (connectionString, path)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">使用する接続文字列。 この接続文字列には、EntityPath プロパティは含めないでください。</param>
        <param name="path">HybridConnection へのパス。</param>
        <summary>新しいインスタンスを作成<see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" />から接続文字列と HybridConection パスを指定します。 接続文字列で使用しない場合にのみ、このオーバー ロードを使用して、<see cref="P:Microsoft.Azure.Relay.RelayConnectionStringBuilder.EntityPath" />プロパティです。</summary>
        <returns>作成された <see cref="T:Microsoft.Azure.Relay.HybridConnectionClient" />。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">場合にスローされるの形式、<paramref name="connectionString" />パラメーターが正しくありません。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HybridConnectionClient (Uri address, Microsoft.Azure.Relay.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.Relay.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.#ctor(System.Uri,Microsoft.Azure.Relay.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.HybridConnectionClient : Uri * Microsoft.Azure.Relay.TokenProvider -&gt; Microsoft.Azure.Relay.HybridConnectionClient" Usage="new Microsoft.Azure.Relay.HybridConnectionClient (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.Relay.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">HybridConnections をリッスンするアドレス。  このアドレスは、"sb://contoso.servicebus.windows.net/yourhybridconnection"の形式でなければなりません。</param>
        <param name="tokenProvider">ServiceBus に接続するため TokenProvider です。</param>
        <summary>
            クライアント認証と HybridConnections を開始するための新しい HybridConnectionClient インスタンスを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.Azure.Relay.HybridConnectionClient.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この HybridConnection を使用して接続のアドレスを取得します。 HybridConnections をリッスンするアドレス。
            このアドレスは、"sb://contoso.servicebus.windows.net/yourhybridconnection"の形式でなければなりません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConnectionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt; CreateConnectionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionStream&gt; CreateConnectionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.CreateConnectionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConnectionAsync () As Task(Of HybridConnectionStream)" />
      <MemberSignature Language="F#" Value="member this.CreateConnectionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt;" Usage="hybridConnectionClient.CreateConnectionAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionClient/&lt;CreateConnectionAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionStream&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            新しい送信側 HybridConnection を確立し、ストリームを返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.GetRuntimeInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRuntimeInformationAsync () As Task(Of HybridConnectionRuntimeInformation)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;" Usage="hybridConnectionClient.GetRuntimeInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Relay.HybridConnectionClient/&lt;GetRuntimeInformationAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            取得、<see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" />の既定のタイムアウトを使用してこの HybridConnection エンティティです。
            接続文字列で指定しない限り、既定値は 1 分にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuntimeInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt; GetRuntimeInformationAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.HybridConnectionClient.GetRuntimeInformationAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRuntimeInformationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;" Usage="hybridConnectionClient.GetRuntimeInformationAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Relay.HybridConnectionRuntimeInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">観察するキャンセル トークン。</param>
        <summary>
            取得、<see cref="T:Microsoft.Azure.Relay.HybridConnectionRuntimeInformation" />の指定されたキャンセル トークンを使用してこの HybridConnection エンティティです。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionClient.OperationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、HybridConnection を接続するときに使用されるタイムアウトを設定します。  既定値は、70 秒です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Proxy">
      <MemberSignature Language="C#" Value="public System.Net.IWebProxy Proxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.IWebProxy Proxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.Proxy" />
      <MemberSignature Language="VB.NET" Value="Public Property Proxy As IWebProxy" />
      <MemberSignature Language="F#" Value="member this.Proxy : System.Net.IWebProxy with get, set" Usage="Microsoft.Azure.Relay.HybridConnectionClient.Proxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.IWebProxy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または ServiceBus に接続するためのプロキシ情報を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Relay.TokenProvider TokenProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Relay.TokenProvider TokenProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.HybridConnectionClient.TokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenProvider As TokenProvider" />
      <MemberSignature Language="F#" Value="member this.TokenProvider : Microsoft.Azure.Relay.TokenProvider" Usage="Microsoft.Azure.Relay.HybridConnectionClient.TokenProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Relay.TokenProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            HybridConnections を認証するため、TokenProvider を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>